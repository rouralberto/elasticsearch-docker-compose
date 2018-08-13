# Basic ElasticSearch + Kibana Setup

## Requirements
This relies in the presence of any reverse proxy based on `jwilder/nginx-proxy`. This
means that you'll need to add `127.0.0.1 es.docker kibana.docker` to your `/etc/hosts` file.

## Make it work
Assuming that the latest ElasticSearch version is `6.3.2`, just run `TAG=6.3.2 docker-compose up -d`.

## Tadaa
Yep.
