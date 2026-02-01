> Available languages / Idiomas disponibles: [*English*](README.md) / [*Español*](README.ES.md)

# Mariano Enrique Torres Ponce - DevOps & MLOps

Cloud & DevOps Engineer focused on resilient, reproducible infrastructure and MLOps automation. I build CI/CD pipelines, Kubernetes/Helm delivery, and observability stacks that run locally or in the cloud-with zero vendor lock-in for demos and testing.

- Kubernetes (EKS/OpenShift) · Terraform/IaC · CI/CD (GitHub Actions/Jenkins)  
- Docker/FastAPI · Observability (Prometheus, Grafana) · MLOps (MLflow)

## Highlights
- Reproducible IaC and delivery workflows with automated validation, linting, and releases.
- Serverless patterns on AWS emulated locally (LocalStack) for fast, cost-safe integration tests.
- Hands-on observability for apps and models: metrics, dashboards, basic drift checks.
- Experiment tracking and artifact versioning with MLflow for traceable ML lifecycles.

## Featured Projects

### Infrastructure as Code
- **[Terraform Local Demo](https://github.com/metorresponce/terraform-local-demo/blob/main/README.md)** - Reproducible infra without cloud providers (`local` + `random`). CI with `fmt` and `validate`.  
  [![terraform-ci](https://github.com/metorresponce/terraform-local-demo/actions/workflows/terraform-ci.yml/badge.svg?branch=main&style=flat-square)](https://github.com/metorresponce/terraform-local-demo/actions/workflows/terraform-ci.yml)

- **[AWS Serverless Local Demo](https://github.com/metorresponce/aws-serverless-local-demo/blob/main/README.md)** - Serverless “without the cloud”: S3 + SQS + DynamoDB on LocalStack, with integration tests and CI in GitHub Actions.  
  [![ci](https://github.com/metorresponce/aws-serverless-local-demo/actions/workflows/ci.yml/badge.svg?branch=main&style=flat-square)](https://github.com/metorresponce/aws-serverless-local-demo/actions/workflows/ci.yml)

### Kubernetes & Delivery
- **[Helm Chart Skeleton](https://github.com/metorresponce/helm-chart-skeleton/blob/main/README.md)** - Chart skeleton for K8s deployments with CI (lint + template) and automated releases.  
  [![chart-ci](https://github.com/metorresponce/helm-chart-skeleton/actions/workflows/chart-ci.yml/badge.svg?branch=main&style=flat-square)](https://github.com/metorresponce/helm-chart-skeleton/actions/workflows/chart-ci.yml)

- **[Kubernetes Admin Ops Kit](https://github.com/metorresponce/k8s-admin-ops-kit/blob/main/README.md)** - Runbooks-as-code for K8s admins: Ansible playbooks (cordon/drain, ordered restarts, rollback), Helm chart (api/worker/nlp with probes, PDB, NetworkPolicy), and CI with KinD.  
  [![ci](https://github.com/metorresponce/k8s-admin-ops-kit/actions/workflows/ci.yml/badge.svg?branch=main&style=flat-square)](https://github.com/metorresponce/k8s-admin-ops-kit/actions/workflows/ci.yml)

### Observability
- **[FastAPI Observability Demo](https://github.com/metorresponce/fastapi-observability-demo/blob/main/README.md)** - FastAPI service with `/metrics`, tests, and CI (pytest + Docker build).  
  [![ci](https://github.com/metorresponce/fastapi-observability-demo/actions/workflows/ci.yml/badge.svg?branch=main&style=flat-square)](https://github.com/metorresponce/fastapi-observability-demo/actions/workflows/ci.yml)

- **[GitHub Observability Demo](https://github.com/metorresponce/github-observability-demo/blob/main/README.md)** - Prometheus + Grafana stack + exporter for GitHub metrics.  
  [![compose-validate](https://github.com/metorresponce/github-observability-demo/actions/workflows/compose-validate.yml/badge.svg?branch=main&style=flat-square)](https://github.com/metorresponce/github-observability-demo/actions/workflows/compose-validate.yml)

### MLOps
- **[ML Mini Pipeline](https://github.com/metorresponce/ml-mini-pipeline/blob/main/README.md)** - Mini ML pipeline (scikit-learn) that generates synthetic data, trains, and publishes artifacts (`model.pkl`, `metrics.json`) with CI.  
  [![ci](https://github.com/metorresponce/ml-mini-pipeline/actions/workflows/ci.yml/badge.svg?branch=main&style=flat-square)](https://github.com/metorresponce/ml-mini-pipeline/actions/workflows/ci.yml)

- **[MLflow Mini Experiments](https://github.com/metorresponce/mlflow-mini-experiments/blob/main/README.md)** - Experiment tracking with MLflow: parameters, metrics, and models; reproducible CI; optional local UI with Docker Compose.  
  [![ci](https://github.com/metorresponce/mlflow-mini-experiments/actions/workflows/ci.yml/badge.svg?branch=main&style=flat-square)](https://github.com/metorresponce/mlflow-mini-experiments/actions/workflows/ci.yml)

> All repos are free of corporate/cloud dependencies; everything runs locally or fully online via GitHub Actions.

## Skills
- IaC: Terraform (modules, workspaces), policy-as-code basics, validations in CI
- Kubernetes: Helm packaging, rollout strategies, PDB/NetworkPolicy, KinD for CI
- CI/CD: GitHub Actions, Jenkins, semantic versioning and automated releases
- Observability: Prometheus exporters, Grafana dashboards, health checks
- Python & APIs: FastAPI services, pytest, Dockerized builds
- MLOps: MLflow tracking, artifact/version management, basic drift monitoring

## Publications & Profiles
- [Google Scholar](https://scholar.google.com/citations?hl=en&user=FCQXlNMAAAAJ)  
- [GitHub](https://github.com/metorresponce/academic-impact/blob/main/README.md)
