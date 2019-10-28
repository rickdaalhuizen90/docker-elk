# Docker environment for PHP WebApps

### Included
 - Nginx
 - PHP-FPM (FastCGI Process Manager)
 - Percona (Mysql)
 - Redis
 - Elasticsearch + Kibana

### Prerequisites
The vm.max_map_count kernel setting needs to be set to at least 262144 for production use [see](https://www.elastic.co/guide/en/elasticsearch/reference/current/docker.html#docker-prod-prerequisites).
```sudo sysctl -w vm.max_map_count=262144```

### Resources
 - [Elasticsearch Docs](https://www.elastic.co/guide/en/elasticsearch/reference/current/docker.html)
 - [Elasticsearch & Laravel](https://madewithlove.be/how-to-integrate-elasticsearch-in-your-laravel-app-2019-edition/)
