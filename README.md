# Swagger Demo API

Minimal **ASP.NET Core Web API** demonstrating **Swagger (OpenAPI)** running in **Docker**.

This repository is intended as a small, real-world example showing:
- how to create a simple ASP.NET Core web service
- how to add Swagger via a NuGet package
- how to build and run the service using Docker and Docker Compose

## Features

- ASP.NET Core (.NET 8)
- Swagger UI (OpenAPI) via `Swashbuckle.AspNetCore`
- Docker multi-stage build
- Docker Compose setup
- Minimal API style

## Getting started

### Build and run with Docker Compose

```bash
docker compose up --build
```

The API will be available at:

- Hello endpoint: http://localhost:8080
- Health endpoint: http://localhost:8080/health
- Swagger UI: http://localhost:8080/swagger

