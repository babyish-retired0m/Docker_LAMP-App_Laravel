# Docker_LAMP-App_Laravel

Run system
'''
docker-compose build app
docker-compose up -d
docker-compose ps
docker-compose exec app ls -l
docker-compose exec app composer update		
docker-compose exec app composer install
docker-compose exec app php artisan key:generate
docker-compose logs httpd
docker ps
docker exec -it <container_name> sh
'''