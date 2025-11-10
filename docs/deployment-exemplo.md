# Exemplo de Deployment

Exemplo simples de deployment Nginx:

```yaml
apiVersion: apps/v1
kind: Deployment
metadata:
  name: nginx-deployment
spec:
  replicas: 2
  selector:
    matchLabels:
      app: nginx
  template:
    metadata:
      labels:
        app: nginx
    spec:
      containers:
      - name: nginx
        image: nginx:latest
        ports:
        - containerPort: 80
```

```bash
kubectl apply -f deployment.yaml
kubectl get pods
kubectl get svc
```

Referência: [Deployments - Kubernetes.io](https://kubernetes.io/docs/concepts/workloads/controllers/deployment/)
