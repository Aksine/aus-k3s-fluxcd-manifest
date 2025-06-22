# aus-k3s-fluxcd-manifest
Kubernetes Flux manifests for my Melbourne Kubernetes homelab cluster

this repo contains the GitOps config files for managing my K3s cluster using FluxCD for my australian site

## Repo structure
├── cluster/
│   └── aus/
│       ├── flux-system/           # Flux controllers and configuration
│       ├── infra/        # Infrastructure components (ingress, monitoring, etc.)
│       ├── apps/                  # Application deployments

