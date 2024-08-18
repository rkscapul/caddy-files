# Caddy + Porkbun
This repository contains files for Caddy. SSL certificates will be managed by a Porkbun plugin through DNS-01 challenge.

### Pre-requisites
* Docker
* A custom Docker image of Caddy with the Porkbun plugin.

**Note:** Commands below uses Docker Compose V2.

### Set environment variables
1. Create a `.env` file.
2. Copy and paste the contents of `.env.sample` to `.env`. 
3. Replace **REDACTED** with actual values.
4. Save.

### To start Caddy
```
cd ./caddy-files
docker compose up -d
```

### To stop Caddy
```
docker compose down
```