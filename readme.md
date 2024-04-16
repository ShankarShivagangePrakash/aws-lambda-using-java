## AWS Lambda Learning - Java Lambdas & Serverless Architecture

This repository documents my journey learning AWS Lambda functions in Java. Here, you'll find code examples for various functionalities and integrations with other AWS services.

**Learning Objectives:**

* Develop and deploy Java Lambda functions
* Integrate Lambda functions with DynamoDB, S3, SQS, and SNS
* Automate Lambda deployments using AWS SAM (Serverless Application Model)

**Project Structure:**

This repository contains three folders, each demonstrating a specific Lambda functionality:

* **hello-world:** A simple "Hello World" Lambda function showcasing basic Java Lambda development.
* **ordersapi:** An Orders API implemented using a Lambda function. This function connects to a DynamoDB table and can be accessed via an API Gateway endpoint deployed with the application.  
* **patientcheckout:** A patient checkout Lambda function demonstrating interactions with various AWS services:
    * Uploads files to an S3 bucket
    * Sends messages to an SQS queue
    * Publishes notifications via SNS

**Technology Stack:**

* Java 
* AWS Lambda
* AWS DynamoDB (ordersapi)
* AWS S3 (patientcheckout)
* AWS SQS (patientcheckout)
* AWS SNS (patientcheckout)
* AWS API Gateway (ordersapi)
* AWS Serverless Application Model (AWS SAM) for deployment automation

**Deployment:**

Instructions for deploying these Lambda functions are included within each respective folder. All projects leverage AWS SAM for automating the deployment process using CloudFormation templates.

**Note:**

This repository serves as a personal learning project and may not adhere to all production-ready best practices.

I hope this code proves useful for anyone else exploring AWS Lambda and serverless architectures!
