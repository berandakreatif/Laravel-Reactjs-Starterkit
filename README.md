<p align="center"><img src="https://laravel.com/assets/img/components/logo-laravel.svg"><img src="https://www.import.io/wp-content/uploads/2017/10/React-logo-1.png" style="max-width:150px;"></p>

## Laravel 5.8 and React 16.2.0 boilerplate

Please follow the guide.

1. `git clone https://github.com/berandakreatif/Laravel-Reactjs-Starterkit.git`
2. `update the .env file along with database connection`
3. `composer install && composer update`
4. `php artisan migrate`
5. `php artisan db:seed`
6. `npm install`
6. `php artisan serve`

## Running Application
1. open terminal and run command 

---
php artisan serve
---

2. Open browser and run with this url

---
http://127.0.0.1:8000
---

3. Login with username `user@gmail.com` and password `123456789`

## Update the Passport keys in .env file 
Copy the keys for personal and password grants in `.env` file

```
PERSONAL_CLIENT_ID=1
PERSONAL_CLIENT_SECRET=xxxxxxxxxxxxxxxxxxxxxxxxxxxxx
PASSWORD_CLIENT_ID=2
PASSWORD_CLIENT_SECRET=xxxxxxxxxxxxxxxxxxxxxxxxxxxxx
```
## Set the App URL
Set the APP_URL in `.env` file (e.g)

```
APP_URL=http://localhost:8000
```

## Set the APP Title
Set the APP_TITLE in `resources/assets/js/values/index.js`

```angular2html
APP_TITLE='Your Blog Name'
```

## Run PHP Dev Server
Either create a local dev url and map the link in webpack.mix.js file or open an other terminal window and copy paste the following command

```
php artisan serve
```

## Run Node Engine

Compile assets one time.
```
npm run dev
```
**OR**
or if you would like to compile assets on runtime then copy paste following command in terminal 

`npm run watch` or `npm run watch-poll`


for complete sample todo app follow the link below
    [Todo App Laravel & React Js](https://github.com/berandakreatif/Laravel-Reactjs-CRUD-Todo-App)
