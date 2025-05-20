# CONTRIBUTING

## How to run the DockerFile locally
Using the docker-compose files.
```
docker compose -f docker-compose.yml -f docker-compose.debug.yml up --build --force-recreate --no-deps api

docker compose up --build --force-recreate --no-deps api
```

To run a migration with Docker Compose and using the Docker db container
```
docker compose exec api flask db migrate
```