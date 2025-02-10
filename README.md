## Distributed Web Crawler & RAG Pipeline

Here is the code for my distributed web crawler rag pipeline.
It features a worker framework I've designed to be easily extendable to cater to **any** task involving worker nodes which communicate via queues.

## Tech Stack

- Go
- Typescript
- Terraform
- Redis
- AWS

## Features

- Distributed scraper and RAG clusters communicate via Redis queues.
- Localized text processing, chunking and embedding inference (secure).
- Autoscaling of clusters using custom Redis queue size metrics (refreshed by Lambda every minute).
- Email addresses, phone numbers and links extracted from web pages.
- Very high test coverage

## AWS Services

- **VPC & Networking**: VPC, Internet/NAT Gateways, Route Tables, and Security Groups
- **Compute & Containers**: ECS (Fargate) and ECR
- **Message Queue**: ElastiCache (Redis)
- **Serverless & Automation**: Lambda, CloudWatch, App Auto Scaling
- **Security & Identity**: IAM and Secrets Manager

## Infrastructure Visualized

![AWS Infrastructure](aws-infra.png)
