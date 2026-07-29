![CI](https://github.com/viplavsomkuwar77/end-to-end-devops-microservices-k8s/actions/workflows/pipeline.yml/badge.svg)

# End-to-End Microservices DevOps Platform

🧩 Project Context

This repository is a hands-on implementation of the OpenTelemetry Demo application that I built to strengthen my practical DevOps skills. I customized the deployment, documentation, and CI/CD workflow — working with Docker, Kubernetes, GitHub Actions, observability tooling (OpenTelemetry, Prometheus, Grafana), and load testing with Locust — to deepen my understanding of production-style DevOps practices.

This project is intended for learning and portfolio purposes and demonstrates my practical DevOps skills.

---

## 🎯 Project Objectives

- Deploy a containerized microservices application
- Implement Kubernetes deployments
- Build a CI/CD workflow using GitHub Actions
- Configure observability using OpenTelemetry
- Monitor metrics with Prometheus and Grafana
- Perform load testing using Locust

---

## 🏗️ Architecture

![architecture-diagram png](https://github.com/user-attachments/assets/c6738426-d977-4c0a-9839-3aab8985e76c)

---

## 🧱 Microservices

The application follows a microservices architecture and includes services such as:

- Frontend
- Product Catalog
- Recommendation Service
- Cart Service
- Checkout Service
- Payment Service
- Ads Service
- Shipping Service
- Email Service

---

## 🛠️ Tech Stack

**Containers & Orchestration**
- Docker
- Kubernetes
- Helm

**CI/CD**
- GitHub Actions

**Observability**
- OpenTelemetry
- Prometheus
- Grafana

**Load Testing**
- Locust

---

## ✨ Features

- Dockerized microservices
- Kubernetes deployments
- Helm charts
- GitHub Actions CI/CD
- OpenTelemetry integration
- Prometheus monitoring
- Grafana dashboards
- Locust load testing

---

## 📂 Repository Structure

```text
.
├── docker/
├── kubernetes/
├── observability/
├── load-testing/
├── architecture/
└── .github/workflows/
```

---

## 🔁 CI/CD Workflow

This repository demonstrates a GitHub Actions workflow for automating common DevOps tasks.
On each push to the `main` branch, the workflow:

- Checks out the source code
- Simulates Docker image build steps
- Demonstrates where deployment steps would occur

In a real production environment, the build stage would push Docker images to a
container registry, and the deploy stage would update Kubernetes resources using
tools such as Helm or kubectl.

---

## 📊 Observability

This project uses the **OpenTelemetry Collector configuration** from the
OpenTelemetry demo to collect telemetry data (traces, metrics, and logs)
from multiple microservices.

Telemetry data is exported and visualized using **Prometheus and Grafana**,
enabling better monitoring and debugging of distributed systems.

---

## 🚦 Load Testing

Load testing is performed using **Locust** to simulate user traffic and analyze
system performance, latency, and error rates under load.

---

## 📚 Key Learnings

- Docker containerization
- Kubernetes deployments
- GitHub Actions automation
- OpenTelemetry instrumentation
- Prometheus monitoring
- Grafana dashboards
- Load testing with Locust

---

## 💡 Technologies Used

- Docker
- Kubernetes
- Helm
- GitHub Actions
- OpenTelemetry
- Prometheus
- Grafana
- CI/CD
- Monitoring
- Observability
- Load Testing
  
---

## 🚀 Future Improvements

- Deploy on AWS EKS
- Add Terraform infrastructure
- Implement ArgoCD GitOps
- Integrate Trivy security scanning
- Add Slack notifications

---

## 📖 References

- OpenTelemetry Demo – https://github.com/open-telemetry/opentelemetry-demo
- Kubernetes Documentation – https://kubernetes.io/docs/
- Docker Documentation – https://docs.docker.com/
- Prometheus Documentation – https://prometheus.io/docs/
- Grafana Documentation – https://grafana.com/docs/

---

## 📌 Disclaimer

This project is based on the OpenTelemetry Demo application and was implemented for learning and portfolio purposes.

The deployment configuration, documentation, CI/CD workflow, and supporting DevOps practices have been customized to demonstrate my practical understanding of modern DevOps tools and workflows.
