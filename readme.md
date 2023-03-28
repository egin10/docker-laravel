Environment PHP for local using Docker

Usage:

- install docker & docker-compose
- clone this repo
- create directory `dev`, `mysql`, & `postgres`
- create index.php file in `dev` directory
- create image for PHP using `docker build -t docker-php-dev .` on terminal
- run command `docker compose up --build -d` on terminal
- access the app from browser on `http://localhost:8000` and phpmyadmin on `http://localhost:88001`
- you can create new project (PHP) in directory `dev`
- if your project is laravel project, you can copy all files in public dir, and update path on line 19, 37, & 47 on file index.php
- access your project using `http://localhost/project-dir`

Thank you 🚀