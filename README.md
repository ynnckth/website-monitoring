# Website Monitoring
*Pre-configured Grafana & Prometheus monitoring stack using the blackbox exporter for website status monitoring*


## Running the monitoring stack

Prerequisites: 

- Docker and docker-compose

```shell
# Create and run the containers: 
docker compose up -d

# Stop and remove the containers: 
docker compose down
```


## Blackbox Exporter

Access the blackbox exporter at: 
> http://localhost:9115


## Prometheus

Access prometheus at:
> http://localhost:9090/targets
$

## Grafana

Access grafana at (admin/pass):
> http://localhost:3000/login

