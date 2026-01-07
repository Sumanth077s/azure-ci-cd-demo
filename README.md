# Azure CI/CD Pipeline using GitHub Actions

This project demonstrates a secure and automated CI/CD pipeline for deploying a static web application to Azure App Service using GitHub Actions and Azure Active Directory OIDC authentication.

---

## 🚀 Project Overview
The application is deployed automatically to Azure whenever code is pushed to the main branch.  
Authentication is handled using OpenID Connect (OIDC), eliminating the need for basic authentication or stored credentials.

---

## 🧰 Technologies Used
- Azure App Service
- GitHub Actions
- Azure Active Directory (Entra ID)
- Azure RBAC
- HTML

---

## 🔄 CI/CD Workflow
1. Code is pushed to the GitHub repository.
2. GitHub Actions workflow is triggered automatically.
3. Workflow authenticates to Azure using OIDC.
4. Application is deployed to Azure App Service.

---

## 🔐 Security Highlights
- No passwords or publish profiles used
- OIDC-based authentication with federated credentials
- Role-based access control (RBAC) enforced

---

## 📂 Repository Structure
.
├── index.html
└── .github
└── workflows
└── deploy.yml


---

## ✅ Key Learnings
- Implemented enterprise-grade CI/CD on Azure
- Configured GitHub Actions with OIDC authentication
- Applied least-privilege access using Azure RBAC

---

## 📌 Author
Sumanth U
