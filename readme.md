# WordPress, MariaDB, and phpMyAdmin Dockerized

This repository contains a Docker-composer setup for WordPress, MariaDB, and phpMyAdmin.

## Usage

This Docker file can be used along with [Coolify](https://coolify.io/) for rapid prototyping.

## Ports

- **WordPress**: 8080
- **phpMyAdmin**: 8181
- **MariaDB**: 3306

### Important

Please ensure that the following ports are not used by another instance on your system. If they are, you should change them to avoid conflicts:
- Port 8080 for WordPress
- Port 8181 for phpMyAdmin
- Port 3306 for MariaDB

## Security

For security concerns, replace any hardcoded passwords in the Docker file with environment variables or your own password on the production server.

## Sources:

The mariadb healthcheck script is the one used in thier offcial docker image: https://github.com/MariaDB/mariadb-docker/tree/master
