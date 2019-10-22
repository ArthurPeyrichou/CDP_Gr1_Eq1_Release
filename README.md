# Conduite de projet : application de gestion de projet


## BackLog

| Issue N°   | Intitulé                 | Difficulté | Priorité |
|:-----------|:-------------------------|:----------:|:--------:|
| US1 | Page d'inscription pour créer un compte | 1 | HAUT |
| US2 | Page de connexion pour accéder à son compte | 1 | HAUT |
| US3 | Contrôle (bouton) de déconnexion afin de fermer sa session | 1 | HAUT |
| US4 | Page d'accueil affichant la liste des projets d'un utilisateur ainsi que ceux auxquels il est associé | 3 | HAUT |
| US5 | Page de création de projets [(1)](#projectDefinition) | 2 | HAUT |
| US6 | Page permettant d'ajouter ou supprimer des membres dans un projet | 7 | HAUT |
| US7 | Page d'édition d'un projet | 2 | BAS |
| US8 | Page de suppression de projet | 5 | BAS |
| US9 | Page affichant la liste des issues d'un projet (**_backlog_**) | 3 | HAUT |
| US10 | Page de création d'issues [(2)](#issueDefinition) | 2 | HAUT |
| US11 | Page d'édition d'une issue | 2 | HAUT |
| US12 | Page de suppression d'issue (ne permettant que de supprimer des issues non achevées) | 4 | HAUT |
| US13 | Page affichant la liste des tâches d'un projet | 3 | HAUT |
| US14 | Page de création de tâches [(3)](#taskDefinition) | 2 | HAUT |
| US15 | Système de tri des tâches en fonction de leur status | 3 | HAUT |
| US16 | Système de tri des tâches en fonction des issues auxquelles elles se rattachent | 3 | HAUT |
| US17 | Page d'édition d'une tâche | 2 | HAUT |
| US18 | Page de suppression de tâche | 4 | HAUT |
| US19 | Page affichant la liste des sprints d'un projet | 3 | BAS |
| US20 | Page de création de sprints [(4)](#sprintDefinition) | 2 | BAS |
| US21 | Page d'édition d'un sprint | 2 | BAS |
| US22 | Page de suppression de sprint | 4 | BAS |
| US23 | Page affichant la liste des releases d'un projet | 3 | BAS |
| US24 | Page de création de releases [(5)](#releaseDefinition) | 2 | BAS |
| US25 | Page d'édition d'une release | 2 | BAS |
| US26 | Page de suppression de release | 4 | BAS |
| US27 | Page affichant la liste des tests associés à une issue | 3 | BAS |
| US28 | Page de creation de tests [(6)](#testDefinition) | 2 | BAS |
| US29 | Page d'édition d'un test | 2 | BAS |
| US30 | Page de suppression de test | 4 | BAS |
| US31 | Page affichant la liste des ressources de documentation d'un projet | 4 | BAS |
| US32 | Page d'ajout de fichiers (_pdf, txt, pptx, excel,..._) | 3 | BAS |
| US33 | Page de suppression de fichier | 4 | BAS |
| US34 | Page affichant la liste des tâches sous forme de calendrier | 4 | BAS |
| US35 | Système de tri des tâches en fonction des dates de début et de fin | 3 | BAS |

<a id="projectDefinition"></a>(1) Champs constitutifs d'un projet :
* Nom
* Description
* Identifiant (a priori autogénéré)
* Date de création [(7)](#dateNote)

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
* Date de début [(7)](#dateNote)
* Date de fin [(7)](#dateNote)

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

<a id="dateNote"></a>(7) Note sur le format des dates : les dates seront affichées au format Français (**jj/mm/aaaa**) mais seront stockées et traitées par l'application au format US (**yyyy-mm-dd**).