This repository contains real-world DevOps projects designed for mid-level engineers aiming to switch roles. Each week focuses on a key set of tools and ends with a practical project.

---

## 📅 Weekly Projects Overview

### ✅ Week 1: Bash + Git + Python/Go
**Project:** Auto-deploy Nginx with Git-pushed configs using Bash  
- Bash script pulls updated Nginx config from GitHub repo
- Reloads Nginx and validates configuration
- Logs actions with timestamp

---

### ✅ Week 2: Docker + Web + Networking
**Project:** Dockerize Python/Go app + expose via Nginx  
- Dockerfile + Docker Compose for multi-service setup
- Nginx as reverse proxy with SSL
- Test response and log access

---

### ✅ Week 3: Cloud Infra + Ansible + Terraform
**Project:** Provision EC2 using Terraform and configure Nginx with Ansible  
- Write Terraform scripts to spin EC2 + Security Group
- Ansible playbook installs Nginx and applies config
- Test provisioning from scratch

---

### ✅ Week 4: CI/CD + Secrets + Lambda
**Project:** CI/CD with secrets for deploying Python app to AWS Lambda  
- GitHub Actions pipeline
- Secure secrets using HashiCorp Vault or Ansible Vault
- Deploy to Lambda with API Gateway

---

### ✅ Week 5: Monitoring + GitOps
**Project:** App with full observability + GitOps using Argo CD  
- Prometheus & Grafana for metrics
- Loki or ELK stack for logs
- Argo CD auto-deploys to K8s cluster

---

### ✅ Week 6: Kubernetes + Service Mesh
**Project:** Microservice with Helm + Istio + Secrets  
- Build Helm chart for app
- Istio routing & observability
- K8s Secrets injected securely

---

### ✅ Week 7: Infra Security + Final Capstone
**Project:** Full stack: CI/CD → Vault → Docker → K8s → GitOps → Monitoring  
- End-to-end app deployment with all tools integrated
- Monitor, manage secrets, and route traffic securely

---

Each folder contains:
- `README.md` with instructions
- Code examples
- Terraform/Ansible/Docker/K8s configs

Feel free to fork and showcase on your resume or portfolio!
