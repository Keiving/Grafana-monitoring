# Mikrotik & Node Monitoring

## Installation and Configuration

To install the stack, follow the steps below:

- Clone this repository to your host machine.
```bash
git clone https://github.com/Keiving/Grafana-monitoring.git
```

- Enter to the cloned directory.
```bash
cd Grafana-monitoring
```

 - Start the stack with `docker-compose`.
```bash
docker-compose up -d
```

This will start all the containers and make them available on the host machine.
<br/>The following ports are used (only Grafana is exposed on the host machine):
- 3001: Grafana
- 9090: Prometheus
- 9100: NodeExporter
- 9116: SNMP exporter