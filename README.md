# Caddy + Porkbun
This repository contains files for Caddy. SSL certificates will be managed by a Porkbun plugin through DNS-01 challenge.

### Pre-requisites
* Docker
* A custom Docker image of Caddy with the Porkbun plugin.

**Note:** Commands below uses Docker Compose V2.

### Start the container
```
cd ./caddy-files
docker compose up -d
```

### To stop the container
```
docker compose down
```