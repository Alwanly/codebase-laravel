<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400"></a></p>

## Laravel Codebase

This repo is contains codebase for develop with framework Laravel.

## Prerequisites

-   php > 7.4
-   composer > 2

## Installing

for local developmnet :

1. Clone this repo
2. Install vendor `composer install`
3. Create local environment configuration form `.env.example`
4. Seed your local database `php artisan migration`
5. Start development server `php artisan serve`

## Unit Test

The test ran using PhpUnit and extentions xdebug.

-   To run unit test `composer test`
-   To generate coverage report `composer test:converage`

## Conding Style

Code style in this repository is enforced using [PHP_CodeSniffer](https://github.com/squizlabs/PHP_CodeSniffer) with the following style guide PSR-12.

Check the `phpcs.xml` for more information about settings PHP_CodeSniffer.

-   To run the codeSniffer `composer phpcs`.
-   To fix style error `composer phpcbf`

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
