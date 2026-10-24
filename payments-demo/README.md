# payments-demo

Payments demo application

## Deployment

Deployed via ArgoCD GitOps.

- **Namespace:** `payments-demo`
- **Replicas:** 2 - 10

## Access

```bash
kubectl port-forward -n payments-demo svc/payments-demo 8080:80
```

Open http://localhost:8080
