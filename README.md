# terraform-deployment

### General use

1. Code development
2. Code formatting with terraform fmt
3. Initialization with terraform init
4. Code validation with terraform validate
5. Planning with terraform plan
6. Manual verification of Terraform changes on the infrastructure

### Terraform integrated into CI\CD Pipeline
1. Retrieving the code from the SCM
2. Code formatting with terraform fmt
3. Initialization with terraform init
4. Code validation with terraform validate
5. Displaying a preview of the infrastructure changes with terraform plan
-out=out.tfplan
6. Applying changes in automatic mode with terraform apply --autoapprove out.tfplan

#### Store terraform.tfstate using cloud integration\secure backend: https://developer.hashicorp.com/terraform/language/settings/backends/remote
