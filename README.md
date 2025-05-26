# 🛠️ Microservices Web Application on AWS EKS

This project demonstrates the deployment of a containerized microservices application on AWS using EKS, ECR, and CI/CD automation. The architecture is built for scalability, modularity, and real-world cloud deployment practices.

---

## 🚀 Project Overview

A cloud-native web application consisting of multiple microservices (e.g., User, Product, Order), each running in its own container, and deployed to AWS EKS. Infrastructure and deployment automation is handled using GitHub Actions and Kubernetes.

---

## 🔧 Tools & Technologies

- **Cloud**: AWS (EKS, ECR, IAM, VPC)
- **Containerization**: Docker
- **Orchestration**: Kubernetes (via AWS EKS)
- **CI/CD**: GitHub Actions (planned)
- **Networking**: ALB Ingress Controller
- **Infrastructure**: Kubernetes YAML Manifests (Deployments, Services, ConfigMaps, Secrets)

---
- Each service:
  - Has its own Docker container image
  - Connects to a separate database
  - Uses separate Deployment and Service manifests
- Internal communication via Kubernetes services
- Container images stored in AWS ECR
- Future GitHub Actions workflow will automate CI/CD
  
---

📦 Planned Enhancements
✅ Add GitHub Actions for CI/CD

---
Contributors
Aya AbdElaty
Mariam Yasser
Romisaa Sameh
Ereny Abdelmesieh
