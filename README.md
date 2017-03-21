# Drupal Developer Days 2017

Some init project to test funcionalities and developments from DDD 2017 workshops.

## MariaDB docker container

The idea is start a mariaDB docker container for each Drupal instance.

You must install docker-engine and docker-compose.

### Installl docker-engine:
```
curl -fsSL https://get.docker.com/ | sh
docker --version
```

### Install docker-compose:
```
curl -L "https://github.com/docker/compose/releases/download/1.11.2/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose
docker-compose--version
```

### Run container:

```
cd .docker/
docker-compose up --build
```