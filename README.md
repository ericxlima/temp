On Ubuntu Server

```sh
# docker run --rm -v $(pwd):/app composer install
# sudo chown -R $USER:$USER $(pwd):/
docker-compose up -d
# docker compose exec app php artisan key:generate
# docker compose exec app php artisan config:cache # set to dir -> /var/www/bootstrap/cache/config.php
```

```sh
# to run
# php artisan serve
```
