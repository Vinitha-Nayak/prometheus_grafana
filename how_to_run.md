# How to run the prometheus docker image
# please note the prometheus.yml too be present in the location before running below comand

# How to run the nodeexporter  docker image

docker run -d -p 9100:9100 quay.io/prometheus/node-exporter:v1.2.2

# How to run prometheus

docker run -d -p 9090:9090 -v /home/ec2-user/prometheus:/etc/prometheus prom/prometheus


# How to run the Grafana docker image

docker run -d --name=grafana -p 3000:3000 grafana/grafana

