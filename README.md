# Agenda familial — projet d'application

**Statut :** idée / cadrage initial. Aucune fonctionnalité ni technologie n'est encore validée.

## Objectif

Concevoir une application d'agenda familial pour centraliser, si cela correspond aux besoins, les rendez-vous et activités de la famille.

## Fonctionnalités à étudier

- [ ] Calendrier partagé avec vue jour, semaine et mois
- [ ] Activités et rendez-vous de chaque membre de la famille
- [ ] Rappels et notifications
- [ ] Événements récurrents (école, loisirs, rendez-vous)
- [ ] Affichage adapté aux téléphones et éventuellement aux tablettes
- [ ] Gestion des autorisations et de la confidentialité des données familiales
- [ ] Synchronisation ou export avec des calendriers existants, si souhaité

## Décisions à prendre

| Sujet | État |
| --- | --- |
| Plateforme (Android, Web ou les deux) | À définir |
| Technologie | À définir |
| Stockage et synchronisation | À définir |
| Utilisateurs et rôles | À définir |
| Hébergement local sur le homelab R+2 ou autre | À étudier |
| Mode hors ligne | À étudier |

## Prochaines étapes

- [ ] Définir les besoins prioritaires
- [ ] Choisir les appareils compatibles
- [ ] Réaliser une première maquette
- [ ] Définir une architecture minimale et sécurisée
- [ ] Créer un premier prototype
- [ ] Tester l'utilisation avec la famille

## Projets open source à étudier

Ces liens sont des **références à examiner**, pas des dépendances adoptées. Vérifier la maintenance, les fonctionnalités, la documentation d'installation, les licences et la sécurité avant toute réutilisation.

| Projet | Dépôt GitHub | Intérêt pour l'agenda familial | Licence indiquée lors de la recherche (à confirmer) |
| --- | --- | --- | --- |
| OpenFamily | [NexaFlowFrance/OpenFamily](https://github.com/NexaFlowFrance/OpenFamily) | Agenda, tâches, planning familial, interface française, PWA | AGPL-3.0 |
| Tribu | [itsDNNS/tribu](https://github.com/itsDNNS/tribu) | Calendrier partagé, tâches et intégrations (dont CalDAV) | MIT |
| Yuvomi | [ulsklyc/yuvomi](https://github.com/ulsklyc/yuvomi) | Organisation du foyer, menus, courses et agenda | MIT |
| Kinwall | [JohnDuprey/kinwall](https://github.com/JohnDuprey/kinwall) | Tableau de bord familial sur tablette ou écran mural | AGPL-3.0 |
| Musubi | [f-tuma/musubi](https://github.com/f-tuma/musubi) | Calendriers individuels/communs et synchronisation | MIT |

### Comparaison prioritaire

- **OpenFamily** : candidat pour utiliser une solution familiale complète, notamment en français.
- **Tribu** : candidat pour une personnalisation avec intégrations et hébergement local.
- **Yuvomi, Kinwall et Musubi** : alternatives à évaluer selon l'interface, les besoins et les appareils.

### Avant de choisir une base

- [ ] Vérifier que chacun des dépôts et sa documentation sont accessibles et à jour
- [ ] Vérifier les licences dans les dépôts et les obligations de redistribution
- [ ] Tester une installation de démonstration isolée
- [ ] Vérifier les comptes familiaux, permissions, sauvegardes et synchronisation mobile
- [ ] Comparer les options de déploiement sur le homelab R+2
- [ ] Décider entre utiliser une solution existante et développer une application autonome

## Organisation future du dépôt

Ajouter progressivement le code source, les maquettes, la documentation et les instructions d'installation. Ne pas enregistrer d'informations personnelles réelles, mots de passe, clés API ou jetons dans le dépôt public.

## Catalogue

Ce projet est référencé dans [My-apps](https://github.com/berty63/My-apps).
