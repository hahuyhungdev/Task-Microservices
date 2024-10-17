
# Full Source Code: Simple Task Microservices

This repository provides the complete source code for a **Simple Task Microservices** system. It includes microservices, Docker containerization, CI/CD setup with GitHub Actions, and monitoring with Prometheus and Grafana.

## Features

### 1. Microservices Architecture
- Implemented in Go with the following services:
  - **Task Service**
  - **User Service**
  - **Authentication/Authorization Service**
- API Gateway: **Tyk**
- Database: **MySQL**

### 2. Docker Containerization
- All services are containerized using Docker.
- Each service is packaged with specific **Docker Image Version Tags** for easy management and deployment.

### 3. CI/CD: GitHub Actions
- **Automated build, packaging, and deployment** processes are managed through GitHub Actions, enabling continuous integration and delivery (CI/CD).

### 4. Monitoring: Prometheus & Grafana
- The entire system is monitored using **Prometheus** for collecting metrics.
- **Grafana** is used for visualizing data and setting up alerts (notifications) when issues occur.

## Live Demos
- [Task Management Website (with Authentication)](https://todo.showcase.200lab.io/)
- [Grafana Monitoring Dashboard](https://devops-grafana.showcase.200lab.io)

## Technologies Used
- **Go** for microservices.
- **Tyk** for API Gateway.
- **MySQL** as the database.
- **Docker** for containerization.
- **GitHub Actions** for CI/CD.
- **Prometheus & Grafana** for monitoring and alerting.

## Getting Started

### Prerequisites
- Docker
- GitHub Account for CI/CD setup
- Prometheus and Grafana for monitoring

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo.git
   ```

2. Build Docker images:
   ```bash
   docker-compose build
   ```

3. Start services:
   ```bash
   docker-compose up
   ```

4. Access the live services:
   - Task Management Website: `http://localhost:3000`
   - Grafana Dashboard: `http://localhost:3001`

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
