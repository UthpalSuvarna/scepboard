# scepboard

A central backend for internal club use and additionally a dashboard UI for member/event/docs management and stuff.


## Running the project
Install the dependencies
```
$ composer install
```

Generate the secret APP_KEY
```
$ cp .env.example .env
$ php artisan key:generate
```

Migrate the DB
```
$ php artisan migrate
```

Start the server
```
$ php artisan serve
```


## Learning PHP and Laravel

Some resources for php and laravel
- php
    - [learn PHP in Y minutes](https://learnxinyminutes.com/docs/php/)
    - https://quickref.me/php

- laravel
    - quick walkthrough of the framework, https://bootcamp.laravel.com/
    - videos, https://laracasts.com/
    - official docs, https://laravel.com/docs/11.x
    - eloquent orm, https://laravel.com/docs/11.x/eloquent
    - setting up databases, https://laravel.com/docs/11.x/database
