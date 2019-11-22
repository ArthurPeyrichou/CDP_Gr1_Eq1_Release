# Release 2 du 22 Novembre 2019

## Installation :

La release est disponible sur ce dépôt dans l'archive [releases/release2.zip](releases/release2.zip).

Il est possible de l'installer facilement via Docker en se positionnant à la racine de l'archive et en lançant :

``
docker-compose up -d
``

Cette commande va créer un conteneur MariaDB, un conteneur PHP/Apache contenant l'application et un conteneur **temporaire** *builder* basé sur Nodejs pour construire et packager les assets Javascript/CSS.

## Issues réalisées

Cette release comporte l'implémentation des issues suivantes (en plus de la release 1) :

| Issue N°   | Intitulé                 | Difficulté | Priorité | Statut |
|:-----------|:-------------------------|:----------:|:--------:|:------:|
| 6 | En tant que **créateur de projet**, je souhaite ajouter un contributeur à un de mes projets en entrant son adresse email, ce qui lui enverra une invitation à validité limitée, ou bien supprimer un contributeur afin de décider qui peut contribuer à la gestion du projet | 5 | HAUT | Faite |
| 7 | En tant qu'**utilisateur authentifié**, je souhaite accepter une invitation à devenir contributeur d'un projet en cliquant sur le lien d'invitation qui m'a été notifié afin de pouvoir contribuer à la gestion du projet | 5 | HAUT | Faite |
| 8 | En tant que **créateur de projet**, je souhaite modifier les informations liées à un de mes projets en cliquant sur le bouton "éditer" dans les détails du projet afin de les rectifier ou les faire évoluer | 2 | BAS | Faite |
| 9 | En tant que **créateur de projet**, je souhaite supprimer un de mes projets en cliquant sur le bouton "supprimer" dans la liste des projets afin de cesser d'en effectuer la gestion | 5 | BAS | Faite |
| 11 | En tant que **contributeur**, je souhaite créer une issue dans un projet afin de pouvoir la gérer | 2 | HAUT | Faite |
| 12 | En tant que **contributeur**, je souhaite modifier une issue afin de rectifier ses informations | 2 | HAUT | Faite |
| 13 | En tant que **contributeur**, je souhaite supprimer une issue (non achevée) afin qu'elle n'apparaisse plus dans la liste | 4 | HAUT | Faite |
| 14 | En tant que **contributeur**, je souhaite lister les tâches d'un projet afin de pouvoir les visualiser et y accéder | 3 | HAUT | Faite |
| 15 | En tant que **contributeur**, je souhaite créer une tâche dans un projet afin de pouvoir la gérer | 2 | HAUT | Faite |
| 16 | En tant que **contributeur**, je souhaite trier la liste des tâches en fonction de leur statut afin de pouvoir visualiser ce qui est fait/qu'il reste à faire | 3 | HAUT | Faite |
| 18 | En tant que **contributeur**, je souhaite modifier une tâche afin de rectifier ses informations | 2 | HAUT | Faite |
| 19 | En tant que **contributeur**, je souhaite supprimer une tâche (non achevée) afin qu'elle n'apparaisse plus dans la liste | 4 | HAUT | Faite |
| 20 | En tant que **contributeur**, je souhaite lister les sprints d'un projet afin de pouvoir les visualiser et y accéder | 3 | BAS | Faite |
| 21 | En tant que **contributeur**, je souhaite créer un sprint afin de pouvoir le gérer | 2 | BAS | Faite |
| 22 | En tant que **contributeur**, je souhaite modifier un sprint afin de rectifier ses informations ou ajouter/supprimer les issues associées | 2 | BAS | Faite |
| 23 | En tant que **contributeur**, je souhaite supprimer un sprint afin qu'il n'apparaisse plus dans la liste | 4 | BAS | Faite |
| 24 | En tant que **contributeur**, je souhaite lister les releases d'un projet afin de pouvoir les visualiser et y accéder | 3 | BAS | Faite |
| 25 | En tant que **contributeur**, je souhaite créer une release dans un projet afin de pouvoir la gérer | 2 | BAS | Faite |
| 26 | En tant que **contributeur**, je souhaite modifier une release afin de rectifier ses informations ou ajouter/supprimer les sprints associés | 2 | BAS | Faite |
| 27 | En tant que **contributeur**, je souhaite supprimer une release afin qu'elle n'apparaisse plus dans la liste | 4 | BAS | Faite |
| 29 | En tant que **contributeur**, je souhaite créer un test pour une issue afin de pouvoir le gérer | 2 | BAS | Faite |
| 30 | En tant que **contributeur**, je souhaite modifier un test afin de rectifier ses informations | 2 | BAS | Faite |
| 31 | En tant que **contributeur**, je souhaite supprimer un test afin qu'il n'apparaisse plus dans la liste | 4 | BAS | Faite |
| 37 | En tant que **contributeur**, je souhaite pouvoir marquer une tâche comme étant en cours de réalisation ou la marquer comme terminée depuis la liste afin de suivre l'avancement du projet | 3 | HAUT | Faite |

