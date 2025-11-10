# Comandos Essenciais

Alguns comandos `kubectl` úteis para administração diária.

```bash
# Ver todos os pods
kubectl get pods -A

# Ver deployments
kubectl get deployments

# Aplicar configuração
kubectl apply -f arquivo.yaml

# Descrever um recurso
kubectl describe pod <nome>

# Acessar shell dentro de um pod
kubectl exec -it <pod> -- /bin/sh
```

Referência: [kubectl Reference](https://kubernetes.io/docs/reference/kubectl/)
