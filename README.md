# Conduite de projet : application de gestion de projet

### Membres du groupe : DELREE Sylvain, PEYRICHOU Arthur, SLAMA Khadija


## BackLog

| Issue N°   | Intitulé                 | Difficulté | Priorité | Statut |
|:-----------|:-------------------------|:----------:|:--------:|:------:|
| 1 | En tant que **visiteur**, je souhaite m'enregistrer via un formulaire en cliquant sur le bouton "s'enregistrer" afin d'accéder à l'application | 3 | HAUT | Faite |
| 2 | En tant que **visiteur**, je souhaite me connecter en cliquant sur le bouton "se connecter" puis en entrant mon adresse email et mon mot de passe afin d'accéder à l'application | 2 | HAUT | Faite |
| 3 | En tant qu'**utilisateur authentifié**, je souhaite me déconnecter en cliquant sur le bouto "déconnexion" dans la barre d'outil de l'application afin d'arrêter (_temporairement_) d'utiliser l'application | 1 | HAUT | Faite |
| 4 | En tant qu'**utilisateur authentifié**, je souhaite lister mes projets et ceux dont je suis contributeur sur ma page d'accueil afin de pouvoir accéder à ceux-ci | 3 | HAUT | Faite |
| 5 | En tant qu'**utilisateur authentifié**, je souhaite créer un projet[(1)](#projectDefinition) en cliquant sur le bouton "nouveau projet" sur ma page d'accueil afin de pouvoir en effectuer la gestion | 2 | HAUT | Faite |
| 6 | En tant que **créateur de projet**, je souhaite ajouter un contributeur à un de mes projets en entrant son adresse email, ce qui lui enverra une invitation à validité limitée, ou bien supprimer un contributeur afin de décider qui peut contribuer à la gestion du projet | 5 | HAUT | Faite |
| 7 | En tant qu'**utilisateur authentifié**, je souhaite accepter une invitation à devenir contributeur d'un projet en cliquant sur le lien d'invitation qui m'a été notifié afin de pouvoir contribuer à la gestion du projet | 5 | HAUT | Faite |
| 8 | En tant que **créateur de projet**, je souhaite modifier les informations liées à un de mes projets en cliquant sur le bouton "éditer" dans les détails du projet afin de les rectifier ou les faire évoluer | 2 | BAS | Faite |
| 9 | En tant que **créateur de projet**, je souhaite supprimer un de mes projets en cliquant sur le bouton "supprimer" dans la liste des projets afin de cesser d'en effectuer la gestion | 5 | BAS | Faite |
| 10 | En tant que **contributeur**, je souhaite lister les issues (**_backlog_**) d'un projet afin de pouvoir les visualiser et y accéder | 3 | HAUT | Faite |
| 11 | En tant que **contributeur**, je souhaite créer une issue[(2)](#issueDefinition) dans un projet afin de pouvoir la gérer | 2 | HAUT | Faite |
| 12 | En tant que **contributeur**, je souhaite modifier une issue afin de rectifier ses informations | 2 | HAUT | Faite |
| 13 | En tant que **contributeur**, je souhaite supprimer une issue (non achevée) afin qu'elle n'apparaisse plus dans la liste | 4 | HAUT | Faite |
| 14 | En tant que **contributeur**, je souhaite lister les tâches d'un projet afin de pouvoir les visualiser et y accéder | 3 | HAUT | Faite |
| 15 | En tant que **contributeur**, je souhaite créer une tâche[(3)](#taskDefinition) dans un projet afin de pouvoir la gérer | 2 | HAUT | Faite |
| 16 | En tant que **contributeur**, je souhaite trier la liste des tâches en fonction de leur statut afin de pouvoir visualiser ce qui est fait/qu'il reste à faire | 3 | HAUT | Faite |
| 17 | En tant que **contributeur**, je souhaite trier la liste des tâches en fonction des issues auxquelles elles se rattachent afin d'identifier les tâches à effectuer pour finir une issue | 3 | HAUT | Faite |
| 18 | En tant que **contributeur**, je souhaite modifier une tâche afin de rectifier ses informations | 2 | HAUT | Faite |
| 19 | En tant que **contributeur**, je souhaite supprimer une tâche (non achevée) afin qu'elle n'apparaisse plus dans la liste | 4 | HAUT | Faite |
| 20 | En tant que **contributeur**, je souhaite lister les sprints d'un projet afin de pouvoir les visualiser et y accéder | 3 | BAS | Faite |
| 21 | En tant que **contributeur**, je souhaite créer un sprint[(4)](#sprintDefinition) afin de pouvoir le gérer | 2 | BAS | Faite |
| 22 | En tant que **contributeur**, je souhaite modifier un sprint afin de rectifier ses informations ou ajouter/supprimer les issues associées | 2 | BAS | Faite |
| 23 | En tant que **contributeur**, je souhaite supprimer un sprint afin qu'il n'apparaisse plus dans la liste | 4 | BAS | Faite |
| 24 | En tant que **contributeur**, je souhaite lister les releases d'un projet afin de pouvoir les visualiser et y accéder | 3 | BAS | Faite |
| 25 | En tant que **contributeur**, je souhaite créer une release[(5)](#releaseDefinition) dans un projet afin de pouvoir la gérer | 2 | BAS | Faite |
| 26 | En tant que **contributeur**, je souhaite modifier une release afin de rectifier ses informations ou ajouter/supprimer les sprints associés | 2 | BAS | Faite |
| 27 | En tant que **contributeur**, je souhaite supprimer une release afin qu'elle n'apparaisse plus dans la liste | 4 | BAS | Faite |
| 28 | En tant que **contributeur**, je souhaite lister les tests d'une issue afin de pouvoir les visualiser et y accéder | 3 | BAS | A faire |
| 29 | En tant que **contributeur**, je souhaite créer un test[(6)](#testDefinition) pour une issue afin de pouvoir le gérer | 2 | BAS | Faite |
| 30 | En tant que **contributeur**, je souhaite modifier un test afin de rectifier ses informations | 2 | BAS | Faite |
| 31 | En tant que **contributeur**, je souhaite supprimer un test afin qu'il n'apparaisse plus dans la liste | 4 | BAS | Faite |
| 32 | En tant que **contributeur**, je souhaite lister les ressources de documentation d'un projet afin de pouvoir les visualiser et y accéder | 4 | BAS | Faite |
| 33 | En tant que **contributeur**, je souhaite ajouter une ressource de documentation[(7)](#docDefinition) dans un projet afin de pouvoir la gérer | 3 | BAS | Faite |
| 34 | En tant que **contributeur**, je souhaite supprimer une ressource de documentation afin qu'elle n'apparaisse plus dans la liste | 4 | BAS | Faite |
| 35 | En tant que **contributeur**, je souhaite visualiser les tâches d'un projet sous forme de calendrier afin de me rendre compte plus aisément du planning du projet | 4 | BAS | A faire |
| 36 | En tant que **contributeur**, je souhaite trier les tâches en fonction des dates de début et de fin afin de restreindre l'affichage du calendier à une période spécifique | 3 | BAS | A faire |
| 37 | En tant que **contributeur**, je souhaite pouvoir marquer une tâche comme étant en cours de réalisation ou la marquer comme terminée depuis la liste afin de suivre l'avancement du projet | 3 | HAUT | Faite |
| 38 | En tant que **contributeur**, je souhaite pouvoir marquer renseigner quels tests de la liste passent et lesquels ne passent pas et visualiser le pourcentage de tests qui passent afin d'avoir une idée des issues à retravailler | 3 | BAS | Faite |
| 39 | En tant que **contributeur**, je souhaite pouvoir visualiser l'avancement du projet sous forme d'un Burn Down Chart afin de déterminer la vélocité de l'équipe. | 3 | BAS | Faite |
| 40 | En tant que **contributeur**, je souhaite pouvoir organiser et participer à un Planning Poker avec les autres contributeurs d'un projet (lors de l'ajout d'une issue) afin de déterminer collectivement la difficulté nécessaire à la réalisation de mes issues | 5 | BAS | Faite |
| 41 | En tant que **contributeur**, je souhaite pouvoir créer/modifier/supprimer une tâche directement dans un sprint et non pas au niveau global afin de pouvoir gérer les tâches après le début d'un sprint. | 3 | BAS | Faite |
| 42 | En tant que **membre**, je souhaite pouvoir demander à récupérer mon mot de passe via un lien envoyé par email en cliquant sur un bouton "Mot de passe oublié" sur l'écran de connexion si je l'ai oublié afin de pouvoir me connecter à nouveau. | 3 | BAS | A faire |
| 43 | En tant que **contributeur**, je souhaite pouvoir être notifié lors de changements dans le projet: départs/ajout d'un membre et fin d'un planing poker, afin de me tenir informé de l'activité du projet. | 3 | BAS | Faite |
| 44 | En tant que **contributeur**, je souhaite pouvoir migrer les tâches et les issues pas términé d'un sprint terminé vers un sprint encore d'actualité. | 3 | BAS | Faite |

#### Définition des rôles :
* **Visiteur** : un utilisateur non authentifié, soit parce qu'il n'est pas enregistré, soit parce qu'il ne s'est pas connecté.
* **Utilisateur authentifié** : un utilisateur enregistré qui s'est connecté à l'application.
* **Contributeur** : un _utilisateur authentifié_ qui a été ajouté à un projet par le _créateur du projet_. Il a alors le rôle de _contributeur_ dans letdit projet et peut effectuer la gestion des différents aspects de celui-ci.
* **Créateur de projet** : un _utilisateur authentifié_ qui a créé un projet. Il a alors le rôle de _créateur de projet_ dans ledit projet et peut en effectuer la gestion ainsi qu'éditer ses informations et le supprimer. **_Note importante : un créateur de projet est également contributeur dans ses projets_**.

<a id="projectDefinition"></a>(1) Champs constitutifs d'un projet :
* Nom
* Description
* Identifiant (autogénéré)
* Date de création [(8)](#dateNote)

<a id="issueDefinition"></a>(2) Champs constitutifs d'une issue :
* Numéro (autogénéré)
* Description
* Identifiant (autogénéré)
* Difficulté (un chiffre de 1 à 10)
* Priorité (un chiffre de 1 à 10)
* Un sprint pendant lequel l'issue doit être réalisée

<a id="taskDefinition"></a>(3) Champs constitutifs d'une tâche :
* Numéro (autogénéré)
* Description
* Identifiant (autogénéré)
* Statut (à faire, en cours, fait)
* Un membre à qui la tâche est assignée (facultatif)
* Une ou plusieurs issue(s) associée(s)
* Ressources nécessaires à sa réalisation (en jour/homme)

<a id="sprintDefinition"></a>(4) Champs constitutifs d'un sprint :
* Numéro (autogénéré)
* Identifiant (autogénéré)
* Date de début [(8)](#dateNote)
* Date de fin [(8)](#dateNote)
* Une ou plusieurs issue(s) à implémenter

<a id="releaseDefinition"></a>(5) Champs constitutifs d'une release :
* Numéro (autogénéré)
* Description
* Date
* Identifiant (autogénéré)
* Liste du(des) issues(s) qui y sont implémentées
* Zip ou lien vers les fichiers de la release

<a id="testDefinition"></a>(6) Champs constitutifs d'un test :
* Nom
* Description (scénario)
* Identifiant (autogénéré)
* Une unique issue à laquelle se rapporte le test
* Un indicateur de réussite/échec du test

<a id="docDefinition"></a>(7) Une ressource de documentation est un fichier pouvant être de type divers (_md, latex, html, pdf, txt, pptx, excel,..._)

<a id="dateNote"></a>(8) Les dates seront affichées au format Français (**jj/mm/aaaa**) mais seront stockées et traitées par l'application au format US (**yyyy-mm-dd**).
