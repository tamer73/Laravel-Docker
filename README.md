# Laravel-Docker
Create Docker-Based Laravel Environment 

Just a quick playground based on Bitnami images

**Sources:**
https://github.com/bitnami/containers/tree/main/bitnami/laravel
https://github.com/bitnami/containers/tree/main/bitnami/phpmyadmin

**Run docker as user:**
> sudo usermod -aG docker $USER

**Create Project Folder:**
> mkdir MyProject && cd MyProject
create or copy the docker-compose.yml here

**install:** 
> sudo docker-compose up

(leave this shell open)

**Enable and start Docker:**
> sudo systemctl start docker.service

> sudo systemctl enable docker.service

**Access Laravel Container:**
> sudo docker-compose exec myapp bash  
Url: http://0.0.0.0:8000

*** Access phpMyAdmin http://127.0.0.1 and delete all tables ***

**Install Jetstream:**
> composer require laravel/jetstream

> php artisan jetstream:install livewire --teams

> npm install

> npm run build

> php artisan migrate

**Source:** https://jetstream.laravel.com/installation.html




**things to do next:**
[permission](https://laravel-news.com/jetstream-spatie-permission)https://laravel-news.com/jetstream-spatie-permission
marker at: Full CRUD: Buttons and Forms
