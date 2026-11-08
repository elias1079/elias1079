<h1 align="left">👋 Hi, I'm Elias Mouawad</h1>

**Software Engineer · Backend & DevOps** — B.Sc. Computer Science, Holon Institute of Technology (HIT) 🇮🇱

I like building systems that are reliable, observable and easy to deploy: event-driven services on AWS, Java/Spring Boot microservices, and the automation that ships them.
I care about understanding *why* a system works, not just getting it to run.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Elias%20Mouawad-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/elias-mouawad-69b350273)

---

## 🔍 Current Focus

- ☁️ Building **serverless automation on AWS** with Infrastructure-as-Code (AWS SAM)
- 📚 Studying for **AWS Solutions Architect – Associate (SAA-C03)**
- 🧩 Sharpening **Spring Boot & microservices** design
- 🎯 Looking for **junior Backend / DevOps / Cloud** roles

---

## 💻 Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)
![C#](https://img.shields.io/badge/C%23-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=for-the-badge&logo=powershell&logoColor=white)
**Backend**

![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Apache%20Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)
![REST API](https://img.shields.io/badge/REST%20API-005571?style=for-the-badge)
![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)

**Cloud & DevOps**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![AWS Lambda](https://img.shields.io/badge/Lambda-FF9900?style=for-the-badge&logo=awslambda&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

**Databases**

![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![DynamoDB](https://img.shields.io/badge/DynamoDB-4053D6?style=for-the-badge&logo=amazondynamodb&logoColor=white)

**AWS services I've worked with:** Lambda · API Gateway · DynamoDB · EventBridge · SNS · SQS · S3 · Amplify · EC2 · RDS · IAM

---

## 🚀 Active Projects

### ☁️ Serverless RDS Cluster Automation
**Status:** In progress · [Repository](https://github.com/elias1079/serverless-rds-automation)

- Event-driven automation for provisioning and managing RDS clusters on AWS
- Requests flow through **SNS → SQS** into Lambda workers
- Entire stack defined as code with **AWS SAM**

**Tech:** Python, AWS SAM, Lambda, SNS, SQS, RDS, IAM

---

## ✅ Completed Projects

### ⚽ Football Match Video Analysis (Computer Vision)
**Status:** Completed (HIT deep learning project)

- Fine-tuned **YOLO** on a custom football dataset (players, goalkeepers, referees, ball)
- **ByteTrack** multi-object tracking with persistent player IDs
- Team classification by K-Means clustering on jersey colours
- Camera-motion compensation (optical flow) + perspective transform to real-world metres
- Per-player **speed & distance**, ball possession %, and an annotated output video with a top-down minimap

**Tech:** Python, Ultralytics YOLO, OpenCV, supervision, scikit-learn, pandas, NumPy

### 🔔 Alert Hub — Rules-Based Notification Platform
**Status:** Completed · [Repository](https://github.com/IbrahemHurani/AlertHub) (team project)

- **10 Java/Spring Boot microservices** in a monorepo that notify project managers about changes in Jira, ClickUp and GitHub via email/SMS
- Async messaging with **Kafka**, sync calls with **OpenFeign**; MySQL + MongoDB
- **My part:** the **Action service** (AND/OR rule conditions, scheduling) and the **Job Scheduler** microservice
- Deployed with **Docker → Docker Hub → Kubernetes (Minikube)** with Services and Ingress

**Tech:** Java, Spring Boot, Kafka, OpenFeign, MySQL, MongoDB, Docker, Kubernetes, Swagger

### 📦 Serverless Order Management System
**Status:** Completed (AWS Serverless course final project, team of 3)

- REST API for orders on **API Gateway + Lambda (Python)** with **DynamoDB** (GSI for date-sorted queries)
- Asynchronous delete publishes an event to a custom **EventBridge** bus, fanning out to an SNS email notifier and an S3 backup writer
- **SQS Dead Letter Queue** for failed async events; on-demand PDF reports via S3 presigned URLs
- Web client hosted on **AWS Amplify**

**Tech:** Python, API Gateway, Lambda, DynamoDB, EventBridge, SNS, SQS, S3, Amplify

---

## 🌍 Languages

Arabic (native) · Hebrew (native) · English (fluent)

---

<p align="left"><i>Always learning — currently: AWS SAA</i></p>
