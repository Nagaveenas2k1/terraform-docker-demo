# Terraform Docker Provisioning Demo

This project demonstrates how to use Terraform to provision a local Docker container running NGINX.

## Prerequisites

- Docker Desktop
- Terraform

## How to Use

1. Clone this repo or copy files to a directory.
2. Make sure Docker Desktop is running.
3. Run the following in the project directory:
   - terraform init
   - terraform plan
   - terraform apply


4. Visit [http://localhost:8080](http://localhost:8080) to check the running NGINX container.
5. To clean up resources:
   - terraform destroy

  
## File Structure

- `main.tf` – Contains Terraform Docker provider and resources.
- `outputs.tf` – Outputs container ID.
- `providers.tf` – Specifies used provider.

### Author
S Nagaveena

