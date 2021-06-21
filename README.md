## install

- run mysql server
- create a new database: simple_blog
- import file: app/Database/01-schema.sql
- import file: app/Database/02-fk.sql
- check/fix db connection settings in the app/config.php file (see 'db' section)
- composer install
- composer dump-autoload
- run the app: php -S localhost:8181 -t public# faker-mvc
