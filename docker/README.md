## Docker Deployment

Selected microservices in this project are containerized using Docker. Each 
Dockerfile corresponds to a service (e.g., frontend, cart, checkout).

Docker images are built locally and used for Kubernetes deployment. This setup 
supports consistent environments, service isolation, and CI/CD integration.

Docker Compose and Make were used during local development to bring up the 
OpenTelemetry demo stack for testing and validation.
