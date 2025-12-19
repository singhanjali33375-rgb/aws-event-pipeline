# AWS Event Pipeline
# AWS Event-Driven Pipeline using Terraform

This project demonstrates an event-driven architecture on AWS
provisioned using Terraform.

## Architecture
- S3 bucket triggers AWS Lambda on object upload
- Lambda processes the event
- Logs are stored in Amazon CloudWatch
- Infrastructure is fully automated using Terraform
- CI/CD pipeline implemented using GitHub Actions

## Services Used
- AWS S3
- AWS Lambda
- AWS CloudWatch
- Terraform
- GitHub Actions

## Key Features
- Infrastructure as Code (IaC)
- Event-driven serverless architecture
- Automated CI/CD
- CloudWatch logging and monitoring

## Outcome
Successfully triggered Lambda functions via S3 events and
validated execution using CloudWatch logs.
