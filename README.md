# Mikrotik, Services & Nodes Monitoring

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
- 9100: Node Exporter
- 9116: SNMP Exporter
- 9115: Black Box Exporter

## Acknowledgements
This project is a fork of [Docker-Raspberry-PI-Monitoring](https://github.com/oijkn/Docker-Raspberry-PI-Monitoring) by [oijkn](https://github.com/oijkn).  
Most code is licensed under the MIT License (see [LICENSE](LICENSE)).  
Parts of this project (Grafana dashboard and SNMP) are taken from [Grafana-Mikrotik](https://github.com/IgorKha/Grafana-Mikrotik) by [IgorKha](https://github.com/IgorKha) and licensed under the Apache License 2.0.