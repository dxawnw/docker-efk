# Docker EFK(Elasticsearch, Fluentd, Kibana)

EFK setup with docker, docker-compose.

## Requirements

- docker
- docker-compose

## Usege

Using docker-machine

```sh
docker-machine create -d virtualbox dev
eval "$(docker-machine env dev)"
```

```sh
docker-compose up
```

Use Background

```sh
docker-compose up -d
```

```sh
docker-compose ps

# open kibana
open http://127.0.0.1:5601

# if use docker-machine
open http://"$(docker-machine ip dev)":5601
```

If you use docker-toolbox, localhost is docker-machine ip.
