# Monitoring Dashboard

A cloud-based monitoring setup that tracks system metrics and container performance using Prometheus and Grafana.  
Built and deployed on AWS EC2 using Docker and Nginx.

##  Features
- Containerized with Docker
- Monitors CPU, Memory, and Disk usage
- Grafana dashboard for visualization
- Prometheus for metric collection
- Nginx reverse proxy setup
- Deployed on Amazon Linux EC2

##  Tech Stack
- AWS EC2
- Docker
- Prometheus
- Grafana
- Nginx
- Linux (Amazon Linux 2)

##  Setup Instructions
```bash
# clone the repo
git clone https://github.com/abhinav-dops/monitoring-dashboard.git
cd monitoring-dashboard

# build and run containers
docker-compose up -d
