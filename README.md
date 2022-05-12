<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400"></a></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>
Its just UI

## How to Setup a Laravel Project You Cloned from Github.com

1. Clone GitHub repo for this project locally
```
git clone https://github.com/abnain-14/laravelecommerce
```
2. cd into your project
```
cd laravelecommerce
```
3. Install Composer Dependencies
```
composer install
```
4. Install NPM Dependencies
```
npm install
```
5. Create a copy of your .env file
```
cp .env.example .env
```
6. Generate an app encryption key
```
php artisan key:generate
```
7. Create an empty database for our application; in our case the db name is "laravelecommerce"

8. In the .env file, add database information to allow Laravel to connect to the database
In the .env file fill in the DB_HOST, DB_PORT, DB_DATABASE, DB_USERNAME, and DB_PASSWORD options to match the credentials of the database you just created.

9. Migrate the database
```
php artisan migrate
```
10. Run the project
```
php artisan serve
```
## Reference : 
https://devmarketer.io/learn/setup-laravel-project-cloned-github-com/
