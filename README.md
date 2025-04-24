# AWS Cloud School 9기 - A조

## HELM CHART
2025.04.17-2025.04.18 진행한 Kubernetes Infra Toy Project 입니다.

### 설치 방법
```bash
helm repo add myrepo1 https://musclefrog.github.io/aws9argocd
helm install myrelease1 myrepo1/aws9a-helm

or
helm install myrelease1 myrepo1/aws9a-helm --set replicaCount=8
```
