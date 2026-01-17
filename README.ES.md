> Available languages / Idiomas disponibles: [*English*](README.md) / [*Español*](README.ES.md)

# Mariano Enrique Torres Ponce - DevOps & MLOps

Cloud & DevOps Engineer enfocado en infraestructura resiliente y reproducible, y en automatización MLOps. Construyo pipelines CI/CD, entrega con Kubernetes/Helm y stacks de observabilidad que pueden ejecutarse localmente o en cloud, sin dependencia de proveedores para demos y testing.

- Kubernetes (EKS/OpenShift) · Terraform/IaC · CI/CD (GitHub Actions/Jenkins)  
- Docker/FastAPI · Observabilidad (Prometheus, Grafana) · MLOps (MLflow)

## Highlights
- Workflows de IaC y delivery reproducibles, con validación automática, linting y releases.
- Patrones serverless en AWS emulados localmente (LocalStack) para tests de integración rápidos y sin costos.
- Observabilidad práctica para apps y modelos: métricas, dashboards y chequeos básicos de drift.
- Tracking de experimentos y versionado de artefactos con MLflow para ciclos de vida de ML trazables.

## Proyectos destacados

### Infrastructure as Code
- **[Terraform Local Demo](https://github.com/mariano-tp/terraform-local-demo)** - Infraestructura reproducible sin proveedores cloud (`local` + `random`). CI con `fmt` y `validate`.  
  [![terraform-ci](https://github.com/mariano-tp/terraform-local-demo/actions/workflows/terraform-ci.yml/badge.svg?branch=main&style=flat-square)](https://github.com/mariano-tp/terraform-local-demo/actions/workflows/terraform-ci.yml)

- **[AWS Serverless Local Demo](https://github.com/mariano-tp/aws-serverless-local-demo)** - Serverless “sin cloud”: S3 + SQS + DynamoDB sobre LocalStack, con tests de integración y CI en GitHub Actions.  
  [![ci](https://github.com/mariano-tp/aws-serverless-local-demo/actions/workflows/ci.yml/badge.svg?branch=main&style=flat-square)](https://github.com/mariano-tp/aws-serverless-local-demo/actions/workflows/ci.yml)

### Kubernetes & Delivery
- **[Helm Chart Skeleton](https://github.com/mariano-tp/helm-chart-skeleton)** - Esqueleto de Helm Chart para despliegues en Kubernetes, con CI (lint + template) y releases automatizados.  
  [![chart-ci](https://github.com/mariano-tp/helm-chart-skeleton/actions/workflows/chart-ci.yml/badge.svg?branch=main&style=flat-square)](https://github.com/mariano-tp/helm-chart-skeleton/actions/workflows/chart-ci.yml)

- **[Kubernetes Admin Ops Kit](https://github.com/mariano-tp/k8s-admin-ops-kit)** - Runbooks-as-code para administradores de Kubernetes: playbooks Ansible (cordon/drain, reinicios ordenados, rollback), Helm Chart (api/worker/nlp con probes, PDB, NetworkPolicy) y CI con KinD.  
  [![ci](https://github.com/mariano-tp/k8s-admin-ops-kit/actions/workflows/ci.yml/badge.svg?branch=main&style=flat-square)](https://github.com/mariano-tp/k8s-admin-ops-kit/actions/workflows/ci.yml)

### Observabilidad
- **[FastAPI Observability Demo](https://github.com/mariano-tp/fastapi-observability-demo)** - Servicio FastAPI con `/metrics`, tests y CI (pytest + build de Docker).  
  [![ci](https://github.com/mariano-tp/fastapi-observability-demo/actions/workflows/ci.yml/badge.svg?branch=main&style=flat-square)](https://github.com/mariano-tp/fastapi-observability-demo/actions/workflows/ci.yml)

- **[GitHub Observability Demo](https://github.com/mariano-tp/github-observability-demo)** - Stack de Prometheus + Grafana + exporter para métricas de GitHub.  
  [![compose-validate](https://github.com/mariano-tp/github-observability-demo/actions/workflows/compose-validate.yml/badge.svg?branch=main&style=flat-square)](https://github.com/mariano-tp/github-observability-demo/actions/workflows/compose-validate.yml)

### MLOps
- **[ML Mini Pipeline](https://github.com/mariano-tp/ml-mini-pipeline)** - Mini pipeline de ML (scikit-learn) que genera datos sintéticos, entrena y publica artefactos (`model.pkl`, `metrics.json`) con CI.  
  [![ci](https://github.com/mariano-tp/ml-mini-pipeline/actions/workflows/ci.yml/badge.svg?branch=main&style=flat-square)](https://github.com/mariano-tp/ml-mini-pipeline/actions/workflows/ci.yml)

- **[MLflow Mini Experiments](https://github.com/mariano-tp/mlflow-mini-experiments)** - Tracking de experimentos con MLflow: parámetros, métricas y modelos; CI reproducible; UI local opcional con Docker Compose.  
  [![ci](https://github.com/mariano-tp/mlflow-mini-experiments/actions/workflows/ci.yml/badge.svg?branch=main&style=flat-square)](https://github.com/mariano-tp/mlflow-mini-experiments/actions/workflows/ci.yml)

> Todos los repos están libres de dependencias corporativas o de cloud: todo puede ejecutarse localmente o validarse completamente online mediante GitHub Actions.

## Skills
- IaC: Terraform (módulos, workspaces), nociones de policy-as-code, validaciones en CI
- Kubernetes: empaquetado con Helm, estrategias de rollout, PDB/NetworkPolicy, KinD para CI
- CI/CD: GitHub Actions, Jenkins, versionado semántico y releases automatizados
- Observabilidad: exporters de Prometheus, dashboards en Grafana, health checks
- Python & APIs: servicios FastAPI, pytest, builds dockerizados
- MLOps: tracking con MLflow, gestión de artefactos/versiones, monitoreo básico de drift

## Publicaciones y perfiles
- [Google Scholar](https://scholar.google.com/citations?hl=en&user=FCQXlNMAAAAJ)  
- [GitHub](https://github.com/mariano-tp/academic-impact/blob/main/README.ES.md)
