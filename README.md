# ☁️ AWS Automated Infrastructure & Configuration Management

An end-to-end Infrastructure as Code (IaC) and Configuration Management pipeline built on AWS using **Terraform** and **Ansible**. This project automates multi-node cloud infrastructure provisioning and zero-touch web application deployment.

---

## 🏗️ Architecture & Deployment Walkthrough

### 1. Terraform Infrastructure Provisioning
Provisioning AWS EC2 instances (`t3.micro`), security groups, and SSH keys in `us-east-1` via Terraform.

<img width="1024" height="665" alt="image" src="https://github.com/user-attachments/assets/c1fe7866-e7f4-4f3f-842c-79ba182e21ca" />


---

### 2. Ansible Configuration Playbook
Configuring the remote server fleet over SSH, installing Nginx, and deploying the web application across multiple nodes with zero manual intervention.

<img width="1024" height="663" alt="image" src="https://github.com/user-attachments/assets/3f55cc72-58dc-4749-8465-df4e21e7aed5" />


---

### 3. Application Verification (`curl`)
Validating the HTTP response directly from the server endpoint.

<img width="851" height="1024" alt="image" src="https://github.com/user-attachments/assets/13127e3f-6021-4e69-a7e1-0bfe242fefd0" />


---

### 4. Service Exposure & Live UI
The browser view of the final deployed application dashboard running live on AWS.

<img width="1024" height="568" alt="image" src="https://github.com/user-attachments/assets/3a914434-9b18-447c-a92e-3925f8088271" />


---

## 🛠️ Tech Stack
* **Cloud Provider:** AWS EC2 (`us-east-1`)
* **Infrastructure as Code:** Terraform
* **Configuration Management:** Ansible
* **Web Server:** Nginx
* **OS:** Ubuntu 22.04 LTS
