# Simple App Aplik

## use sanctum for token API
- set model hasapitokens
- set middleware ensurefrontendrequest
- set support credential in CORS
- set SESSION_DRIVER = cookie
- set SANCTUM_STATEFUL_DOMAINS=localhost

## API point on user (CRUD) GET POST PUT DELETE
- TODO
- 
## prepare view on web controller
- Use vue js (TODO)
- use blade template (TODO)

## Docker Environment
- use sail (docker environment prepared by laravel)

``composer require laravel/sail –dev
``php artisan sail:install
``./vendor/bin/sail up