# logistics-demo

Logistics demo application

## Deployment

Deployed via ArgoCD GitOps.

- **Namespace:** `logistics-demo`
- **Replicas:** 2 - 10

## Access

```bash
kubectl port-forward -n logistics-demo svc/logistics-demo 8080:80
```

Open http://localhost:8080
