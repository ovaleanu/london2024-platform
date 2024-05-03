# Backstage, Kratix, Crossplane and ArgoCD on EKS

Deploy Amazon EKS with addons configured via ArgoCD.
ArgoCD is used to deploy Kratix, Backstage and Crossplane with AWS Providers configured with IRSA.

Backstage WIP

<img src="https://github.com/ovaleanu/london2024-platform/blob/main/static/argo.png" width=100%>

### Deploy EKS Cluster
```shell
terraform init
terraform apply
```

### Access Terraform output to configure `kubectl` and `argocd`
```shell
terraform output
```

### Destroy EKS Cluster
```shell
./destroy.sh
```
#### Reference: 

- https://github.com/gitops-bridge-dev