```
.
├── README.md
├── argoApps
│   ├── kustomize
│   │   ├── nginx-prod.yaml
│   │   └── nginx-staging.yaml
│   ├── prod-cluster
│   │   └── app-gen.yaml
│   └── staging-cluster
│       └── app-gen.yaml
├── argoHooks
│   ├── post-sync-hook.yaml
│   ├── pre-sync-hook.yaml
│   ├── sync-fail-hook.yaml
│   └── sync-hook.yaml
├── kubectlManifests
│   ├── prod
│   │   ├── apache.yaml
│   │   ├── busybox.yaml
│   │   ├── guestbook.yaml
│   │   ├── nginx.yaml
│   │   └── redis.yaml
│   └── staging
│       ├── apache.yaml
│       ├── busybox.yaml
│       ├── guestbook.yaml
│       ├── nginx.yaml
│       └── redis.yaml
└── kustomize
    └── kustomize-nginx-app
        ├── base
        │   ├── deployment.yaml
        │   ├── kustomization.yaml
        │   └── service.yaml
        ├── kustomization.yaml
        └── overlays
            ├── prod
            │   ├── deployment.yaml
            │   ├── kustomization.yaml
            │   └── namespace.yaml
            └── staging
                ├── deployment.yaml
                ├── kustomization.yaml
                └── namespace.yaml

```