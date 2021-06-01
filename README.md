# docker-compose-laravel

Docker Compose workflow that sets up a LEMP network of containers for local Laravel development

## Usage

To get started, make sure you have Docker Installed on your system, and then clone this repository.

## Spin up the containers for the web server by running.

 `docker-compose up -d --build site`.

## The following are built for our web server, with their exposed ports detailed:

- **nginx** - `:80`
- **mysql** - `:3306`
- **php** - `:9000`

