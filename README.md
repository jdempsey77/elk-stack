# elk-stack
This repo with little work should easily help in getting up elkstack which includes 
Elasticsearch, Kibana, Logstash, Metricbeat, Filebeat and Heartbeat.

## Prerequisites
- Docker and Compose. 

1. Clone the repo
2. Run `sysctl -w vm.max_map_count=262144` 	
3. Edit the .env and update ELASTIC_PASSWORD 
4. Edit all the passwords in the ./config/*/*.yml and update the password from previous step
5. docker-compose up -d 
6. Point a browser at [`http://localhost:5601`](http://localhost:5601) to load kibana
```

This was forked from https://github.com/elastic/stack-docker and changed over to using the OSS images.

