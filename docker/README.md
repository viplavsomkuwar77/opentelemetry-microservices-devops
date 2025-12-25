## Docker Deployment

Selected microservices in this project are containerized using Docker.

Docker images are built for individual services and used by Kubernetes
for deployment. The Docker setup supports:

- Consistent runtime environments
- Easy service isolation
- Seamless integration with CI/CD pipelines

Docker Compose and Make were used during local development to spin up
the OpenTelemetry microservices stack for testing and validation.
