<<<<<<< HEAD
docker-compose -f 'docker-compose.yml' -p 'local-docker-efk' down 
# docker-compose-efbk
---

## Overview
Use elasticsearch, filebeat, and kibana to parse the log files collected using fluentd through patterns to enable log analysis.

You can configure the above environment with docker-compose.

## Usage

Run
docker-compose -f "docker-compose.yml" up -d --build

View Kibana
localhost:5601

Delete
docker-compose -f 'docker-compose.yml' -p 'local-docker-efk' down 
>>>>>>> 0cba9095e68e981f64257975e780596f9c628570
