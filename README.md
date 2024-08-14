# GitOps Project - README
In this project, I implemented a GitOps workflow to manage and deploy both infrastructure and applications using Git.

# What I Did:

-Set up two Git repositories: one for Terraform code to manage AWS infrastructure and another for the application code.

-Created CI/CD pipelines using GitHub Actions to automate the deployment process.
   
  - -The infrastructure pipeline manages AWS resources using Terraform.
   
  - -The application pipeline builds, tests, and deploys the application using Docker, Maven, and Helm.

-Ensured that all changes to the infrastructure and application are tracked and versioned in Git, following GitOps principles.

This setup streamlines deployments and enhances consistency, traceability, and automation.
# Terraform code 

## Maintain vpc & eks with terraform for vprofile project

## Tools required
Terraform version 1.6.3

### Steps
* terraform init
* terraform fmt -check
* terraform validate
* terraform plan -out planfile
* terraform apply -auto-approve -input=false -parallelism=1 planfile
####
#####
