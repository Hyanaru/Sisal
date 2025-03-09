# P.A.S.T.A
Player Authentication Service Tailored on Amazon 

## 📌 Overview
This system is built with a microservices architecture and is hosted on AWS ECS. It ensures security, scalability, and compliance with KYC/AML regulations by leveraging AWS-managed services and third-party integrations.

---

## 🏗 Architecture Overview
The system consists of multiple microservices communicating through API Gateway, designed for high availability and compliance.
The frontend code for PASTA can be done in react + react native in order to reuse as much logic and code as possible and give it a native feeling for the mobile apps.

### 🔑 **Key Components**

### 🛂 **Authentication & KYC**
- **Amazon Cognito** – Manages authentication and MFA (Multi-Factor Authentication).
- **AWS Lambda + Jumio** – Processes KYC (Know Your Customer) checks.
- **Amazon DynamoDB** – Stores risk scoring and compliance audit logs.
- **AWS Fraud Detector** – Ensures AML (Anti-Money Laundering) compliance.

### 📝 **Content Management System (CMS)**
- **Contentful (Headless CMS)** – Manages promotional content.
- **GraphQL/REST API** – Enables content retrieval.
- **Redis** – Caching layer for improved performance.
- **Kafka + Elasticsearch** – Enables real-time personalized content delivery.

### 🔗 **Integrations**
- **Loyalty Program** – Connected via an OAuth 2.0-secured REST API.
- **Responsible Gaming Service** – Integrated through API Gateway and monitored with AWS CloudWatch.

---

## 📌 Features
- ✅ Secure authentication & KYC processing
- ✅ Scalable content management with caching & indexing
- ✅ Seamless third-party integrations
- ✅ AWS-native services for compliance & security

---

## 📞 Contact
For any inquiries, reach out to **[Your Name]** at [your-email@example.com].
