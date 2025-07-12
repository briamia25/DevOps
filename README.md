💇‍♀️ Hair Salon Appointment Scheduler – AWS Cloud Capstone
This project is a full-stack, containerized web application developed for AnyCompany Web Consultancy on behalf of a hair salon client. The application allows salon customers to book appointments and select services online.

Originally drafted by a senior developer, the project was handed off for completion, testing, and deployment into a production-like staging environment on AWS. As a cloud developer, I took ownership of building, testing, containerizing, and deploying the application using AWS-native services and CI/CD best practices.

🛠️ Key Features & Technologies
Backend: Python, Django

Frontend: HTML/CSS (Django templates)

Databases: Amazon RDS (SQL) & DynamoDB (NoSQL)

Containerization: Docker, Amazon Elastic Container Registry (ECR)

Orchestration: Amazon Elastic Kubernetes Service (EKS)

CI/CD: AWS CodePipeline, CodeBuild

Infrastructure: Application Load Balancer (ALB), IAM, VPC

📦 What I Built & Deployed
Refactored UI and backend logic for improved functionality

Wrote and ran new unit tests to ensure application stability

Created an automated CI/CD pipeline using AWS CodePipeline and CodeBuild

Built and pushed Docker container images to Amazon ECR

Deployed the application to a live Amazon EKS Kubernetes cluster

Integrated an Application Load Balancer for high availability

Implemented rollback procedures and automated redeployments

Ensured secure access via IAM roles, security groups, and least-privilege principles

🔁 Deployment Flow (High-Level)
Developer pushes code → triggers AWS CodePipeline

CodeBuild runs tests & builds Docker image

Image is stored in Amazon ECR

Pipeline deploys app to Amazon EKS

Application uses ALB for routing + RDS & DynamoDB for data storage

🚀 Outcome
This capstone project challenged me to apply everything I’ve learned about cloud-native development, DevOps workflows, and scalable infrastructure. It sharpened my skills in automation, debugging, and deployment in a real-world setting — making this one of my most comprehensive cloud engineering projects to date.
