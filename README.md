# 🕷️ Distributed Web Crawler & RAG Pipeline

[![Go Version](https://img.shields.io/badge/Go-1.20+-00ADD8?style=flat&logo=go)](https://go.dev/)
[![TypeScript](https://img.shields.io/badge/TypeScript-4.0+-3178C6?style=flat&logo=typescript)](https://www.typescriptlang.org/)
[![AWS](https://img.shields.io/badge/AWS-Cloud-FF9900?style=flat&logo=amazon-aws)](https://aws.amazon.com/)
[![Redis](https://img.shields.io/badge/Redis-Queue-DC382D?style=flat&logo=redis)](https://redis.io/)
[![Terraform](https://img.shields.io/badge/Terraform-Managed-7B42BC?style=flat&logo=terraform)](https://www.terraform.io/)
[![Docker](https://img.shields.io/badge/Docker-Container-2496ED?style=flat&logo=docker)](https://www.docker.com/)

Here is the code for my distributed web crawler rag pipeline.
It features a worker framework I've designed to be easily extendable to cater to **any** task involving worker
nodes which communicate via queues.

## 🛠️ Tech Stack

- 🔵 Go
- 🔷 Typescript
- 🟣 Terraform
- 🔴 Redis
- 🟡 AWS
- 🐳 Docker

## ⭐ Features

- 🔄 Distributed scraper and RAG clusters communicate via Redis queues
- 🔒 Localized text processing, chunking and embedding inference (secure)
- ⚡ Autoscaling of clusters using custom Redis queue size metrics (refreshed by Lambda every minute)
- 📝 Email addresses, phone numbers and links extracted from web pages
- ✅ Very high test coverage

## 🏗️ AWS Services

| Category                       | Services                                                      |
| ------------------------------ | ------------------------------------------------------------- |
| **🌐 VPC & Networking**        | VPC, Internet/NAT Gateways, Route Tables, and Security Groups |
| **🐳 Compute & Containers**    | ECS (Fargate) and ECR                                         |
| **📨 Message Queue**           | ElastiCache (Redis)                                           |
| **⚡ Serverless & Automation** | Lambda, CloudWatch, App Auto Scaling                          |
| **🔐 Security & Identity**     | IAM and Secrets Manager                                       |

## 🗺️ Infrastructure Visualized

![AWS Infrastructure](aws-infra.png)
