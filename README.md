# My Personal Docker Env to Laravel 8

 - PHP 8.0.0-fpm-alpine3.12
 - PostgreSQL 1.19-alpine
 - Nginx 1.19-alpine

# Information
 - Run Nginx Load Balancer on 4 PHP Containers

# How to use
'''
	1 - create folder .docker/dbdata

	2 - create laravel project on folder ./API

	3* - if API project clone from github, run composer install && npm install && npm run dev on API folder

	4 - configure postgres env in docker-compose.yml file

	5 - run command: docker-compose up -d --build
'''

### Containers

- **[PHP](https://hub.docker.com/_/php)**
- **[PostgreSQL](https://hub.docker.com/_/postgres?tab=tags&page=1&ordering=last_updated)**
- **[Nginx](https://hub.docker.com/_/nginx)**