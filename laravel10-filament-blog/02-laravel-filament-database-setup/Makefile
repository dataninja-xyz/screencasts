build:
	docker-compose build

up:
	docker-compose up -d

init:
	# docker exec -it laravel10-blog cp .env.example .env
	docker exec -it laravel10-blog composer install
	docker exec -it laravel10-blog php artisan key:generate
	docker exec -it laravel10-blog php artisan migrate

down:
	docker-compose down

shell:
	docker exec -it laravel10-blog /bin/sh

pint:
	docker exec -it laravel10-blog ./vendor/bin/pint

test:
	docker exec -it laravel10-blog php artisan test

