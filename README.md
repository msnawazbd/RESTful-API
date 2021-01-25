How to clone laravel project from github ?
1. Clone GitHub repo for this project locally

## git clone linktogithubrepo.com/ projectName

2. cd into this project

## cd projectName

3. Install Composer Dependencies

## composer install

4. Install NPM Dependencies

## npm install

5. Create a copy of this .env file

## cp .env.example .env

6. Generate an app encryption key

## php artisan key:generate

7. Create an empty database for this application

8. In the .env file, add database information to allow Laravel to connect to the database

9. Migrate the database

## php artisan migrate

10. Use the serve command

## php artisan serve

11. Wrapping Up 😀
