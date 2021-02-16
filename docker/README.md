# Changements à effectuer

- .env
- nginx/nginx.conf (server_name et php-fpm-...)
- docker-compose.yml (normale - dev - prodd => services name et network)

# Docker compose

## Development

docker-compose -f docker-compose.yml -f docker-compose.dev.yml up -d

## Production

docker-compose -f docker-compose.yml -f docker-compose.prod.yml up -d
