## Distributed Web Crawler & Rag Pipeline

Here is the code for my distributed web crawler rag pipeline.
It features a worker framework I've designed to be easily extendable to cater to **any** task involving worker nodes which communicate via queues.

## Tech Stack:

- Go
- Typescript
- Terraform
- Redis
- AWS

## Features:

- Scraper and RAG clusters which communicate via Redis queues.
- Local chunking + embedding inference
- Autoscaling of clusters
- Custom Scaling metrics based on Redis Queue Size (Lambda used to refresh this metric every 1 min)
- Extracting of useful contact information from web pages

## Infrastructure Visualized

![AWS Infrastructure](aws-infra.png)
