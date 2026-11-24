# Resource Lab

A personal digital resource management application built with Laravel.

## Requirements

- PHP 8.4
- Composer
- Node.js and npm
- PostgreSQL

## Local setup

```bash
composer install
npm install
cp .env.example .env
php artisan key:generate
createdb resource_lab   # then set DB_USERNAME / DB_PASSWORD in .env
php artisan migrate
```

## Running locally

```bash
composer run dev
```

This runs `php artisan dev`, which starts the Laravel dev server and Vite together. The app is served at http://localhost:8000.

Alternatively, run `php artisan serve` and `npm run dev` in separate terminals, or `npm run build` to compile assets once.

## Tests

```bash
php artisan test
```
