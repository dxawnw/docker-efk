# Docker EFK(Elasticsearch, Fluentd, Kibana)

EFK setup with docker, docker-compose.

## Requirements

- docker
- docker-compose

git clone https://github.com/dxawnw/docker-efk.git

cd docker-efd

chmod +x *.sh

## Usege

Using docker-compose

```sh
shdocker-compose build
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
