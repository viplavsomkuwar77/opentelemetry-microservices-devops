## Kubernetes Manifests

This directory contains Kubernetes manifests used to deploy the
OpenTelemetry microservices demo application.

### Manifests
- `manifests/complete-deploy.yaml`  
  Deploys all core microservices including Ads, Cart, Checkout,
  Payment, Recommendation, Product Catalog, and supporting services.

The manifest defines Kubernetes Deployments, Services, and
ServiceAccounts required to run the application on a cluster.
