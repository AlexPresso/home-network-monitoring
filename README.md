### Home Network Monitoring

Just a [Grafana](https://grafana.com/) + [Prometheus](https://prometheus.io/) + node-exporter, docker-compose stack I use to monitor my home network Raspberry Pi and other stuff.

### Requirements
- docker + docker-compose

### Installation
- Clone the repository anywhere you want
- `cd home-network-monitoring`
- `docker compose up -d`
- go to `http://<host_ip>:3000` to access Grafana and change default user/password (default: user=`admin` ; pass=`admin`)
- Have fun

<img src="https://raw.githubusercontent.com/AlexPresso/home-network-monitoring/main/.assets/dashboard.png">
