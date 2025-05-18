# CONTRIBUTING

## How to run the DockerFile locally
Using the docker-compose files.
```
docker compose -f docker-compose.yml -f docker-compose.debug.yml up --build --force-recreate --no-deps api
```