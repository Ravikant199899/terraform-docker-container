# Terraform Docker Container Provisioning

## 📌 Objective
Provision a Docker container (nginx) using Terraform on a local environment (EC2 Ubuntu).

## 🧰 Tools Used
- Terraform v1.8.3
- Docker vXX
- Ubuntu EC2

## 📝 Steps Followed
1. Installed Terraform and Docker
2. Wrote `main.tf` using Docker provider
3. Initialized Terraform using `terraform init`
4. Planned and applied the infra
5. Verified container with `docker ps`
6. Checked terraform state
7. Destroyed infra using `terraform destroy`

## 📷 Screenshots

### 1. Terraform Version
![Terraform Version](Terraform-Version.png)

### 2. Docker Version
![Docker Version](Docker-Version.png)

### 3. main.tf Code
![main.tf File](mainTF.png)

### 4. Terraform Init
![Terraform Init](Terraform-init.png)

### 5. Terraform Plan
![Terraform Plan](Terraform-plan.png)

### 6. Terraform Apply
![Terraform Apply](terraform-apply.png)

### 7. Docker PS Output
![Docker PS](docker-ps.png)

### 8. Terraform State List
![Terraform State](Terraform-state-list.png)

### 9. Terraform Destroy
![Terraform Destroy](terraform-destroy.png)

## ✅ Outcome
Understood how to use Terraform as Infrastructure as Code (IaC) to provision and manage Docker containers.

## 💻 Author
Ravikant Jadhav  
[GitHub Profile](https://github.com/Ravikant199899)
