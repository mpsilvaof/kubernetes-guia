# EKS (Amazon Elastic Kubernetes Service)

O EKS é o serviço gerenciado de Kubernetes da AWS.

## Criação de Cluster (CLI)
```bash
eksctl create cluster --name meu-cluster --region us-east-1 --nodes 2
```

## Integração com kubectl
```bash
aws eks update-kubeconfig --name meu-cluster --region us-east-1
kubectl get nodes
```

Referência: [AWS EKS Docs](https://docs.aws.amazon.com/eks/latest/userguide/what-is-eks.html)
