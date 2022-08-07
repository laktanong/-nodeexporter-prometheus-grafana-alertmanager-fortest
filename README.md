# -nodeexporter-prometheus-grafana-alertmanager-fortest

**Test on**<br>
**Ubuntu 22.04 LTS**
**Docker version 20.10.17, build 100c701**<br>
**Docker Compose version v2.5.0**<br>

List of All Services

| Service | Port | Web URL | Notes |
| ------------- | ------------- | ------------- | ------------- |
| Prometheus | 9090 | http://(IP or Hostname):9090 | |
| Node Exporter | 9100 | http://(IP or Hostname):9100 | |
| Alert Manager | 9093 | http://(IP or Hostname):9093 | |
| Grafana | 3000 | http://(IP or Hostname):3000 | Grafana Credential <br> Username : admin <br> Password : test (Edit Password in /grafana/config.monitoring) GF_SECURITY_ADMIN_PASSWORD=) |
