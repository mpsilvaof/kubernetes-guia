# Armazenamento (Storage)

O Kubernetes suporta diferentes tipos de volumes e persistência de dados.

## Tipos de Storage
- **emptyDir:** temporário, excluído quando o pod é removido.
- **hostPath:** usa diretórios do node (para uso local).
- **PersistentVolume (PV)** e **PersistentVolumeClaim (PVC):** para armazenamento persistente.
- **StorageClass:** define provisionamento dinâmico.

Referência: [Volumes - Kubernetes.io](https://kubernetes.io/docs/concepts/storage/)
