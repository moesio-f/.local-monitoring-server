# Local Monitoring Server

This repository contains a simple monitoring/observability setup with Prometheus and Grafana. The default configuration requires manual service discovery in the `targets.json` files.

## Setup and Run

- Create the `config/targets.json` file with custom services;
- Run `docker compose up -d`;
