# Release 3 du 10 Décembre 2019

## Installation :

La release est disponible sur ce dépôt dans l'archive [releases/release3.zip](releases/release3.zip).

Il est possible de l'installer facilement via Docker en se positionnant à la racine de l'archive et en lançant :

``
docker-compose up -d --build
``

Cette commande va créer un conteneur MariaDB, un conteneur PHP/Apache contenant l'application et un conteneur **temporaire** *builder* basé sur Nodejs pour construire et packager les assets Javascript/CSS.

## Issues réalisées

Cette release comporte l'implémentation des issues suivantes (en plus des précedentes releases) :

| Issue N°   | Intitulé                 | Difficulté | Priorité | Statut |
|:-----------|:-------------------------|:----------:|:--------:|:------:|
| 17 | En tant que **contributeur**, je souhaite trier la liste des tâches en fonction des issues auxquelles elles se rattachent afin d'identifier les tâches à effectuer pour finir une issue | 3 | HAUT | Faite |
| 28 | En tant que **contributeur**, je souhaite lister les tests d'une issue afin de pouvoir les visualiser et y accéder | 3 | BAS | Faite |
| 38 | En tant que **contributeur**, je souhaite pouvoir renseigner quels tests de la liste passent et lesquels ne passent pas et visualiser le pourcentage de tests qui passent afin d'avoir une idée des issues à retravailler | 3 | BAS | Faite |
| 32 | En tant que **contributeur**, je souhaite lister les ressources de documentation d'un projet afin de pouvoir les visualiser et y accéder | 4 | BAS | Faite |
| 33 | En tant que **contributeur**, je souhaite ajouter une ressource de documentation dans un projet afin de pouvoir la gérer | 3 | BAS | Faite |
| 34 | En tant que **contributeur**, je souhaite supprimer une ressource de documentation afin qu'elle n'apparaisse plus dans la liste | 4 | BAS | Faite |
| 39 | En tant que **contributeur**, je souhaite pouvoir visualiser l'avancement du projet sous forme d'un Burn Down Chart afin de déterminer la vélocité de l'équipe. | 3 | BAS | Faite |
| 40 | En tant que **contributeur**, je souhaite pouvoir organiser et participer à un Planning Poker avec les autres contributeurs d'un projet (lors de l'ajout d'une issue) afin de déterminer collectivement la difficulté nécessaire à la réalisation de mes issues | 5 | BAS | Faite |
| 41 | En tant que **contributeur**, je souhaite pouvoir créer/modifier/supprimer une tâche directement dans un sprint et non pas au niveau global afin de pouvoir gérer les tâches après le début d'un sprint. | 3 | BAS | Faite |
| 42 | En tant que **membre**, je souhaite pouvoir demander à récupérer mon mot de passe via un lien envoyé par email en cliquant sur un bouton "Mot de passe oublié" sur l'écran de connexion si je l'ai oublié afin de pouvoir me connecter à nouveau. | 3 | BAS | Faite |
| 43 | En tant que **contributeur**, je souhaite pouvoir être notifié lors de changements dans le projet: départs/ajout d'un membre et fin d'un planing poker, afin de me tenir informé de l'activité du projet. | 3 | BAS | Faite |
| 44 | En tant que **contributeur**, je souhaite pouvoir migrer les tâches et les issues pas términé d'un sprint terminé vers un sprint encore d'actualité. | 3 | BAS | Faite |
