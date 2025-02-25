# AWS Lift & Shift Project

## Overview
This project demonstrates how to lift and shift a multi-tier application (VProfile) to AWS using EC2 instances, Elastic Load Balancer, Auto Scaling, Route 53, and other AWS services.

## Architecture
![AWS Architecture](screenshots/aws-architecture.png)

## Steps to Set Up
1. **Provision EC2 Instances**:
   - Use the provided scripts to set up Tomcat, MySQL, RabbitMQ, and Memcached.
2. **Configure Elastic Load Balancer**:
   - Create an Application Load Balancer to route traffic to Tomcat instances.
3. **Set Up Route 53**:
   - Configure DNS for your application.
4. **Upload Artifacts to S3**:
   - Store your application artifacts in an S3 bucket.
5. **Deploy the Application**:
   - Download the artifacts from S3 and deploy them to the Tomcat instances.

## Project Structure
aws-lift-and-shift/
├── scripts/
├── screenshots/
├── README.md
