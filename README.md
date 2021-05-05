## Laravel Socialite (Social Login) - Login with google, facebook and github

## Clone this repo
```
https://github.com/SergeyHub/laravel-socialite-login
```

## Install composer packages
```
$ cd laravel-socialite
$ composer install
```

## Create and setup .env file
```
make a copy of .env.example and rename to .env
$ copy .env.example .env
$ php artisan key:generate
put database credentials in .env file
```
npm install & npm run dev
```
## Create app for google, facebook and github
```
For google app
https://console.developers.google.com/
For facebook app
https://developers.facebook.com/apps/
For gitgub app
https://github.com/settings/developers

Put all ids and secrets in .env file
```

## Migrate and insert records
```
$ php artisan migrate
```
## Run
php artisan serve or use Laravel Valet or Laravel Homestead
Visit localhost:8000 in your browser




