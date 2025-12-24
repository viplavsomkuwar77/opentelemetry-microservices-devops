## Kubernetes Deployment

This directory contains Kubernetes manifests used to deploy the
OpenTelemetry microservices demo application.

- `complete-deploy.yaml` includes all core microservices such as
  Ads, Cart, Checkout, Payment, Recommendation, and Product Catalog.
- The manifest defines Services, Deployments, and ServiceAccounts
  required to run the application on a Kubernetes cluster.

This approach was used to understand end-to-end microservices
deployment and service communication within Kubernetes.
