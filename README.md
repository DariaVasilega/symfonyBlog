# symfonyBlog
Installation process
 
 1. Run `composer install`
 2. Add database configuration `.env` file
 3. Run `php bin/console doctrine:database:create` to create the database
 4. Run `php bin/console doctrine:migrations:diff` to create migration
 5. Run `php bin/console doctrine:migrations:migrate` to execute the migration
 6. Run `php bin/console doctrine:fixtures:load` to insert the default user into database
 ...
 
plan 
1) add uploading photos. User can set and change own status
2)add online status or last visit 
3) add mailer
4) add registration form (users can't login)
5) add tokens