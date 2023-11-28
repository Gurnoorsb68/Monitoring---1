# MONITORING SYSTEM

## Description

This project provides a monitoring solution using Telegraf, InfluxDB, and Grafana. It includes Dockerfiles for each component and a Docker-compose file for easy deployment.


## Installation

To get started, clone the repository:

```bash
git clone https://github.com/Gurnoorsb68/Monitoring---1.git


Open telegraf.conf and update the InfluxDB connection details, such as URLs, database, username, and password.

Docker-compose Configuration
Update the docker-compose.yml file if necessary, especially the build contexts for each service.

Usage
To start the monitoring stack, use Docker-compose:

docker-compose up -d

This command will build and start the InfluxDB, Telegraf, and Grafana services.

Monitoring Setup

InfluxDB
InfluxDB is accessible at http://localhost:8086.

Telegraf
Telegraf is configured with telegraf.conf. It collects system metrics and sends them to InfluxDB.

Grafana
Grafana is accessible at http://localhost:3000.
Default credentials: admin/admin.
Add InfluxDB as a data source using the InfluxDB URL, database, and credentials from telegraf.conf.

