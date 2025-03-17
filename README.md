# Creation d'infrastructure fictive
Création d'une infrastructure basique ( ce projet pose les pierres d'une infrastructure fonctionnelle, de nombreuses améliorations, tant en termes de performance que de sécurité sont tout à fait réalisable ) comprenant plusieurs sous-réseaux, services et serveurs, reliés entre eux grâce à PfSense.

- Segmentation IP selon des tailles de disponibilité personnalisées.
- Création d'un domaine Active Directory (AD) basique.
- Mise en place d'un serveur Web IIS avec certificats SSL/TLS internes et enregistrements DNS pour un accès sécurisé en HTTPS avec un nom de domaine choisi.
- Explication des principes AGLDP.
- Configuration de serveurs Samba pour le stockage de fichiers et les dossiers personnels des clients.
- Mise en place d'un serveur Unbound pour servir de cache DNS avec redirection en cas d'absence dans le cache.
- Déploiement d'un serveur LAMP avec le CMS WordPress.
- Installation d'un serveur GLPI pour la gestion des tickets et des actifs.
- Configuration d'un serveur de base de données MariaDB pour héberger les bases de données des serveurs LAMP et GLPI.
- Mise en œuvre d'un serveur de supervision Nagios.
- Création de scripts personnalisés (Bash/PowerShell) pour automatiser la gestion des dossiers personnels des clients et la base de données du serveur GLPI.
