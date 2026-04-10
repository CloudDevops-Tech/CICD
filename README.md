# CICD Project

## Tools Used
- Jenkins.
- GitHub Actions.
- Terraform.

### Day 1
- Installed Java V17.0.18,Jenkins V2.541.3 and Terraform v1.14.8 on top of the EC2 Insatnce.
- Executed Jenkins pipeline to run Terraform configuration from Day1_Terraform_Basic_Config.


### Day 2
- Created Infrastructure using GitHub Actions Workflow pipeline by using Terraform.
- Automated deployment of a Python app to an EC2 instance using GitHub Actions via SSH.
-Implemented CI/CD pipeline using Jenkins to deploy a Python application from GitHub to an Ubuntu EC2 instance via SSH.

### Day 3
## CI/CD Pipeline
GitHub Actions workflow using self-hosted runners:
- git-runner → code checkout
- terraform-runner → Terraform init/plan/apply with approval gate