# Terraform Infrastructure for SimpleTimeService

## Prerequisites

- Terraform installed
- AWS credentials configured (`aws configure` or environment variables)

## Usage

```bash
cd terraform
terraform init
terraform apply
```

## Notes

- Ensure `container_image` in `terraform.tfvars` points to your DockerHub image.
- This setup creates a VPC. Add ECS/ALB modules to deploy the app.
