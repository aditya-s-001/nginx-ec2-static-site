# 🌐 NGINX Static Website on EC2

This project shows how I hosted a simple HTML + CSS website using **NGINX directly on an Amazon EC2 instance** (Amazon Linux 2).  
No Docker. No frameworks. Just clean and minimal manual setup.

---

## 🔧 Tech Stack

- Amazon EC2 (Amazon Linux 2)
- NGINX (manual setup)
- HTML + CSS
- SSH & Linux CLI

---

## 🚀 How It Works

1. Launched EC2 instance (Amazon Linux 2)
2. Installed NGINX manually via CLI
3. Created or uploaded custom `index.html` & `style.css`
4. Copied site files to `/usr/share/nginx/html/`
5. Opened port 80 (HTTP) in EC2 Security Group
6. Accessed the hosted website using EC2 Public IP

---


## 🔒 EC2 Security Group Settings
Make sure port 80 (HTTP) is open to 0.0.0.0/0 in your EC2 instance’s security group to allow web traffic.


## 📂 Project Structure

```bash
.
├── index.html
└── style.css
