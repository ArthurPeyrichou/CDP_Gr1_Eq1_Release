| Task N°    | Intitulé                 | Affectation |  Status  |
|:-----------|:-------------------------|:-----------:|:--------:|
|#T1|Mise en place le framework Symfony|All|Done|
|#T2|Création d'une base de données sous MySql|All|Done|
|#T3|Identification des caractéristiques d'un visiteur du site|All|Done|
|#T4|Identification des caractéristiques d'un mebre de projet du site|All|Done|
|#T5|Identification des caractéristiques d'un chef de projet du site|All|Done|
|#T6|Identification des caractéristiques d'un Projet|All|Done|
|#T7|Identification des caractéristiques d'une US|All|Done|
|#T8|Identification des caractéristiques d'une Taches|All|Done|
|#T9|Création des tables de la base de données|Khadija|ToDo|
|#T10|Création des dépendances de la base de données|Khadija|ToDo|
|#T11|Créer l'interface d'inscription(en précisant le nom de ce fichier où on crée cet interface,le root,avec les labels "Nom", "Email","Password","ConfirmPassword"et les champs "name","mail","password"et"confirmpassword" et un bouton de type submit appelé "Creer compte")|Arthur|ToDo|
|#T12|Créer un service afin d'ajouter un nouveau membres dans la table Member|Sylvain|ToDo|
|#T13|Créer l'interface de connexion avec les  champs "usermail", "password"|Arthur|ToDo|
|#T14|Créer un service afin de vérifie que le visiteur est bien un membres et que le mot de passe est valide afin de l'authentifier|Sylvain|ToDo|
|#T15|Créer l'interface de création d'un projet avec les champs "projectName", "projectDescription"|Khadija|ToDo|
|#T16|Créer l'interface de création d'une US avec les champs "USName", "USDescription", "USDifficulté", "USPriorité"|Khadija|ToDo|
|#T17|Créer l'interface de création d'une tache avec les champs "tacheName", "tacheDescription", "tacheStatus", "tacheMembre" (facultatif), "tacheDuree"|Arthur|ToDo|
|#T18|Créer un repository afin d'ajouter un projet dans la table Project et de récupérer la liste des projets existant, la liste des projet existant lié a un membre authentifié, un projet spécifique...|Sylvain|ToDo|
|#T19|Créer un repository afin d'ajouter une US dans la table US et de récupérer la liste des US existant, la liste des US existant lié a un projet, une US spécifique...|Sylvain|ToDo|
|#T20|Créer un repository afin d'ajouter une tache dans la table Task et de récupérer la liste des taches existantes, la liste des taches existantes liées a un projet, une tache spécifique...|Sylvain|ToDo|
|#T21|Créer l'interface de la liste des projets avec comme id de liste "projectsList"|Arthur|ToDo|
|#T22|Créer l'interface d'affichage des détails d'un projet|Khadija|ToDo|
|#T23|Création d'une table invitation avec les champs (memberId, projectID, invitationDate, invitationKey).|Arthur|ToDo|
|#T24|Créer un service afin de générer l'invitaion et l'ajouter dans la base de données, valider le couple  (clef d'invitation,date) récupéré afin d'ajouter le membre au projet|Khadija|ToDo|
|#T25|Créer l'interface d'invitation dans un projet avec comme nom de champ "share project with" pour l'utilisateur à inviter|Khadija|ToDo
|#T26|Créer l'interface d'affichage de la liste des membres invité ou dans le projets, avec la possibilité de récupérer le lien d'invitaion des membres pas encore ajoutés et la possibilité de les retirer du projet.|Arthur|ToDo|
|#T27|Envoie de mail lors de l'invitation d'un membre à un projet avec un lien contenant une clef d'invitation|Arthur|ToDo|
|#T28|Créer l'interface de vérification d'invitation|All|ToDo|
|#T29|Tester le formulaire de création de compte|All|ToDo|
|#T30|Tester le formulaire de connexion des membres|All|ToDo|
|#T31|Tester le formulaire d'ajout d'un projet|All|ToDo|
|#T32|Tester le formulaire d'ajout d'une US|All|ToDo|
|#T33|Tester le formulaire d'ajout d'une tache|All|ToDo|
|#T34|Tester le formulaire d'invitation d'un membre à un projet|All|ToDo|
|#T35|Tester les opérations CRUD d'un membre dans la base de données|All|ToDo|
|#T36|Tester les opérations CRUD d'un projet dans la base de données|All|ToDo|
|#T37|Tester les opérations CRUD d'une invitation dans la base de données|All|ToDo|
|#T38|Tester les opérations CRUD d'une US dans la base de données|All|ToDo|
|#T39|Tester les opérations CRUD d'une tache dans la base de données|All|ToDo|
|#T40|Tester la génération et vérification des invitations|All|ToDo|
|#T41|Tester l'envoie de mails d'invitation à un projet|All|ToDo|