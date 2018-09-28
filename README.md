# test-run
Includes all projects created on a test basis...

Installation
Follow the instructions below to install the project

Clone the repository using git clone git@gitlab.com:hc4u/agent-management-panel.git

Create .env by copying the env.example file
composer install
php artisan key:generate
php artisan migrate
Set administrator info in UserTableSeeder.php

php artisan db:seed
import each docs/tables/*.sql files on location_divisions, location_districts, location_upazillas accordingly.
php artisan import:sql
