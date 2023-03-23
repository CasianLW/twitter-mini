<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## ETAPES

### Setup

1. composer create-project laravel/laravel twitter-mini

suivre : https://laravel.com/docs/10.x/starter-kits#laravel-breeze

1.composer require laravel/breeze --dev

1. php artisan breeze:install
1. Choisir blade / vue / react / api
1. ajouter les infos de la database dans le .env
1. run migrations
1. mettre l'adresse du local / website en .env app_url

1. npm install (pour installer les dependences)
1. npm run dev (pour avoir un site vite qui refresh en temps reel les modifications, a faire dans un terminal different de celui de laravel)(si le app_url est mal ecrit, l'erreur va etre indiquée)
1. lancer php artisan serve
1. c'est bon vous avez un systeme d'auth et vite qui refresh chaque changement irt

### Start dev

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
