# XOps Microchallenge #4 - EC2 Web App Deployment with Terraform & Ansible

This project automates the deployment of a static web page on an AWS EC2 instance using **Terraform** for provisioning and **Ansible** for configuration (NGINX + HTML setup).

---

## Project Structure

- `main.tf` – Terraform script 
- `inventory` – Contains EC2 public IP for Ansible
- `site.yml` – Ansible playbook
- `index.html` – Custom web page
- `screenshots/` – Folder with setup proof images

---

## Deployment Steps

1. **Terraform**  
   Initialize and apply the infrastructure:
   ```bash
   terraform init
   terraform apply

## Ansible

ansible-playbook -i inventory site.yml

## Clean up
terraform destroy

## Screenshots

Screenshots

**Terraform Apply Output**  
![Terraform Output](./screenshots/terraform-output.png)

**Ansible Playbook Success**  
![Ansible Output](./screenshots/ansible-success.png)

**NGINX Web Page**  
![Deployed Site](./screenshots/nginx-browser.png)

**XOps Challenge Completion**  
![Challenge Complete](./screenshots/Xops_MC4.png)

## Author
Pradhyu - Completed XOps MC - 4
