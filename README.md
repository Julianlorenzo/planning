# planning
# README.md
## Projet : Gestion de planning pour entreprise de bâtiment

Objectif : Développer une application web complète permettant de gérer des chantiers, planifier les ouvriers et le matériel, et visualiser tout cela sur un calendrier.

### Spécifications :
- Back-end : Node.js + Express + Sequelize + PostgreSQL.
- Front-end : React + FullCalendar + Axios.
- Authentification : JWT.
- Rôles utilisateurs : Admin, Chef de chantier, Ouvrier.
- Export des plannings en PDF / Excel.
- Notifications par e-mail pour rappel de début de chantier.

À partir de cette description, générer :
1. Les fichiers de configuration (package.json, .env.example, etc.).
2. Les modèles Sequelize (Chantier, Utilisateur, Materiel, Planning).
3. Les routes et controllers pour chaque fonctionnalité.
4. Un composant React principal avec intégration de FullCalendar.
5. Un exemple de workflow GitHub Actions pour les tests et le déploiement.
