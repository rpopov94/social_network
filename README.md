# microblog
ELASTICSEARCH
1. docker pull image

`docker pull docker.elastic.co/elasticsearch/elasticsearch:7.5.2`
3. Start Elasticsearch in Docker

`docker run -p 9200:9200 -p 9300:9300 -e "discovery.type=single-node" docker.elastic.co/elasticsearch/elasticsearch:7.5.2`
