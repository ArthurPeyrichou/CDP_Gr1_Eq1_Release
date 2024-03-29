# Release 1 du 8 Novembre 2019

## Récupération de la release :

La release est disponible sur ce dépôt dans l'archive [releases/release1.zip](releases/release1.zip).

Il est possible de l'installer facilement via Docker en se positionnant à la racine de l'archive et en lançant :

``
docker-compose up -d
``

## Issues réalisées

Cette release comporte l'implémentation des issues suivantes :

| Issue N°   | Intitulé                 | Difficulté | Priorité | Statut |
|:-----------|:-------------------------|:----------:|:--------:|:------:|
| 1 | En tant que **visiteur**, je souhaite m'enregistrer via un formulaire en cliquant sur le bouton "s'enregistrer" afin d'accéder à l'application | 3 | HAUT | Faite |
| 2 | En tant que **visiteur**, je souhaite me connecter en cliquant sur le bouton "se connecter" puis en entrant mon adresse email et mon mot de passe afin d'accéder à l'application | 2 | HAUT |Faite |
| 3 | En tant qu'**utilisateur authentifié**, je souhaite me déconnecter en cliquant sur le bouto "déconnexion" dans la barre d'outil de l'application afin d'arrêter (_temporairement_) d'utiliser l'application | 1 | HAUT | Faite |
| 4 | En tant qu'**utilisateur authentifié**, je souhaite lister mes projets et ceux dont je suis contributeur sur ma page d'accueil afin de pouvoir accéder à ceux-ci | 3 | HAUT | Faite |
| 5 | En tant qu'**utilisateur authentifié**, je souhaite créer un projet[(1)](#projectDefinition) en cliquant sur le bouton "nouveau projet" sur ma page d'accueil afin de pouvoir en effectuer la gestion | 2 | HAUT | Faite |
| 10 | En tant que **contributeur**, je souhaite lister les issues (**_backlog_**) d'un projet afin de pouvoir les visualiser et y accéder | 3 | HAUT | Faite |

