# Advanced Deployment Patterns

This repo demonstrates:
- Blue/Green Deployment
- Canary Releases
- Scaling Multiple Replicas

## Usage

### Blue/Green Deployment
Apply blue and green versions:
```bash
kubectl apply -f deployments/blue-green/
```

### Canary Deployment
Apply canary version:
```bash
kubectl apply -f deployments/canary/
```

### Scaling Replicas
Apply scaled replicas:
```bash
kubectl apply -f deployments/replicas/
```
