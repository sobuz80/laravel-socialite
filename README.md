<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400"></a></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## About Laravel

Laravel is a web application framework with expressive, elegant syntax. We believe development must be an enjoyable and creative experience to be truly fulfilling. Laravel takes the pain out of development by easing common tasks used in many web projects, such as:


###
#composer require laravel/ui --dev
#php artisan ui bootstrap --auth
#composer require laravel/ui
#php artisan ui:auth
#php artisan serve
#php artisan migrate
#composer require laravel/socialite






****
Laravel Socialite (Social Login) - Login with google, facebook and github
Clone this repo
https://github.com/samironbarai/laravel-socialite.git
Install composer packages
$ cd laravel-socialite
$ composer install
Create and setup .env file
make a copy of .env.example and rename to .env
$ copy .env.example .env
$ php artisan key:generate
put database credentials in .env file
Create app for google, facebook and github
For google app
https://console.developers.google.com/
For facebook app
https://developers.facebook.com/apps/
For gitgub app
https://github.com/settings/developers

Put all ids and secrets in .env file
Migrate and insert records
$ php artisan migrate
