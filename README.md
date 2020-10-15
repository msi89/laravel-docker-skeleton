## Development environment for laravel using docker

- build containers
  `docker-compose build`
- Create your laravel project into this `src` directory.
  `docker-compose run --rm composer create-project laravel/laravel .` in your terminal.

- run app
  ` docker-compose up web -d`
- run pgadmin (optional)
  `docker-compose up pgadmin -d`
- run redis (optional)
  `docker-compose up pgadmin -d`

### using artisan command

`docker-compose run --m artisan migrate`

### install dependencies

`docker-compose run --m composer require laravel/passport` for example
