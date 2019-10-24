# Conduite de projet : application de gestion de projet

### Membres du groupe : DELREE Sylvain, PEYRICHOU Arthur, SLAMA Khadija


## BackLog

| Issue N°   | Intitulé                 | Difficulté | Priorité | Statut |
|:-----------|:-------------------------|:----------:|:--------:|:------:|
| 1 | En tant que **visiteur**, je souhaite m'enregistrer via un formulaire en cliquant sur le bouton "s'enregistrer" afin d'accéder à l'application | 3 | HAUT | A faire |
| 2 | En tant que **visiteur**, je souhaite me connecter en cliquant sur le bouton "se connecter" puis en entrant mon adresse email et mon mot de passe afin d'accéder à l'application | 2 | HAUT | A faire |
| 3 | En tant qu'**utilisateur authentifié**, je souhaite me déconnecter en cliquant sur le bouto "déconnexion" dans la barre d'outil de l'application afin d'arrêter (_temporairement_) d'utiliser l'application | 1 | HAUT | A faire |
| 4 | En tant qu'**utilisateur authentifié**, je souhaite lister mes projets et ceux dont je suis contributeur sur ma page d'accueil afin de pouvoir accéder à ceux-ci | 3 | HAUT | A faire |
| 5 | En tant qu'**utilisateur authentifié**, je souhaite créer un projet[(1)](#projectDefinition) en cliquant sur le bouton "nouveau projet" sur ma page d'accueil afin de pouvoir en effectuer la gestion | 2 | HAUT | A faire |
| 6 | En tant que **créateur de projet**, je souhaite ajouter un contributeur à un de mes projets en entrant son adresse email, ce qui lui enverra une invitation à validité limitée par email, ou bien supprimer un contributeur afin de décider qui peut contribuer à la gestion du projet | 5 | HAUT | A faire |
| 7 | En tant qu'**utilisateur authentifié**, je souhaite accepter une invitation à devenir contributeur d'un projet en cliquant sur le lien d'invitation qui m'a été envoyé par mail par le créateur afin de pouvoir contribuer à la gestion du projet | 5 | HAUT | A faire|
| 8 | En tant que **créateur de projet**, je souhaite modifier les informations liées à un de mes projets en cliquant sur le bouton "éditer" dans les détails du projet afin de les rectifier ou les faire évoluer | 2 | BAS | A faire |
| 9 | En tant que **créateur de projet**, je souhaite supprimer un de mes projets en cliquant sur le bouton "supprimer" dans la liste des projets afin de cesser d'en effectuer la gestion | 5 | BAS | A faire |
| 10 | En tant que **contributeur**, je souhaite lister les issues (**_backlog_**) d'un projet afin de pouvoir les visualiser et y accéder | 3 | HAUT | A faire |
| 11 | En tant que **contributeur**, je souhaite créer une issue[(2)](#issueDefinition) dans un projet afin de pouvoir la gérer | 2 | HAUT | A faire |
| 12 | En tant que **contributeur**, je souhaite modifier une issue afin de rectifier ses informations | 2 | HAUT | A faire |
| 13 | En tant que **contributeur**, je souhaite supprimer une issue (non achevée) afin qu'elle n'apparaisse plus dans la liste | 4 | HAUT | A faire |
| 14 | En tant que **contributeur**, je souhaite lister les tâches d'un projet afin de pouvoir les visualiser et y accéder | 3 | HAUT | A faire |
| 15 | En tant que **contributeur**, je souhaite créer une tâche[(3)](#taskDefinition) dans un projet afin de pouvoir la gérer | 2 | HAUT | A faire |
| 16 | En tant que **contributeur**, je souhaite trier la liste des tâches en fonction de leur statut afin de pouvoir visualiser ce qui est fait/qu'il reste à faire | 3 | HAUT | A faire |
| 17 | En tant que **contributeur**, je souhaite trier la liste des tâches en fonction des issues auxquelles elles se rattachent afin d'identifier les tâches à effectuer pour finir une issue | 3 | HAUT | A faire |
| 18 | En tant que **contributeur**, je souhaite modifier une tâche afin de rectifier ses informations | 2 | HAUT | A faire |
| 19 | En tant que **contributeur**, je souhaite supprimer une tâche (non achevée) afin qu'elle n'apparaisse plus dans la liste | 4 | HAUT | A faire |
| 20 | En tant que **contributeur**, je souhaite lister les sprints d'un projet afin de pouvoir les visualiser et y accéder | 3 | BAS | A faire |
| 21 | En tant que **contributeur**, je souhaite créer un sprint[(4)](#sprintDefinition) afin de pouvoir le gérer | 2 | BAS | A faire |
| 22 | En tant que **contributeur**, je souhaite modifier un sprint afin de rectifier ses informations ou ajouter/supprimer les issues associées | 2 | BAS | A faire |
| 23 | En tant que **contributeur**, je souhaite supprimer un sprint afin qu'il n'apparaisse plus dans la liste | 4 | BAS | A faire |
| 24 | En tant que **contributeur**, je souhaite lister les releases d'un projet afin de pouvoir les visualiser et y accéder | 3 | BAS | A faire |
| 25 | En tant que **contributeur**, je souhaite créer une release[(5)](#releaseDefinition) dans un projet afin de pouvoir la gérer | 2 | BAS | A faire |
| 26 | En tant que **contributeur**, je souhaite modifier une release afin de rectifier ses informations ou ajouter/supprimer les sprints associés | 2 | BAS | A faire |
| 27 | En tant que **contributeur**, je souhaite supprimer une release afin qu'elle n'apparaisse plus dans la liste | 4 | BAS | A faire |
| 28 | En tant que **contributeur**, je souhaite lister les tests d'une issue afin de pouvoir les visualiser et y accéder | 3 | BAS | A faire |
| 29 | En tant que **contributeur**, je souhaite créer un test[(6)](#testDefinition) pour une issue afin de pouvoir le gérer | 2 | BAS | A faire |
| 30 | En tant que **contributeur**, je souhaite modifier un test afin de rectifier ses informations | 2 | BAS | A faire |
| 31 | En tant que **contributeur**, je souhaite supprimer un test afin qu'il n'apparaisse plus dans la liste | 4 | BAS | A faire |
| 32 | En tant que **contributeur**, je souhaite lister les ressources de documentation d'un projet afin de pouvoir les visualiser et y accéder | 4 | BAS | A faire |
| 33 | En tant que **contributeur**, je souhaite ajouter une ressource de documentation[(7)](#docDefinition) dans un projet afin de pouvoir la gérer | 3 | BAS | A faire |
| 34 | En tant que **contributeur**, je souhaite supprimer une ressource de documentation afin qu'elle n'apparaisse plus dans la liste | 4 | BAS | A faire |
| 35 | En tant que **contributeur**, je souhaite visualiser les tâches d'un projet sous forme de calendrier afin de me rendre compte plus aisément du planning du projet | 4 | BAS | A faire |
| 36 | En tant que **contributeur**, je souhaite trier les tâches en fonction des dates de début et de fin afin de restreindre l'affichage du calendier à une période spécifique | 3 | BAS | A faire |

#### Définition des rôles :
* **Visiteur** : un utilisateur non authentifié, soit parce qu'il n'est pas enregistré, soit parce qu'il ne s'est pas connecté.
* **Utilisateur authentifié** : un utilisateur enregistré qui s'est connecté à l'application.
* **Contributeur** : un _utilisateur authentifié_ qui a été ajouté à un projet par le _créateur du projet_. Il a alors le rôle de _contributeur_ dans letdit projet et peut effectuer la gestion des différents aspects de celui-ci.
* **Créateur de projet** : un _utilisateur authentifié_ qui a créé un projet. Il a alors le rôle de _créateur de projet_ dans ledit projet et peut en effectuer la gestion ainsi qu'éditer ses informations et le supprimer. **_Note importante : un créateur de projet est également contributeur dans ses projets_**.

<a id="projectDefinition"></a>(1) Champs constitutifs d'un projet :
* Nom
* Description
* Identifiant (a priori autogénéré)
* Date de création [(8)](#dateNote)

<a id="issueDefinition"></a>(2) Champs constitutifs d'une issue :
* Nom (numéro)
* Description
* Identifiant (autogénéré)
* Difficulté (un chiffre de 1 à 10)
* Priorité (un chiffre de 1 à 10) (un code couleur sera utilisé pour identifier visuellement la priorité des issues)
* Un sprint pendant lequel l'issue doit être réalisée

<a id="taskDefinition"></a>(3) Champs constitutifs d'une tâche :
* Nom (numéro)
* Description
* Identifiant (autogénéré)
* Status (à faire, en cours, fait, rendu)
* Un membre à qui la tâche est assignée (facultatif)
* Une ou plusieurs issue(s) associée(s)
* Temps nécessaire à sa réalisation (durée en jours)

<a id="sprintDefinition"></a>(4) Champs constitutifs d'un sprint :
* Nom (numéro)
* Identifiant (autogénéré)
* Date de début [(8)](#dateNote)
* Date de fin [(8)](#dateNote)

<a id="releaseDefinition"></a>(5) Champs constitutifs d'une release :
* Nom (numéro)
* Description
* Identifiant (autogénéré)
* Liste du(des) sprint(s) qui la constituent
* Zip ou lien vers les fichiers de la release

<a id="testDefinition"></a>(6) Champs constitutifs d'un test :
* Nom (numéro)
* Description
* Identifiant (autogénéré)
* Une unique issue à laquelle se rapporte le test

<a id="docDefinition"></a>(7) Une ressource de documentation est un fichier pouvant être de type divers (_md, latex, html, pdf, txt, pptx, excel,..._)

<a id="dateNote"></a>(8) Les dates seront affichées au format Français (**jj/mm/aaaa**) mais seront stockées et traitées par l'application au format US (**yyyy-mm-dd**).