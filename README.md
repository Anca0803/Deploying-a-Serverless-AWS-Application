# Deploying-a-Serverless-AWS-Application
Deploying a Serverless Application Using AWS Lambda, API Gateway, and DynamoDB
#  Quotes API – Serverless Project on AWS

This is a fully serverless web application that delivers random inspirational quotes using AWS services. The project is live and integrated into my personal AWS-hosted website:  
👉https://anca-irimia.com/quotes.html

## What I Built:

- **Amazon DynamoDB** – Stores 20+ inspirational quotes with a partition key (`quote`) and sort key (`author`). Auto-scaling is enabled with encryption at rest.
- **AWS Lambda** – Two Python-based functions:
  - `PutQuotes`: seeds the database with quotes.
  - `GetQuotes`: retrieves a random quote from DynamoDB.
- **Amazon API Gateway** – REST endpoints for `/PutQuotes` and `/GetQuotes`, secured and integrated with Lambda.
- **Amazon S3 Website** – Quotes are fetched and displayed on my front-end page hosted at anca-irimia.com
- **IAM & CloudWatch** – Configured IAM roles with least-privilege access and enabled full request/response logging and X-Ray tracing for monitoring.

##  Key Learnings

- Hands-on experience designing, deploying, and securing a real-world serverless API.
- Practiced integrating backend AWS services with a live frontend website.
- Applied core concepts like IAM roles, API Gateway integrations, CORS, and CloudWatch monitoring.

##  Live Demo

📄 Visit the live page here:  
(https://anca-irimia.com/quotes.html)

## Architecture Diagram:

https://github.com/Anca0803/Serverless-Quote-Generator-on-AWS-/blob/main/QuotesDiagram.png

