# Zabbix Monitoring with Docker

This repository provides a Docker-based setup for deploying the Zabbix Monitoring solution, using separate containers for the Zabbix server, Apache, and MySQL. This project helps to quickly set up a Zabbix monitoring system for development and testing purposes.

## Folder Structure

.
├── Dockerfile.zabbix     # Dockerfile for the Zabbix server and Apache
├── docker-compose.yml    # Docker Compose file to define services
├── zabbix_server.conf    # Configuration file for the Zabbix server
├── .env                  # Environment variables for MySQL
└── README.md             # Documentation for the project


## Prerequisites

- Docker: [Install Docker](https://docs.docker.com/get-docker/)
- Docker Compose: [Install Docker Compose](https://docs.docker.com/compose/install/)

## How to Use

### 1. Clone the Repository

```sh
git clone https://github.com/SNA212/zabbix-monitoring-docker.git
cd zabbix-monitoring-docker

docker compose up --build

---


