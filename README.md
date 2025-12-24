🚀 OpenTelemetry Microservices DevOps Project

📌 Overview

This project demonstrates a production-like microservices architecture deployed on Kubernetes and instrumented with OpenTelemetry for complete observability (logs, metrics, and traces).

It simulates an e-commerce application composed of multiple microservices such as Cart, Checkout, Payment, Recommendation, and Product Catalog.
The project focuses on DevOps best practices, including containerization, CI/CD automation, observability, and load testing.

🏗 Architecture

![Project-arch](https://github.com/user-attachments/assets/8ebfc5ba-d14f-4667-9f05-61a9dc0acdc2)


🧩 Microservices

• Frontend

• Product Catalog

• Recommendation Service

• Cart Service

• Checkout Service

• Payment Service

• Ads Service

• Shipping Service

• Email Service

🛠 Tech Stack

Containers & Orchestration

• Docker

• Kubernetes

• Helm

CI/CD

• GitHub Actions

Observability

• OpenTelemetry

• Prometheus

• Grafana

Load Testing

• Locust

🔁 CI/CD Pipeline

GitHub Actions pipeline automatically:

• Builds Docker images

• Pushes images to container registry

• Deploys microservices to Kubernetes using Helm

📊 Observability

• Integrated OpenTelemetry SDK in all services

• Configured OpenTelemetry Collector

• Collected:

  • Traces for distributed request tracking

  • Metrics for service performance

  • Logs for debugging

• Visualized metrics and traces using Prometheus and Grafana

📈 Load Testing

• Used Locust to generate traffic

• Validated system performance under load

• Observed latency and error rates via dashboards

🎯 Key DevOps Learnings

• Kubernetes-based microservices deployment

• CI/CD automation using GitHub Actions

• End-to-end observability using OpenTelemetry

• Monitoring and troubleshooting distributed systems

• Load testing and performance analysis
