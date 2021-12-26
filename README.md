# Wordpress and DB setup with Docker

Wordpress setup for local development of project in production.

## Installation
1. Start Docker
2. Run `docker-compose up -d`
3. Copy theme from server to `wp-content/themes`
4. Use phpMyAdmin to import data

## Ports
Wordpress: `http://localhost:8000/`

phpMyAdmin: `http://localhost:8081/` (user and password are in docker-compose.yml)