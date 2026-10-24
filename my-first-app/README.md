# my-first-app

My first Backstage-deployed app

## Deployment

Deployed via ArgoCD GitOps.

- **Namespace:** `default`
- **Replicas:** 2 - 10

## Access

```bash
kubectl port-forward -n default svc/my-first-app 8080:80
```

Open http://localhost:8080
