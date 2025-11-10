# ArgoCD

ArgoCD é uma ferramenta de Continuous Delivery declarativa para Kubernetes.

## Instalação

```bash
kubectl create namespace argocd
kubectl apply -n argocd -f https://raw.githubusercontent.com/argoproj/argo-cd/stable/manifests/install.yaml
```

## Acesso

```bash
kubectl port-forward svc/argocd-server -n argocd 8080:443
```

Referência: [ArgoCD Docs](https://argo-cd.readthedocs.io/)
