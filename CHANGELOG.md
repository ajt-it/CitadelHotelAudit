# Historique des versions

## v1.1 - Juillet 2026

Révision suite aux premiers retours d'audits réels et à la relecture de professionnels de la communauté (notamment Koffi KWADZO).

- **Nouveau domaine : Gouvernance & Politique de sécurité** (8 points de contrôle) - existence et formalisation des politiques de sécurité, classification de l'information, gestion des accès, mots de passe, visiteurs, clés/badges ; responsable sécurité identifié ; revue périodique des politiques
- **Reformulation technologie-agnostique** des points de contrôle réseau : les questions de segmentation ne présupposent plus l'usage de VLAN (VLAN, pare-feu, routeur dédié ou séparation physique sont tous des méthodes valables - la méthode se documente en Constat) ; le chiffrement Wifi n'est plus lié à une version de protocole précise (WPA2/WPA3)
- **Domaine "Gestion des accès" enrichi** : distinction accès physique/logique/distant, gestion des visiteurs dans les zones techniques
- **Domaine "Sécurité physique" enrichi** : vidéosurveillance de la salle serveur, accès par badge nominatif, registre de gestion des clés
- **Restructuration de la grille Excel** : un onglet dédié par domaine (au lieu d'une seule feuille de 71 lignes) pour une navigation plus claire ; le tableau de bord agrège désormais directement les 9 onglets
- Total : 85 points de contrôle répartis en 9 domaines (contre 71 points / 8 domaines en v1.0)
- Documents mis à jour en conséquence : guide méthodologique et fiche de terrain

## v1.0 - Juillet 2026

Première version publique du framework.

- Grille d'audit : 71 points de contrôle répartis en 8 domaines (Réseau & Infrastructure, Protection des postes/serveurs & supervision, Gouvernance & cycle de vie des accès, Paiement & Terminaux, PMS & Applications métier, Données clients & Confidentialité, Sécurité physique & Organisationnelle, Continuité d'activité & Sauvegardes)
- Scoring automatique pondéré par niveau de risque (Critique/Élevé/Moyen/Faible) et statut (Conforme/Partiel/Non conforme/N/A)
- Tableau de bord avec taux de conformité par domaine et global
- Guide méthodologique complet : logique de notation, glossaire, méthodologie de vérification active (tests de segmentation VLAN), guide de restitution
- Fiche de terrain imprimable (A4 paysage) pour collecte papier sur site
- Identité visuelle Citadel IT Solutions (en-tête, pied de page, filigrane, pagination)

---

*Ce framework est en amélioration continue. Les versions futures intégreront les retours d'audits réels menés sur le terrain.*
