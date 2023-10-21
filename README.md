# Ntwrk-mntr docker compose

> UET K64 graduation project

- A solution for monitor network traffics & system status of routers using Prometheus, Grafana, SNMP Exporter & Alertmanager, bootstrapped using Docker compose.

## Installation

1. Install Docker from there website, recommend using Docker Desktop. You can install Docker Desktop from here: https://www.docker.com/products/docker-desktop/

2. Clone this project

   ```bash
   git clone https://github.com/SonDinh5310/ntwrk-mntr.git
   ```

3. Start Docker Desktop & run the following commands

   - Pull new service images

     ```bash
     docker compose pull
     ```

   - Start the container

     ```bash
     docker compose up -d
     ```

4. (Extra) To stop or remove container

   - Stop container

     ```bash
     docker compose stop
     ```

   - Remove container (WARNING: will remove all monitoring data - use carefully)

     ```bash
     docker compose down
     ```

## After Installation

- Once everything has run correctly, you can access all services by:

  - Grafana: `localhost:4000`

  - Prometheus: `localhost:9090`

  - SNMP Exporter: `localhost:9116`

  - Alertmanager: `localhost:9093`
