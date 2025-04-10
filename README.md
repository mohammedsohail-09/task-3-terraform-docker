# Task 3 - Infrastructure as Code with Terraform

## ✅ Objective
Provision a Docker container (NGINX) using Terraform on an Ubuntu EC2 instance.

## 🛠 Tools Used
- Terraform
- Docker
- AWS EC2 (Ubuntu)

## 📌 Steps Followed
1. Installed Docker and Terraform on Ubuntu EC2.
2. Created a `main.tf` file using Docker provider.
3. Ran `terraform init`, `terraform plan`, and `terraform apply`.
4. Verified the running NGINX container using `docker ps`.
5. Opened port 8080 in the AWS Security Group.
6. Accessed NGINX in the browser via `http://<EC2_PUBLIC_IP>:8080`.
7. Destroyed the infrastructure using `terraform destroy`.

## 📸 Output Screenshot
(Optional: Add a screenshot of browser or `docker ps` output)

## 🙋‍♂️ Author
Mohammed Sohail
