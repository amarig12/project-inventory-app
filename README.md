# Inventory Management System

A full-featured **Inventory Management System** built using **Angular**, **Flask**, and **MSSQL**, designed with scalability and security in mind. This system supports essential inventory operations across multiple locations, secure multi-organization data segregation, and robust monitoring with Grafana and Prometheus.

> 🚀 **Deployed to Microsoft Azure Web App in Docker container using GitHub Actions for CI/CD**

📁 **Private repository** — This public repo exists to showcase the project to recruiters. Code access available upon request.

---

## 🔧 Tech Stack

- **Frontend**: Angular
- **Backend**: Flask (REST API)
- **Database**: Microsoft SQL Server (MSSQL)
- **Real-time Communication**: WebSockets via Flask-SocketIO
- **Auth**: JWT & bcrypt
- **Monitoring**: Prometheus + Grafana
- **DevOps**: Docker, GitHub Actions (CI/CD), Microsoft Azure
- **Testing**: Pytest (API + DB coverage)

---

## ✅ Features

- 🔐 **User Authentication**: Secure login with JWT and hashed passwords  
- 🏢 **Multi-Tenant Access**: Users see data only for their organization  
- 📦 **Full CRUD Operations**: Manage inventory items with create, read, update, delete  
- 📷 **Photo Uploads**: Upload and view images for inventory items  
- 📄 **Report Generation**: Export inventory data to downloadable PDF files  
- 🧹 **Cleanup Functionality**: Auto-delete temp reports older than a specified time  
- 📜 **Application Logs**: Activity and cleanup logs for audit and monitoring  
- 🧪 **API + DB Testing**: All backend endpoints and database functions tested via Pytest  
- 📊 **Metrics & Monitoring**: Real-time monitoring via integrated Prometheus and Grafana  

---

## 🚀 Deployment Architecture

- Application runs inside a Docker container on Microsoft Azure Web App.
- MSSQL hosted in Microsoft Azure SQL Database.
- Images and file uploads stored in Microsoft Azure Blob Storage
- GitHub Actions for CI/CD pipeline.
- Prometheus and Grafana are configured to monitor system health and usage metrics.

---

## Instructions to Register

When on the website, create an account and enter **1** as the Organization Number.

---

## 🔗 Project Link

[Live link to Project](https://amari-gordon-inventory-app-bqcjehh5gze8g9hm.eastus-01.azurewebsites.net/) 

> 📁 _Note: This is a **public showcase** repository for recruiters and potential employers. The full codebase is stored in a private repository._

---
