up: docker-pull docker-up
down:
	docker compose down -t 0 -v --remove-orphans

restart:
	docker compose down -t 0 -v --remove-orphans
	docker compose up -d

docker-up:
	docker compose up -d

docker-pull:
	docker compose pull

clean:
	docker compose down -t 0 -v --remove-orphans
