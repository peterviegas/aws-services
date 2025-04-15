# 🛠️ aws-services

Infrastructure for a modern **microservices architecture** using **Spring Boot** and **AWS CDK** to deploy a production-ready system on **AWS ECS (Fargate)**, with support for **service discovery**, **asynchronous messaging**, **relational and NoSQL databases**, and **cloud storage**.

## 🚀 Overview

This project showcases a modular and scalable infrastructure using:

- **Spring Boot** for building RESTful APIs.
- **AWS CDK (Java)** for Infrastructure as Code (IaC).
- **Amazon ECS (Fargate)** to run Docker containers serverlessly.
- **Cloud Map** for service discovery across microservices.
- **Amazon SQS** for asynchronous communication via queues.
- **Amazon RDS (PostgreSQL)** for relational database needs.
- **Amazon DynamoDB** for NoSQL data storage.
- **Amazon S3** for file and object storage.

## 🧱 Architecture Highlights

- Microservices run independently in containers managed by ECS.
- Services communicate via **SQS** and **service discovery**.
- Backend infrastructure is fully defined in **AWS CDK** (Java).
- Secure deployment with **VPC**, **ALB**, and IAM roles.
- Scalable and resilient setup ideal for production.

## 🗂️ Project Structure

