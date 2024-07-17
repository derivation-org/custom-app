## Application Repository

This repository contains our application code and CI/CD pipeline. GitHub Actions automate building and pushing Docker images to Azure Container Registry, and updating Kubernetes manifests. ArgoCD monitors these changes, automatically deploying updates to our AKS cluster for swift and consistent deployments.
