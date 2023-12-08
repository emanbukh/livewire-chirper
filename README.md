## About Livewire-Chirper

A simple application created based on Twitter.com, wherein 'chirps' emulate the action of tweets when posting content.

    * Tackle authentication features like login and registration using Laravel Breeze
    * Handle form for creating a post and display list using livewire component
    * User input is is validate from back end using livewire rule attribute
    * Authorization is handle by applying model policy
    * Every post creted will have a notification trigger to all users

Built using Livewire, which aims to enhance the efficiency and pleasure of creating web applications with Laravel, taking it to the maximum potential. We've either attempted or have plans to streamline any aspect of web development that can be simplified.

This application was developed to fulfill the requirements of my internship assignment.
## Deployment

Clone this directory then run:

```bash
composer install
```

## Prepare Environment File

Rename .env.example to .env

## Generate Application Key

```bash
php artisan key:generate
```

## Setup Database

configure database connection at .env file

## Run Migration

```bash
php artisan migrate
```

## Start Development Server

```bash
php artisan serve
```

## Security Vulnerabilities

If you discover a security vulnerability within this application, please send an e-mail to Aiman Bukhori via [emanbukhori@gmail.com](mailto:emanbukhori@gmail.com). All security vulnerabilities will be promptly addressed.

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).


