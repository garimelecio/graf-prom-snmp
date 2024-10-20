# Grafana-Prometheus-snmp-exporter Stack

```
mkdir ~/docker
cd ~/docker
git clone https://github.com/garimelecio/graf-prom-snmp.git
cd ~/docker/graf-prom-snmp
mkdir -p grafana/provisioning
```

Edit `snmp-exporter/snmp.yml` with your snmp credentials.

```
docker compose up -d
```


