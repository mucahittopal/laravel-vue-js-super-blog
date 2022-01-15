
# About Laravel vue js Blog Project

![laravel vue js vuex vue router blog project](https://user-images.githubusercontent.com/29582239/49328894-e5dff680-f5a1-11e8-9190-c6b25730bfb5.png)
   
##Here are the things you will learn in this series:
* How use Vue Router with Laravel(Using for routing)
* How to Use Vue filter
* How use Vuex with Laravel (Used for state management)
* How to Install AdminLTE 3 (Template used for admin panel)
* How to Use Font Awesome 5 on Laravel (Used for admin panel icon)
* Vform validation with Laravel (Used for form validation)
* Relational Database with Laravel (Used for Maintainance DB)
* Axios and Ajax Request (Passing request for fetch and crud operation)
* How to Use Moment js on Laravel (Used for formating date time)
* How to Use sweetalert2 (Used for flash message)
* How to Image intervation with Laravel (Used for image resize) 
* How to Use lodash 
* And much more...






Installation
Clone repository

clone repository to your local machine

<code>git clone https://github.com/mucahittopal/laravel-vue-js-super-blog.git</code>

Change Directory

Navigate into the project directory

<code>cd laravel-vue-js-super-blog</code>

Copy .env file

copy content of the environment file

<code>cp .env.example .env</code>

Edit .env file

Update .env file with DB information

<pre>
  DB_CONNECTION=mysql
  DB_HOST=localhost
  DB_PORT=3306
  DB_DATABASE=homestead
  DB_USERNAME=homestead
  DB_PASSWORD=secret
</pre>

Install laravel packages

Remove composer.lock file and install packages

<code>rm composer.lock</code>

<code>composer install</code>

Generate Key

Generate application key from your terminal

<code>php artisan key:generate</code>

Install npm packages

Remove package-lock.json file and install npm packages

<code>rm package-lock.json</code>

<code>npm i</code>

Run Migrations

Run database migrations and seed the post tables

<code>php artisan migrate:fresh --seed</code>


Start Vue

<code>npm run watch</code>

Start Application

<code>php artisan serve</code>

Go to localhost:8000 and register, start blogging tada






