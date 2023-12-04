# docker-compose-efbk
---

## Overview
Use elasticsearch, filebeat, and kibana to parse the log files collected using fluentd through patterns to enable log analysis.

You can configure the above environment with docker-compose.

## Usage

### Run <br/>
docker-compose -f "docker-compose.yml" up -d --build <br/><br/>

### View Kibana <br/>
localhost:5601 <br/><br/>

### Stop <br/>
docker-compose down <br/><br/>

### Delete <br/>
docker-compose -f 'docker-compose.yml' -p 'local-docker-efk' down
