# 🛠️ aws-services

Infrastructure for a modern **microservices architecture** using **Spring Boot** and **AWS CDK** to deploy a production-ready system on **AWS ECS (Fargate)**. Includes support for **service discovery**, **asynchronous messaging**, **relational and NoSQL databases**, and **cloud storage**.

---

## 🚀 Overview

This project showcases a modular and scalable infrastructure using:

- ✅ **Spring Boot** for building RESTful APIs  
- ✅ **AWS CDK (Java)** for Infrastructure as Code (IaC)  
- ✅ **Amazon ECS (Fargate)** to run Docker containers without managing servers  
- ✅ **AWS Cloud Map** for service discovery between microservices  
- ✅ **Amazon SQS** for asynchronous communication  
- ✅ **Amazon RDS (PostgreSQL)** for relational data  
- ✅ **Amazon DynamoDB** for NoSQL data  
- ✅ **Amazon S3** for object and file storage  

---

## 🧱 Architecture Highlights

- Microservices run independently as Docker containers on **ECS Fargate**
- Services discover each other through **Cloud Map**
- Inter-service communication is handled asynchronously via **SQS**
- Infrastructure is fully defined in **AWS CDK (Java)**
- Includes security best practices with **VPC**, **IAM**, and **ALB**
- Built for **scalability, resilience, and production-readiness**

---

## 🗂️ Project Structure
```
aws-services/
├── cdk/           # AWS CDK infrastructure code (Java)
├── service-a/     # Spring Boot Microservice A
├── service-b/     # Spring Boot Microservice B
├── common/        # Shared modules (DTOs, configurations, etc.)
└── README.md
```

---

## 📦 Requirements

- ✅ Java 17+
- ✅ Docker
- ✅ AWS CLI (configured with credentials)
- ✅ AWS CDK CLI  
  Install with: `npm install -g aws-cdk`
- ✅ Gradle

---

## 🌍 AWS Resources Used

| Resource        | Purpose                              |
|----------------|--------------------------------------|
| **ECS Fargate** | Container orchestration              |
| **RDS**         | Relational database (PostgreSQL)     |
| **DynamoDB**    | NoSQL database                       |
| **SQS**         | Asynchronous messaging               |
| **S3**          | File and object storage              |
| **Cloud Map**   | Service discovery between services   |

---

## 🤝 Contributing

Contributions are welcome!  
Feel free to fork the repository, open issues or submit pull requests.

---

## 📄 License

This project is licensed under the **MIT License**.

---

Built with ❤️ by [Peter Viegas](https://github.com/peterviegas)

