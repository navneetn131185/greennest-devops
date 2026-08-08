# GreenNest DevOps

GreenNest is a full-stack plant-store application prepared as a DevOps and security portfolio project. It includes a Java/Spring Boot backend, React frontend, Docker Compose stack, Prometheus/Grafana monitoring, and GitHub Actions security checks.

## Included DevOps tooling

- Docker and Docker Compose for local deployment
- GitHub Actions CI, CodeQL, Trivy, Gitleaks, and OWASP ZAP workflows
- Dependabot configuration
- Prometheus metrics and a provisioned Grafana dashboard

## Run locally

1. Copy `.env.example` to `.env` and replace all `change_me` values with strong local secrets.
2. Run `docker compose up --build`.
3. Open the frontend at `http://localhost:5173`, Grafana at `http://localhost:3000`, and Prometheus at `http://localhost:9090`.

`.env` is deliberately ignored by Git. Do not add credentials, private keys, or production configuration to the repository.
