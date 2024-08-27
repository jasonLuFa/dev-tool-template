# Prometheus and Grafana monitoring

### Service
| Service  | Description  |
|---|---|
|prometheus   |This service monitors other services and collects metrics about their performance.   |
|grafana   |This service provides a web interface for visualizing the metrics collected by Prometheus.   |

### [prometheus's exporters](https://prometheus.io/docs/instrumenting/exporters/)

- Prometheus's Exporter will export existing metrics from third-party systems(database, MQ ...) as Prometheus metrics

| exporter  | Description  |
|---|---|
|[node_exporter](https://github.com/prometheus/node_exporter)   |This service exposes system metrics about the host machine where Docker is running.   |
|[cadvisor](https://github.com/google/cadvisor)   |This service collects, aggregates, and exposes container usage statistics.   |