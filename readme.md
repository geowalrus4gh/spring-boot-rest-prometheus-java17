# Spring Boot REST application with Prometheus support (Java 17)

This is a template application for Spring Boot REST application instrumented to
expose Prometheus metrics. This quickstart uses Java 17.

## Endpoints used by Kubernetes

This quickstart exposes the following endpoints important for Kubernetes deployments:
- `/actuator/health` - Spring Boot endpoint indicating health. Used by Kubernetes as readiness probe.
- `/actuator/metrics` - Prometheus metrics. Invoked periodically and collected by Prometheus Kubernetes scraper.
##Test build 13
