# redwood-docker

My attempt at dockerizing RedwoodJS

## Setup

```shell
mkdir app && cd app
```

```shell
curl -O https://github.com/MBahrSNC/redwood-docker/blob/main/docker-compose.yml
```

```shell
docker compose up -d  # development
```

```shell
NODE_ENV=production docker compose up -d  # production
```
