# Opentelemetry Deployment


## Terraform

Create the resources in backend folder in terraform.
```
terraform init
terraform plan
terraform apply
```
Repeat this action in the terraform root folder to create EKS and VPC.

## Kubernetes

For deploying on EKS use the following command:
```
kubectl apply -f .
```
