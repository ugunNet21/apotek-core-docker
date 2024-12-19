## Install project
````
composer create-project --prefer-dist laravel/laravel nama-proyek
cd nama-proyek

````

## install docker

````
composer require laravel/sail --dev
php artisan sail:install
./vendor/bin/sail up

````

## cek port runing

````
sudo lsof -i :80

````

### running

````
docker ps

docker-compose up -d

Migrasi databse:
docker exec -it laravel_app php artisan migrate
docker exec -it apotek-core_laravel.test_1 php artisan migrate

docker exec -it apotek-core_mysql_1 mysql -u sail -p


cek daftar container:
docker ps

masuk container:
docker exec -it laravel_app bash

stop container:
docker-compose down


cek log:
docker-compose logs laravel.test

docker-compose logs mysql

````
