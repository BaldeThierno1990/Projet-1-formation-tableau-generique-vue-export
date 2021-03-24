# Projet-1


API en Symfony
-------------------

- API:

    *Il n'y a pour l'instant que la table formations dans l'API pour que les groupes puissent avancer*
    - Settings :
        * Dans le dossier du projet "Symfony-rest-api":
            - Faire un : *composer update* pour pouvoir utiliser les outils
            - Créer un fichier *.env.local* et écrire la ligne :
                * DATABASE_URL=mysql://db_user:db_password@127.0.0.1:3306/db_name?serverVersion=5.7
                * *Remplacez db_user par le nom d'utilisateur de base de données, db_password par son mot de passe et db_name par le nom de la base de données.*
    * Utilisation API :
        - Créer la base de données : 
            - php bin/console doctrine:database:create
        - Migrer la base de données : 
            1. php bin/console make:migration
            2. php bin/console doctrine:migrations:migrate
        - Ouvrir l'API dans le navigateur : 
            1. Exécuter dans le terminal à la racine du projet : php -S localhost:8000 -t public/ ou symfony server:start 
            2. Mettre dans l'URL : http://localhost:8000/api
        - Dans l'API pour ajouter/supprimer/modifier 
            * Aller dans les onglets delete/put/pach/post 
                * Clicker sur "Try it out"
                * Insérer les valeurs en JSON, exécuter et vérifier si les données on bien été insérées dans la base.

    > :warning: Si vous avez une erreur d'encodage quand vous faites vos get/post/delete il faut que vous changiez la colonne durée et la mettre sans accents. CHANGER TOUT DANS LA METHODE. (durée -> duree)  