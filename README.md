# Step 4 Simulator Service

This repository contains the Step 4 Simulator service which provides a mock API for testing. It includes logging and deployment configurations.

## Mock API Testing

The service includes endpoints that simulate the backend behavior for testing purposes.

### Endpoints
- **GET /api/simulate**: Returns a mock response for the simulation.
- **POST /api/simulate**: Accepts a request to simulate behavior and returns a mock response.

## Logging
The service uses a logging framework to maintain logs for all API requests and responses.

### Configuration
- Logging can be configured through environment variables.

## Deployment Configuration
The deployment configuration for the service is specified in the `docker-compose.yml` and Kubernetes manifests.

### Tools used
- Docker
- Kubernetes