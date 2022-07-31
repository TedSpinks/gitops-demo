# cf-demo1_gitops

GitOps repo for deploying the microservices that are stored in repo [cf-demo1](https://github.com/codefresh-contrib/cf-demo1).

Directories include:
- **k8s-resources** - Helm and Kustomize manifests for deploying the cf-demo1 microservices.
- **argocd-definitions** - Argo CD application definitions, which tell Argo CD to keep target Kubernetes clusters in sync with the k8s-resources manifests.
- **workflow-templates** - Shared Argo WorkflowTemplates used in the CI and Promotion pipelines of the cf-demo1 microservices.
