# Docker-Monitoring-CIPG
Simplify Monitoring the Docker Container by Cadvisor, Influxdb, Prometheus and Grafana

# Step
```
docker-compose up -d

Reset and Remove:
docker-compose down
rm -rf ./data
docker volume rm $(docker volume ls | grep grafana_data | awk '{print $2}')
```

# Default Info
```
localhost:3000
grafana login: admin / admin
```

# Reference
```
Dashboard Search: https://grafana.com/grafana/dashboards/
Thanks for:
https://medium.com/@mertcan.simsek276/docker-monitoring-with-cadvisor-prometheus-and-grafana-adefe1202bf8
```
