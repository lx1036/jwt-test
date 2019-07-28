```bash
composer create-project laravel/laravel test
composer require tymon/jwt-auth:dev-develop --prefer-source
php artisan jwt:secret
php artisan migrate
php artisan make:controller ApiController
php artisan serve
```
