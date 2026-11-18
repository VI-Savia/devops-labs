# Основи DevOps — лабораторні роботи 3–7

Загальні частини лабораторних робіт. Індивідуальний проєкт (варіант 6, «Соціальна платформа для клубів») — в окремому репозиторії [club-platform](https://github.com/VI-Savia/club-platform).

| Папка | Тема |
|---|---|
| `lab3/` | Docker, Docker Compose |
| `lab4/` | Kubernetes (kind): Deployment, Service, Helm, HPA, RBAC, Ingress |
| `lab5/` | HashiCorp Vault, Terraform (LocalStack) |
| `lab6/` | Ansible |
| `lab7/` | Prometheus, Grafana, Jaeger, Loki, ArgoCD |

У кожній папці: `ЗВІТ.md` — хід роботи, `logs/` — вивід команд, `logs-windows/` — повторний запуск на Windows 10.

## Середовище (Windows 10)

Docker Desktop (WSL2), kind, kubectl, Helm, Terraform, argocd CLI, PowerShell 7.
Ansible під Windows не працює, тому для ЛР6 є керуючий контейнер `lab6/control/` (Debian + ansible-core + kubectl + helm).
