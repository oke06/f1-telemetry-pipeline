# F1 Telemetry Pipeline

Real-time data ingestion and API service for Formula 1 telemetry simulation.

## Architecture
- **Data Ingestion**: Python async service consuming high-frequency sensor data
- **API Service**: .NET service with dependency injection, async patterns
- **Orchestration**: Kubernetes deployment with monitoring (Prometheus/Grafana)

## Why This Project?
Demonstrates production-grade software engineering:
- Real-time, high-concurrency workloads
- DevOps maturity (Docker, K8s, CI/CD)
- Clean architecture (SOLID principles, design patterns)
- Monitoring & observability

## Tech Stack
- Python 3.10+ (async/await, aiohttp)
- .NET 7+ (C#, dependency injection, async)
- Docker & Kubernetes
- Prometheus & Grafana
- GitHub Actions (CI/CD)

## Getting Started
[You'll fill this in as you build]