# Liferay Portal Docker Setup

This repository contains the necessary configuration to run Liferay Portal using Docker and Dev Containers.

## Prerequisites

- Docker and Docker Compose installed

## How to Run Liferay Portal

### Using Docker Compose

1. Ensure Docker is running.
2. In the terminal, navigate to this repository's directory.
3. Run the following command:

   ```bash
   docker-compose up
   ```

4. Access Liferay Portal in your browser at: [http://localhost:8080](http://localhost:8080)

## Additional Configurations

- The `docker-compose.yaml` file defines the services and resource limits.

## Common Issues

- **Port 8080 is already in use:** Ensure no other service is using port 8080 before starting the container.
- **Memory errors:** Verify that Docker is configured to allocate at least 8GB of memory to containers.