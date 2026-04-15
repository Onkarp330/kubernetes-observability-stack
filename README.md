# Kubernetes Observability Stack

This project deploys a basic monitoring stack for Kubernetes using Prometheus and Grafana.

## Components

Prometheus  
- Metrics collection system

Grafana  
- Visualization dashboards

## Deployment

Apply manifests:

```
kubectl apply -f prometheus/
kubectl apply -f grafana/
```

Access Grafana:

```
kubectl get svc grafana-service
```

Open the NodePort in browser.
