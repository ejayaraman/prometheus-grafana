# prometheus-grafana
docker-compose to run Grafana with Prometheus as a datasource locally.

Based on:
https://techviewleo.com/run-prometheus-and-grafana-using-docker-compose/ 

## To run grafana and prometheus locally
```
docker-compose up -d
```

## To access Grafana
```
http://localhost:3000
```
username: admin
password: admin

## To access Prometheus
```
http://localhost:9000
```

## To view the metrics
```
http://localhost:9000/metrics
```