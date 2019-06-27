# api-platform

## Prerequisites

### From scratch :
php composer.phar create-project symfony/skeleton project_name

composer req api make

### From this repo :

composer install

## Php server

php -S 127.0.0.1:8000 -t public

database -> adjust DATABASE_URL in .env

front : http://127.0.0.1:8000/api

### Useful links

doc : https://api-platform.com

serialization : https://api-platform.com/docs/core/serialization/

jwt : https://api-platform.com/docs/core/jwt/ & https://github.com/lexik/LexikJWTAuthenticationBundle
