# Mariano T. P. - DevOps & MLOps

DevOps & Cloud Engineer. Kubernetes (EKS/OpenShift), Terraform, CI/CD (Jenkins/GitHub Actions),
Docker/FastAPI, Observabilidad (Prometheus, Grafana) y MLOps (MLflow).

## Proyectos destacados

### Infraestructura como código
- **[Terraform Local Demo](https://github.com/mariano-tp/terraform-local-demo)** – Infra reproducible sin nubes (providers `local` + `random`). CI con `fmt`/`validate`.  
  [![terraform-ci](https://github.com/mariano-tp/terraform-local-demo/actions/workflows/terraform-ci.yml/badge.svg?branch=main&style=flat-square)](https://github.com/mariano-tp/terraform-local-demo/actions/workflows/terraform-ci.yml)

- **[AWS Serverless Local Demo](https://github.com/mariano-tp/aws-serverless-local-demo)** – Serverless “sin cloud”: **S3 + SQS + DynamoDB** en LocalStack, con tests de integración y CI en GitHub Actions.  
  [![ci](https://github.com/mariano-tp/aws-serverless-local-demo/actions/workflows/ci.yml/badge.svg?branch=main&style=flat-square)](https://github.com/mariano-tp/aws-serverless-local-demo/actions/workflows/ci.yml)

### Kubernetes & Delivery
- **[Helm Chart Skeleton](https://github.com/mariano-tp/helm-chart-skeleton)** – Esqueleto de chart para despliegues en K8s con CI (lint + template) y release automático.  
  [![chart-ci](https://github.com/mariano-tp/helm-chart-skeleton/actions/workflows/chart-ci.yml/badge.svg?branch=main&style=flat-square)](https://github.com/mariano-tp/helm-chart-skeleton/actions/workflows/chart-ci.yml)

- **[Kubernetes Admin Ops Kit](https://github.com/mariano-tp/k8s-admin-ops-kit)** – Runbooks-as-code para un administrador de K8s: playbooks Ansible (cordon/drain, restart ordenado, rollback), chart Helm (api/worker/nlp con probes, PDB y NetworkPolicy) y CI en GitHub Actions con KinD.  
  [![ci](https://github.com/mariano-tp/k8s-admin-ops-kit/actions/workflows/ci.yml/badge.svg?branch=main&style=flat-square)](https://github.com/mariano-tp/k8s-admin-ops-kit/actions/workflows/ci.yml)

### Observabilidad
- **[FastAPI Observability Demo](https://github.com/mariano-tp/fastapi-observability-demo)** – Servicio FastAPI con `/metrics`, tests y CI (pytest + build Docker).  
  [![ci](https://github.com/mariano-tp/fastapi-observability-demo/actions/workflows/ci.yml/badge.svg?branch=main&style=flat-square)](https://github.com/mariano-tp/fastapi-observability-demo/actions/workflows/ci.yml)

- **[GitHub Observability Demo](https://github.com/mariano-tp/github-observability-demo)** – Stack Prometheus + Grafana + exporter para métricas de GitHub.  
  [![compose-validate](https://github.com/mariano-tp/github-observability-demo/actions/workflows/compose-validate.yml/badge.svg?branch=main&style=flat-square)](https://github.com/mariano-tp/github-observability-demo/actions/workflows/compose-validate.yml)

### MLOps
- **[ML Mini Pipeline](https://github.com/mariano-tp/ml-mini-pipeline)** – Mini pipeline de ML (scikit-learn) que genera datos sintéticos, entrena y publica artefactos (`model.pkl`, `metrics.json`) con CI.  
  [![ci](https://github.com/mariano-tp/ml-mini-pipeline/actions/workflows/ci.yml/badge.svg?branch=main&style=flat-square)](https://github.com/mariano-tp/ml-mini-pipeline/actions/workflows/ci.yml)

- **[MLflow Mini Experiments](https://github.com/mariano-tp/mlflow-mini-experiments)** – Tracking de experimentos con **MLflow**: logging de parámetros, métricas y modelos, CI reproducible en GitHub Actions y opción de UI local con Docker Compose.  
  [![ci](https://github.com/mariano-tp/mlflow-mini-experiments/actions/workflows/ci.yml/badge.svg?branch=main&style=flat-square)](https://github.com/mariano-tp/mlflow-mini-experiments/actions/workflows/ci.yml)


> Repos sin dependencias de empresas ni cuentas cloud; todo corre local o 100% online con GitHub Actions.

## Qué puedo aportar
- **Infra reproducible (Terraform/IaC):** módulos reutilizables, convenciones claras y validaciones (`fmt`/`validate`) integradas al CI.
- **AWS serverless sin cuenta cloud:** diseño y pruebas de **S3 + SQS + DynamoDB** en **LocalStack**, con tests de integración y bootstrapping automatizado.
- **Kubernetes & delivery:** empaquetado con **Helm**, despliegues versionados y rollouts controlados.
- **Observabilidad práctica:** métricas de app y de modelo (latencia/throughput/error-rate, drift básico), dashboards Grafana y health checks.
- **CI/CD de apps y modelos:** pipelines con **pytest**, build de contenedores, artefactos y releases semánticas en GitHub Actions.
- **Fundamentos de MLOps:** desde pipelines simples (scikit-learn) hasta **tracking de experimentos en MLflow**, versionado de modelos y reproducibilidad.
