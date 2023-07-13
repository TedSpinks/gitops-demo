# gitops-demo

Directories include:
- **k8s-resources** - Helm and Kustomize manifests for deploying the cf-demo1 microservices.
- **argocd-definitions** - Argo CD application definitions, which tell Argo CD to keep target Kubernetes clusters in sync with the k8s-resources manifests.
