# Conduite de projet : application de gestion de projet


## BackLog

_Note sur la priorité : La priorité est notée par un chiffre allant de la priorité la plus haute (1) à  la plus basse (7)_ 

| Issue N°   | Intitulé                 | Difficulté | Priorité |
|:-----------|:-------------------------|:----------:|:--------:|
| 1.1 | Page d'inscription pour créer un compte | 1 | 1 |
| 1.2 | Page de connexion pour accéder à son compte | 1 | 1 |
| 1.3 | Contrôle (bouton) de déconnexion afin de fermer sa session | 1 | 1 |
| 2.1 | Page d'accueil affichant la liste des projets d'un utilisateur ainsi que ceux auxquels il est associé | 3 | 2 |
| 2.2 | Page de création de projets [(1)](#projectDefinition) | 2 | 2 |
| 2.3 | Page permettant d'ajouter ou supprimer des membres dans un projet | 7 | 2 |
| 2.4 | Page d'édition d'un projet | 2 | 2 |
| 2.5 | Page de suppression de projet | 5 | 2 |
| 3.1 | Page affichant la liste des sprints d'un projet | 3 | 3 |
| 3.2 | Page de création de sprints [(2)](#sprintDefinition) | 2 | 3 |
| 3.3 | Page d'édition d'un sprint | 2 | 3 |
| 3.4 | Page de suppression de sprint | 4 | 3 |
| 4.1 | Page affichant la liste des tâches d'un projet | 3 | 4 |
| 4.2 | Page de création de tâches [(3)](#taskDefinition) | 2 | 4 |
| 4.3 | Système de tri des tâches en fonction de leur status | 3 | 4 |
| 4.4 | Système de tri des tâches en fonction des issues auxquelles elles se rattachent | 3 | 4 |
| 4.5 | Page d'édition d'une tâche | 2 | 4 |
| 4.6 | Page de suppression de tâche | 4 | 4 |
| 5.1 | Page affichant la liste des issues d'un projet (**_backlog_**) | 3 | 4 |
| 5.2 | Page de création d'issues [(4)](#issueDefinition) | 2 | 4 |
| 5.3 | Page d'édition d'une issue | 2 | 4 |
| 5.4 | Page de suppression d'issue (ne permettant que de supprimer des issues non achevées) | 4 | 4 |
| 6.1 | Page affichant la liste des releases d'un projet | 3 | 5 |
| 6.2 | Page de création de releases [(5)](#releaseDefinition) | 2 | 5 |
| 6.3 | Page d'édition d'une release | 2 | 5 |
| 6.4 | Page de suppression de release | 4 | 5 |
| 7.1 | Page affichant la liste des tests associés à une issue | 3 | 5 |
| 7.2 | Page de creation de tests [(6)](#testDefinition) | 2 | 5 |
| 7.3 | Page d'édition d'un test | 2 | 5 |
| 7.4 | Page de suppression de test | 4 | 5 |
| 8.1 | Page affichant la liste des ressources de documentation d'un projet | 4 | 6 |
| 8.2 | Page d'ajout de fichiers (_pdf, txt, pptx, excel,..._) | 3 | 6 |
| 8.3 | Page de suppression de fichier | 4 | 6 |
| 9.1 | Page affichant la liste des tâches sous forme de calendrier | 4 | 7 |
| 9.2 | Système de tri des tâches en fonction des dates de début et de fin | 3 | 7 |

<a id="projectDefinition"></a>(1) Champs constitutifs d'un projet :
* Nom
* Description
* Identifiant (a priori autogénéré)
* Date de création [(7)](#dateNote)

<a id="sprintDefinition"></a>(2) Champs constitutifs d'un sprint :
* Nom (numéro)
* Identifiant (autogénéré)
* Date de début [(7)](#dateNote)
* Date de fin [(7)](#dateNote)

<a id="taskDefinition"></a>(3) Champs constitutifs d'une tâche :
* Nom (numéro)
* Description
* Identifiant (autogénéré)
* Status (à faire, en cours, fait, rendu)
* Un membre à qui la tâche est assignée (facultatif)
* Une ou plusieurs issue(s) associée(s)
* Temps nécessaire à sa réalisation (durée en jours)

<a id="issueDefinition"></a>(4) Champs constitutifs d'une issue :
* Nom (numéro)
* Description
* Identifiant (autogénéré)
* Difficulté (un chiffre de 1 à 10)
* Priorité (un chiffre de 1 à 10) (un code couleur sera utilisé pour identifier visuellement la priorité des issues)
* Un sprint pendant lequel l'issue doit être réalisée

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