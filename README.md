#                            Rapport de Fonctionnement du Projet

## Introduction
Le présent rapport documente le fonctionnement du projet , un système de gestion des patients 
doté d'une interface de login sécurisée. Le système vise à offrir une gestion efficace des 
informations relatives aux patients, en fournissant différentes fonctionnalités selon le rôle 
de l'utilisateur connecté.

## Fonctionnalités Principales

1. Interface de Login
    Le système démarre par une interface de login requérant le nom d'utilisateur et le mot de passe.
    Cette mesure de sécurité garantit que seuls les utilisateurs autorisés peuvent accéder aux 
    fonctionnalités du système.
    ![Capture d’écran 2023-11-23 à 23.43.42.png](..%2F..%2F..%2F..%2Fvar%2Ffolders%2Ff6%2Fvn95x63x1kvc8lfshgcl7v000000gn%2FT%2FTemporaryItems%2FNSIRD_screencaptureui_LrTzQh%2FCapture%20d%E2%80%99%C3%A9cran%202023-11-23%20%C3%A0%2023.43.42.png)

2. Fonctionnalités Administratives
   - Si l'utilisateur connecté possède le rôle d'administrateur, des fonctionnalités supplémentaires
   deviennent accessibles. L'administrateur peut ajouter, supprimer, modifier des entrées de 
   patients et effectuer des recherches avancées dans la base de données. Ceci offre un contrôle 
   complet sur la gestion des informations patients.
   - Une fois authentifié, l'utilisateur est redirigé vers une interface présentant une liste complète
   des patients. Cette liste inclut des informations cruciales telles que le nom, la date de naissance,
   le score du patient, et son statut de santé.
   ![Capture d’écran 2023-11-23 à 23.49.23.png](..%2F..%2F..%2F..%2Fvar%2Ffolders%2Ff6%2Fvn95x63x1kvc8lfshgcl7v000000gn%2FT%2FTemporaryItems%2FNSIRD_screencaptureui_ZlnhaZ%2FCapture%20d%E2%80%99%C3%A9cran%202023-11-23%20%C3%A0%2023.49.23.png)
- Pour ajouter un patient l'utilisateur appuie sur patient en haut dans la barre ensuite sur nouveau.
  ![Capture d’écran 2023-11-24 à 09.04.53.png](..%2F..%2F..%2F..%2Fvar%2Ffolders%2Ff6%2Fvn95x63x1kvc8lfshgcl7v000000gn%2FT%2FTemporaryItems%2FNSIRD_screencaptureui_rZwnUC%2FCapture%20d%E2%80%99%C3%A9cran%202023-11-24%20%C3%A0%2009.04.53.png)
- Ensuite il rempli les champs (nom,date de naissance,score et malade) et il enregistre le patient
  en appuiyant sur le bouton save
  ![Capture d’écran 2023-11-24 à 09.11.03.png](..%2F..%2F..%2F..%2Fvar%2Ffolders%2Ff6%2Fvn95x63x1kvc8lfshgcl7v000000gn%2FT%2FTemporaryItems%2FNSIRD_screencaptureui_zA8YLV%2FCapture%20d%E2%80%99%C3%A9cran%202023-11-24%20%C3%A0%2009.11.03.png)
- si l'administrateur veut modifier un utilisateur prenons comme exemple celui a l'id=2 on modifie
  les informations et on appuie sur save.
 ![Capture d’écran 2023-11-23 à 23.58.07.png](..%2F..%2F..%2F..%2Fvar%2Ffolders%2Ff6%2Fvn95x63x1kvc8lfshgcl7v000000gn%2FT%2FTemporaryItems%2FNSIRD_screencaptureui_qJLnz0%2FCapture%20d%E2%80%99%C3%A9cran%202023-11-23%20%C3%A0%2023.58.07.png)
- Et pour supprimer un patient toujours comme exemple celui a l'id=2 on appuie sur DELETE.
  ![Capture d’écran 2023-11-24 à 00.01.00.png](..%2F..%2F..%2F..%2Fvar%2Ffolders%2Ff6%2Fvn95x63x1kvc8lfshgcl7v000000gn%2FT%2FTemporaryItems%2FNSIRD_screencaptureui_DAMsiL%2FCapture%20d%E2%80%99%C3%A9cran%202023-11-24%20%C3%A0%2000.01.00.png)
- En confirmant la suppression en appuiyant sur ok.
  ![Capture d’écran 2023-11-24 à 00.02.13.png](..%2F..%2F..%2F..%2Fvar%2Ffolders%2Ff6%2Fvn95x63x1kvc8lfshgcl7v000000gn%2FT%2FTemporaryItems%2FNSIRD_screencaptureui_rhHhkr%2FCapture%20d%E2%80%99%C3%A9cran%202023-11-24%20%C3%A0%2000.02.13.png)
- Et il a la possibilité de rechercher un patient
  ![Capture d’écran 2023-11-24 à 08.57.12.png](..%2F..%2F..%2F..%2Fvar%2Ffolders%2Ff6%2Fvn95x63x1kvc8lfshgcl7v000000gn%2FT%2FTemporaryItems%2FNSIRD_screencaptureui_KHxE7d%2FCapture%20d%E2%80%99%C3%A9cran%202023-11-24%20%C3%A0%2008.57.12.png)
- 