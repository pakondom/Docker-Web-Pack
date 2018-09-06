# lemp-docker-starter-kit

A starter kit to run LEMP stack (Linux, nginx, MySQL + PhpMyAdmin and PHP) with docker.

# Usage

Go to Terminal and type command below to start the LEMP stack:

```
$ docker-compose up -d
OR
$ docker-compose start
```

# phpMyAdmin
in Docker-Web-Pack dir
```
$ mkdir nginx/site/phpMyAdmin/tmp-file && chmod 777 nginx/site/phpMyAdmin/tmp-file
```

# Details

## Docker Containers name

**nginx**: `lemp-nginx`

**php7-fpm**: `lemp-phpfpm`

**mysql**: `lemp-mysql`

## Path

**Path to place your website**: `./nginx/site`

**Path to edit your nginx configuration**: `./nginx/conf`

**Path to add your custom mysql configuration**: `./mysql/conf`

## MySQL Default Root Password

`1212312121`

Please feel free to edit `docker-compose.yml` file per your demand.

# Requirement on your host machine

- Any OS with Docker Engine and docker-compose installed
