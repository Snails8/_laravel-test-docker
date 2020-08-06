# docker-laravel-sample

# install laravel

$ docker-compose exec app bash

$ composer create-project --prefer-dist "laravel/laravel=6.0.*" .

$ php artisan -V

# confirm
$ docker-compose exec app php -v

$ docker-compose exec web nginx -v

$ docker-compose exec db mysql -V
