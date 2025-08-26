# Mariano T. P. - DevOps & MLOps

DevOps & Cloud Engineer. Kubernetes (EKS/OpenShift), Terraform, CI/CD (Jenkins/GitHub Actions),
Docker/FastAPI, Observabilidad (Prometheus, Grafana) y MLOps (MLflow).

## Proyectos destacados

- **[Terraform Local Demo](https://github.com/mariano-tp/terraform-local-demo)** — Infra reproducible sin nubes (providers `local` + `random`). CI con `fmt`/`validate`.  
  [![terraform-ci](https://github.com/mariano-tp/terraform-local-demo/actions/workflows/terraform-ci.yml/badge.svg?branch=main&style=flat-square)](https://github.com/mariano-tp/terraform-local-demo/actions/workflows/terraform-ci.yml)

- **[Helm Chart Skeleton](https://github.com/mariano-tp/helm-chart-skeleton)** — Esqueleto de chart para despliegues en K8s con CI (lint + template) y release automático.  
  [![chart-ci](https://github.com/mariano-tp/helm-chart-skeleton/actions/workflows/chart-ci.yml/badge.svg?branch=main&style=flat-square)](https://github.com/mariano-tp/helm-chart-skeleton/actions/workflows/chart-ci.yml)

- **[FastAPI Observability Demo](https://github.com/mariano-tp/fastapi-observability-demo)** — Servicio FastAPI con `/metrics`, tests y CI (pytest + build Docker).  
  [![ci](https://github.com/mariano-tp/fastapi-observability-demo/actions/workflows/ci.yml/badge.svg?branch=main&style=flat-square)](https://github.com/mariano-tp/fastapi-observability-demo/actions/workflows/ci.yml)

- **[GitHub Observability Demo](https://github.com/mariano-tp/github-observability-demo)** — Stack Prometheus + Grafana + exporter para métricas de GitHub.  
  [![compose-validate](https://github.com/mariano-tp/github-observability-demo/actions/workflows/compose-validate.yml/badge.svg?branch=main&style=flat-square)](https://github.com/mariano-tp/github-observability-demo/actions/workflows/compose-validate.yml)

- **[ML Mini Pipeline](https://github.com/mariano-tp/ml-mini-pipeline)** — Mini pipeline de ML (scikit-learn) que genera datos sintéticos, entrena y publica artefactos (`model.pkl`, `metrics.json`) con CI.  
  [![ci](https://github.com/mariano-tp/ml-mini-pipeline/actions/workflows/ci.yml/badge.svg?branch=main&style=flat-square)](https://github.com/mariano-tp/ml-mini-pipeline/actions/workflows/ci.yml)

> Repos sin dependencias de empresas ni cuentas cloud; todo corre local o 100% online con GitHub Actions.

## Qué puedo aportar
- **Infra reproducible (Terraform/IaC):** módulos reutilizables, convenciones claras y validaciones (`fmt`/`validate`) integradas al CI.
- **CI/CD de apps y modelos:** pipelines con tests (pytest), build de contenedores, artefactos y releases semánticas en GitHub Actions.
- **Observabilidad práctica:** métricas de aplicación y de modelo (latencia/throughput/error-rate y drift básico), dashboards Grafana y checks de salud.
- **Serving y Kubernetes:** FastAPI para inferencia, imágenes Docker optimizadas (multi-stage) y despliegues con Helm (rollouts controlados).
- **Fundamentos de MLOps:** tracking de experimentos, versionado simple de datos/modelo, validación de datos y empaquetado de modelos para inferencia.
