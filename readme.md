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

https://github.com/pradhyupradhyumna/Xops_Pradhyu_04/tree/460cbd4e166c933fe1a5366deeb483ce00c3076c/Screenshots

## Author
Pradhyu - Completed XOps MC - 4
