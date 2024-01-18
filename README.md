# Laravel-Docker
Create Docker-Based Laravel Environment 

Just a quick playground based on Bitnami images

Sources:
https://github.com/bitnami/containers/tree/main/bitnami/laravel
https://github.com/bitnami/containers/tree/main/bitnami/phpmyadmin

Run docker as user:
sudo usermod -aG docker $USER

install: sudo docker-compose up (leave this shell open)

Enable and start Docker:
sudo systemctl start docker.service
sudo systemctl enable docker.service

Access Laravel Container:
sudo docker-compose exec myapp bash  
Url: http://0.0.0.0:8000

Install Jetstream:
composer require laravel/jetstream
php artisan jetstream:install livewire --teams
npm install
npm run build
php artisan migrate

source:https://jetstream.laravel.com/installation.html


Access phpMyAdmin:
http://127.0.0.1

