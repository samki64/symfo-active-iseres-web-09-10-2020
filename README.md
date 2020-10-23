# symfo-active-iseres-web-09-10-2020

crud en symfony 5
Suivez les étapes: 
Pour créer le projet:
composer create-project symfony/website-skeleton symfo-active-iseres-web-09-10-2020
configurer la base de données:
DATABASE_URL=‘mysql://db_user:db_password@127.0.0.1:3306/db_name’
db_user: root
db_password: par défaut vide 
db_name: nom de la base de données: 'active_iseres_web'

créer la base de données :
php bin/console doctrine:database:create
Créer des entités:
php bin/console make:entity
nom de classe/entite

Migrations:
php bin/console make:migration puis: php bin/console doctrine:migrations:migrate
Créer crud
php bin/console make:crud 
 >nom de la classe

Ouvrir le projet sur le serveur local
symfony server:start
