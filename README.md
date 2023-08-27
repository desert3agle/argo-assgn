Argo CD infra (assignment)

- find screenshots in /screenshots folder 

![apps and superapps](screenshots/apps-n-superapps.png)


### File Structure

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
├── kubectlManifests
│   ├── prod
│   │   ├── apache.yaml
│   │   ├── busybox.yaml
│   │   ├── guestbook.yaml
│   │   ├── nginx.yaml
│   │   ├── post-sync-hook.yaml
│   │   ├── pre-sync-hook.yaml
│   │   ├── redis.yaml
│   │   ├── sync-fail-hook.yaml
│   │   └── sync-hook.yaml
│   └── staging
│       ├── apache.yaml
│       ├── busybox.yaml
│       ├── guestbook.yaml
│       ├── nginx.yaml
│       ├── post-sync-hook.yaml
│       ├── pre-sync-hook.yaml
│       ├── redis.yaml
│       ├── sync-fail-hook.yaml
│       └── sync-hook.yaml
├── kustomize
│   └── kustomize-nginx-app
│       ├── base
│       │   ├── deployment.yaml
│       │   ├── kustomization.yaml
│       │   └── service.yaml
│       ├── kustomization.yaml
│       └── overlays
│           ├── prod
│           │   ├── deployment.yaml
│           │   ├── kustomization.yaml
│           │   └── namespace.yaml
│           └── staging
│               ├── deployment.yaml
│               ├── kustomization.yaml
│               └── namespace.yaml
```

