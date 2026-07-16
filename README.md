# Framework d'Audit IT pour Établissements Hôteliers

**Version 1.1 - Juillet 2026**
Un outil gratuit et open source pour auditer l'infrastructure IT d'un hôtel indépendant ou d'un petit groupe hôtelier (environ 30 à 100 chambres) : gouvernance, réseau, paiement, PMS, données clients, sécurité physique, continuité d'activité.

Développé et maintenu par **Citadel IT Solutions** (Lomé, Togo).

## Pourquoi ce framework ?

La grande majorité des hôtels 3-4 étoiles n'ont ni le budget ni le besoin d'un audit PCI-DSS complet par un cabinet certifié, mais font face aux mêmes risques : réseaux mal segmentés, terminaux de paiement mal isolés, comptes PMS partagés, données clients mal protégées. Ce framework comble cet espace : un outil de terrain rigoureux, sans jargon inutile, utilisable par un administrateur système sans expérience d'audit formel.

## Contenu du dépôt

| Fichier | Description |
|---|---|
| `Grille_Audit_IT_Hotelier.xlsx` | Grille de 85 points de contrôle répartis en 9 domaines (un onglet par domaine), avec scoring automatique et tableau de bord |
| `Guide_Methodologique_Audit_IT_Hotelier.docx` | Guide d'utilisation : méthodologie, logique de notation, glossaire, détail par domaine |
| `Fiche_Terrain_Audit_IT_Hotelier.docx` | Fiche imprimable (A4 paysage) à cocher à la main sur site, pour report ultérieur dans l'Excel |

## Périmètre couvert

- Gouvernance & Politique de sécurité
- Réseau & Infrastructure (segmentation, Wifi, vérification active)
- Protection des postes, serveurs & supervision
- Gestion des accès (attribution, départs, traçabilité)
- Paiement & Terminaux (TPE, PCI-DSS, VCC, guichets bancaires)
- PMS & Applications métier
- Données clients & Confidentialité
- Sécurité physique & Organisationnelle
- Continuité d'activité & Sauvegardes

## Comment l'utiliser

1. Lire le Guide méthodologique (section 2 : "Comment utiliser ce document")
2. Imprimer la Fiche de terrain et la faire remplir sur site par l'équipe technique
3. Reporter les résultats dans la Grille Excel - le score et le taux de conformité par domaine se calculent automatiquement (un onglet par domaine)
4. Restituer les résultats à la direction en priorisant les non-conformités à risque Critique/Élevé

## Une note sur les questions techniques

Les points de contrôle décrivent un résultat attendu ("le réseau est segmenté", "le Wifi est chiffré avec un protocole à jour") plutôt qu'une technologie précise (VLAN, pare-feu, WPA2/WPA3...). La méthode utilisée se documente dans la colonne Constat de chaque ligne. Objectif : que la grille reste valable même quand les technologies évoluent.

## Licence

CC BY-SA 4.0 - voir [LICENSE.md](./LICENSE.md). Utilisation libre, y compris commerciale, à condition de créditer Citadel IT Solutions et de partager toute version modifiée sous la même licence.

## Avertissement

Cet outil ne remplace pas un audit PCI-DSS officiel réalisé par un QSA certifié, ni un avis juridique sur la conformité aux lois locales de protection des données.

## Remerciements

La v1.1 intègre les retours de professionnels ayant relu et testé la v1.0 sur le terrain, notamment Koffi KWADZO, dont les observations sur la gouvernance et la formulation des points de contrôle ont significativement enrichi ce framework.

## Contribuer / Signaler un problème

Ce framework est amené à évoluer avec les retours du terrain. Toute suggestion, correction ou retour d'expérience d'audit réel est bienvenu - contactez Citadel IT Solutions.

## Historique des versions

Voir [CHANGELOG.md](./CHANGELOG.md).
