# logistics-prod

Production logistics application

## Deployment

Deployed via ArgoCD GitOps.

- **Namespace:** `logistics-prod`
- **Replicas:** 2 - 10

## Access

```bash
kubectl port-forward -n logistics-prod svc/logistics-prod 8080:80
```

Open http://localhost:8080
