# docker-laravel-sample

# install laravel

$ docker-compose exec app ash

$ composer install

$ cp .env.example .env

$ php artisan key:generate

$ php artisan migrate

$ php artisan -V

# confirm
$ docker-compose exec app php -v

$ docker-compose exec web nginx -v

$ docker-compose exec db mysql -V

# mysql error confirmation

$ docker-compose exec db bash -c 'mysql -uroot -psecret'

mysql> show databases;

mysql> SELECT Host, User, plugin FROM mysql.user;

mysql> show grants for 'phper'@'%';

