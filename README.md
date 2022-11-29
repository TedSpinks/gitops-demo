# cf-demo1_gitops

[![GitHub Super-Linter](https://github.com/TedSpinks/cf-demo1_gitops/workflows/Lint%20Code%20Base/badge.svg)](https://github.com/marketplace/actions/super-linter)
GitOps repository for deploying the microservices that are stored in repo [cf-demo1](https://github.com/codefresh-contrib/cf-demo1).

Directories include:
- **k8s-resources** - Helm and Kustomize manifests for deploying the cf-demo1 microservices.
- **argocd-definitions** - Argo CD application definitions, which tell Argo CD to keep target Kubernetes clusters in sync with the k8s-resources manifests.
- **workflow-templates** - Shared Argo WorkflowTemplates used in the CI and Promotion pipelines of the cf-demo1 microservices.
