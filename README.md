Create an Elasticsearch and kibana docker image

## Version
- Elasticsearch: latest
- Kibana: latest

## Start cluster
- ``docker-compose up -d``

First time requires download and install of elasticsearch and kibana images. After that this process should be fast.

## Scale elasticsearch
- ``docker-compose scale elasticsearch=3``

## Stop cluster
- ``docker-compose stop``


## URLs
- Elasticsearch: http://localhost:9200
- Kibana: http://localhost:5601

## Create an index
- ``curl -XPUT 'http://localhost:9200/applog/'``

## Reference
- https://github.com/deviantony/docker-elk
