# DevOps Project (Production Ready)

## Stack
- Terraform (VPC + EKS)
- Helm (Kubernetes templates)
- Jenkins (CI)
- ArgoCD (GitOps CD)

## Flow
1. Push code
2. Jenkins builds & pushes image
3. Updates Helm values
4. ArgoCD auto deploys
