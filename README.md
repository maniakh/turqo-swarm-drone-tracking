# Turqo – Swarm Drone Telemetry & Monitoring Platform

**Turqo** is a real-time swarm drone telemetry and anomaly detection platform. It ingests telemetry from multiple drones, detects anomalies, and provides alerting, with full DevOps and observability support.

## Features

- Real-time telemetry ingestion from swarm drones
- Drone management (metadata, status, missions)
- Anomaly detection (speed limit violations, altitude violations, battery warnings, boundary breaches)
- Alert system via Slack, Email, or Webhook
- Real-time dashboard with map visualization and alerts
- Observability: Prometheus metrics, Grafana dashboards, Loki logs
- DevOps: CI/CD pipeline via GitHub Actions, Docker Compose deployment

## Tech Stack

| Component           | Technology                  |
|--------------------|-----------------------------|
| Backend Services    | Java Spring Boot, Python FastAPI |
| Frontend Dashboard  | React, Leaflet / Mapbox     |
| Database            | PostgreSQL / TimescaleDB    |
| Messaging           | Kafka / NATS                |
| Monitoring          | Prometheus, Grafana, Loki   |
| Deployment          | Docker Compose, Kubernetes  |
| CI/CD               | GitHub Actions              |

## Repo Structure
turqo-swarm-drone-tracking/
├── backend/
│ ├── telemetry/
│ ├── drone-mgmt/
│ ├── anomaly/
│ └── alert/
├── frontend/
│ └── dashboard/
├── infra/
│ ├── docker/
│ ├── kubernetes/
│ └── grafana/
├── .github/
│ └── workflows/
└── README.md



## Getting Started

### Prerequisites

- Docker & Docker Compose
- Java 21 + Maven
- Python 3.11+
- Node.js 18+

### Run the Platform

1. Clone the repo:

```bash
git clone 
## Getting Started

### Prerequisites

- Docker & Docker Compose
- Java 21 + Maven
- Python 3.11+
- Node.js 18+

### Run the Platform

1. Clone the repo:

```bash
git clone https://github.com/<your-username>/turqo-swarm-drone-tracking.git
cd turqo-swarm-drone-tracking
