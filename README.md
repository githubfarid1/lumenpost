# Lumen PHP Framework

[![Build Status](https://travis-ci.org/laravel/lumen-framework.svg)](https://travis-ci.org/laravel/lumen-framework)
[![Total Downloads](https://img.shields.io/packagist/dt/laravel/framework)](https://packagist.org/packages/laravel/lumen-framework)
[![Latest Stable Version](https://img.shields.io/packagist/v/laravel/framework)](https://packagist.org/packages/laravel/lumen-framework)
[![License](https://img.shields.io/packagist/l/laravel/framework)](https://packagist.org/packages/laravel/lumen-framework)

Laravel Lumen is a stunningly fast PHP micro-framework for building web applications with expressive, elegant syntax. We believe development must be an enjoyable, creative experience to be truly fulfilling. Lumen attempts to take the pain out of development by easing common tasks used in the majority of web projects, such as routing, database abstraction, queueing, and caching.

## Cara Install & Setup Codebase
untuk melakukan instalasi project ini, silahkan ikuti langkah langkah berikut :
1. git clone https://github.com/nurisakbar/marketplace.git
2. cd marketplace
3. composer install
4. cp .env.example .env
5. sesuaikan konfigurasi database
6. php artisan key:generate
7. php artisan jwt:secret
8. php artisan migrate
9. php artisan serve

## Migration & Seeder
untuk menajalankan migrate sekaligus dengan data dummy, silahkan jalankan perintah:<br>
php artisan migrate --seed

## System Requiretmen


    PHP >= 7.3
    OpenSSL PHP Extension
    PDO PHP Extension
    Mbstring PHP Extension



## Referensi
https://github.com/surahmans/Lumen-Design-Pattern<br>
https://github.com/andersao/l5-repository
