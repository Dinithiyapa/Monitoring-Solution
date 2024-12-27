# Monitoring Stack Deployment with Ansible ----

This repository provides an Ansible-based solution for deploying a complete monitoring stack, which includes Prometheus, Alertmanager, Node Exporter, and Grafana. It allows you to monitor server metrics, set up alerting, and visualize data in an interactive Grafana dashboard.

---

## Features

- **Prometheus**: Time-series database and monitoring solution.
- **Alertmanager**: Handles alerts sent by Prometheus.
- **Node Exporter**: Collects system metrics (e.g., CPU, memory, disk).
- **Grafana**: Visualizes data and provides interactive dashboards.
- **Automation**: Entire deployment is automated using Ansible roles.
- **docker_nginx_setup**: Installs Docker, Docker Compose, and Nginx.

---

## Verify Deployment

- **Prometheus**: [http://<server-ip>:9090](http://<server-ip>:9090)
- **Alertmanager**: [http://<server-ip>:9093](http://<server-ip>:9093)
- **Node Exporter**: [http://<server-ip>:9100/metrics](http://<server-ip>:9100/metrics)
- **Grafana**: [http://<server-ip>:3000](http://<server-ip>:3000) (default login: `admin` / `admin`)

---
