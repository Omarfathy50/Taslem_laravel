







Steps:

INSTALL:
composer install

MIGRATE AND SEED:
php artisan migrate

php artisan db:seed --class=userSeeder

php artisan db:seed --class=orderSeeder

php artisan db:seed --class=productSeeder

php artisan key:generate

START:
php artisan serve

go to:
http://localhost:8000/login
