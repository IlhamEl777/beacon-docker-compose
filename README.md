# beacon-docker-compose

Docker Compose setup for installing Blockcast CDN gateways.

---

## Preparation: Clone the Repository

First, clone this repository from GitHub:

```bash
git clone https://github.com/IlhamEl777/beacon-docker-compose.git
cd beacon-docker-compose
```

## Install
Pulls the image associated with the service defined in the compose.yaml file:

```bash
docker compose pull
# or
docker-compose pull
```

## Registration

Start Blockcast services:

```bash
docker compose up -d
# or
docker-compose up -d
```

Get Node info by running:
```bash
docker compose exec blockcastd blockcastd init
# or
docker-compose exec blockcastd blockcastd init
```

Register using the provided URL or by using the Hardware ID and Challenge Key manually.
