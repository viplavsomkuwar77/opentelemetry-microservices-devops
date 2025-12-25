![CI](https://github.com/viplavsomkuwar77/opentelemetry-microservices-devops/actions/workflows/pipeline.yml/badge.svg)

# OpenTelemetry Microservices DevOps Project

## 🧩 Project Context

This repository represents a microservices-based DevOps project that I worked on
during my **9-month DevOps internship**. The project environment was used to
implement, test, and continuously improve DevOps practices such as CI/CD
automation, Kubernetes deployments, and observability.

Due to confidentiality, this repository contains a recreated version that reflects
the **same tools, workflows, and DevOps practices** used in the actual environment.

---

## 🛠️ My Responsibilities

- Worked closely with multiple development teams to support DevOps practices
- Designed and improved CI/CD workflows using GitHub Actions
- Created and maintained Kubernetes deployment manifests
- Implemented observability using OpenTelemetry, Prometheus, and Grafana
- Performed load testing using Locust and analyzed system behavior
- Improved Docker configurations for selected microservices
- Continuously enhanced deployment scripts and configurations

---

## 🏗️ Architecture

![Architecture Diagram](architecture/architecture-diagram.png)

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

## 🔁 CI/CD Workflow

This repository contains a GitHub Actions workflow demonstrating the DevOps CI/CD flow.
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
