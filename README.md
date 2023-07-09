# Chirp with Blade

## Requirements
- PHP 8.2
- sqlite extension

## Installation
- Install vendors: composer install
- Change DB_CONNECTION constant to sqlite
- Create database file: touch database/database.sqlite
- Remove DB_DATABASE constant from .env file
- php artisan migrate