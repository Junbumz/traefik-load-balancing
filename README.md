# Traefik Load Balancing

Load Balancing with Traefik

## Usage

Create a network:

```sh
docker network create --subnet=172.28.0.0/16 --gateway=172.28.0.1 traefik
```

Create and start containers:

```sh
docker compose up -d
```

Stop and remove containers, networks:

```sh
docker compose down
```
