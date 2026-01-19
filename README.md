## 📘 Devops Capstone Project 

![Build Status](https://github.com/ayanshaikh0525/devops-capstone-project/actions/workflows/ci-build.yaml/badge.svg)

The **Account Microservice** is designed to manage customer accounts for an e-commerce platform as part of a larger microservices architecture. This service exposes a RESTful API that allows other microservices—such as order processing, payment, and inventory—to reliably interact with customer data.

### 🎯 Scope of the Microservice
This service is responsible for performing the following operations on customer accounts:

- **Create** a new customer account *(already implemented)*
- **Read** an existing customer account
- **Update** an existing customer account
- **Delete** an existing customer account
- **List** all customer accounts

The project initially provides a Python **Flask-based REST API** with an existing *Create Customer* endpoint. Additional CRUD endpoints will be developed to complete the microservice functionality.

### 🧱 Architecture Foundations
- **Backend Framework:** Python Flask  
- **Database Model:** Already implemented  
- **API Style:** REST  
- **Intended Deployment:** Online lab environment / containerized microservice architecture  

### 🛠️ Development Plan
To complete the service, the next steps include:

1. **Set up the online lab development environment**
   - Install required dependencies
   - Configure database connection
   - Run the existing codebase locally

2. **Implement remaining REST API endpoints**
   - `GET /accounts/<id>` – Read customer details  
   - `PUT /accounts/<id>` – Update customer details  
   - `DELETE /accounts/<id>` – Delete a customer account  
   - `GET /accounts` – List all customers  

3. **Add unit tests and integration tests**
   - Test CRUD operations  
   - Validate error handling  

4. **Update API documentation**
   - Swagger/OpenAPI recommended  

5. **Prepare deployment configuration**
   - Dockerfile  
   - Environment variables  
   - CI/CD considerations  

---

