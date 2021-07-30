include .env

.PHONY: up
up:
	docker-compose -f docker-compose.dev.yaml up -d --build

.PHONY: down
down:
	docker-compose -f docker-compose.dev.yaml down

.PHONY: logs
logs:
	docker-compose -f docker-compose.dev.yaml logs --tail 50 -f

.PHONY: start
start:
	docker-compose -f docker-compose.dev.yaml start

.PHONY: restart
restart:
	docker-compose -f docker-compose.dev.yaml restart

.PHONY: stop
stop: 
	docker-compose -f docker-compose.dev.yaml stop