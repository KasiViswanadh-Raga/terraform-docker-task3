# Task 3 - Infrastructure as Code (IaC) with Terraform

## 🚀 Objective
Provision a *Docker container* using *Terraform* as part of the DevOps Internship Task 3.

---

## 🛠 Tools Used
- *Terraform*
- *Docker*
- *GitHub*

---

## 📋 What I Did
- Used Terraform's Docker provider to provision infrastructure.
- Pulled the official nginx Docker image.
- Created and exposed an nginx container on port 8080.
- Verified container status using docker ps.
- Managed infra lifecycle with terraform init, plan, apply, and destroy.
- Captured and attached all relevant screenshots.

---

## 📁 Files Included
- main.tf – Terraform code
- README.md – This documentation
- 6 screenshots showing each step
- Terraform logs available in terminal history

---

## 📸 Screenshots

### 1. Terraform Init
![Terraform Init](screenshot1-init.png)

### 2. Terraform Plan
![Terraform Plan](screenshot2-plan.png)

### 3. Terraform Apply
![Terraform Apply](screenshot3-apply.png)

### 4. Docker Container Running
![Docker Container Running](screenshot4-running.png)

### 5. Terraform State
![Terraform State](screenshot5-state.png)

### 6. Terraform Destroy
![Terraform Destroy](screenshot6-destroy.png)

---

## ⚙ Commands Used

```bash
terraform init
terraform plan
terraform apply
docker ps
terraform state list
terraform destroy


---

✅ Outcome

Successfully used Terraform to provision Docker container locally.

Learned core IaC concepts like provider, resource, state file, and resource lifecycle management.
