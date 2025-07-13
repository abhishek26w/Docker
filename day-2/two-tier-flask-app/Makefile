DOCKER_COMPOSE := docker-compose 



OS := $(shell name)

build:
	@echo "Building containers (UID/GID auto-detected)"
		UID=$$(id -u) GID=$$(id -g) $(DOCKER_COMPOSE) build
up:
	                $(DOCKER_COMPOSE) up -d
down:
	                $(DOCKER_COMPOSE) down
clean:
	docker system prune -f


