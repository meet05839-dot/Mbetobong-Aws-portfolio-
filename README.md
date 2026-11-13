# Mbetobong-Aws-portfolio-
My practical AWS cloud computing project and learning journey 
Project 1: Static Website Hosting Using Amazon S3

Project Status

Completed.

Project Overview

Successfully deployed and hosted a static website using Amazon Simple Storage Service (Amazon S3). This project demonstrates the fundamental process of publishing an HTML website through an S3 bucket configured for static website hosting.

AWS Services Used

Amazon S3

Tasks Completed

1. Created and configured an Amazon S3 bucket.
2. Uploaded an HTML website file to the bucket.
3. Enabled static website hosting.
4. Configured bucket permissions to allow website access.
5. Accessed and verified the live website through the S3 website endpoint.

Skills Demonstrated

~ Amazon S3 bucket creation and management.
~ Static website deployment and hosting.
~ Basic HTML implementation.
~ Bucket policies and access permissions.
~ Fundamental cloud hosting concepts.

Learning Outcome

Developed practical experience deploying and hosting a static website with Amazon S3. This project provided hands-on exposure to object storage, website configuration, access control, and basic AWS hosting workflows.

Project Evidence

~ Screenshot of the configured S3 bucket.
~ Screenshot of the uploaded HTML website file.
~ Screenshot of the static website hosting configuration.
~ Screenshot of the live website.

Live Website

[http://mbetobong-cloud-portfolio-2026.s3-website-us-east-1.amazonaws.com]

Project 2: Highly Available Web Application on AWS

Project Status

Completed.

Project Overview

Designed and deployed a highly available web application using Amazon EC2, Application Load Balancer and Auto Scaling.

AWS Services Used

* Amazon EC2
* Application Load Balancer
* EC2 Auto Scaling
* Amazon VPC
* Security Groups

Architecture

Internet → Application Load Balancer → Target Group → EC2 Instances

Tasks Completed

1. Created security groups for the Load Balancer and EC2 instances.
2. Created a target group.
3. Deployed an internet-facing Application Load Balancer.
4. Created an EC2 launch template.
5. Configured Apache web server using user data.
6. Created an Auto Scaling group.
7. Launched two EC2 instances across Availability Zones.
8. Verified target health.
9. Tested website accessibility through the Load Balancer DNS name.

Skills Demonstrated

* EC2 instance management.
* Application Load Balancing.
* Auto Scaling configuration.
* Security group management.
* Basic web server deployment.
* High availability concepts.
* Cloud infrastructure monitoring.

Learning Outcome

Gained practical experience designing and deploying a highly available web application using AWS infrastructure services.

Project Evidence

* Security group screenshots.
* Target group screenshot.
* Load Balancer screenshot.
* Auto Scaling group screenshot.
* EC2 instance screenshots.
* Screenshot of the working website.
Live Application
[http://mbet-web-alb-420611425.us-east-1.elb.amazonaws.com]

Project 3: CloudWatch Monitoring System — Completed
I have successfully configured:

Amazon EC2 monitoring server 
Amazon CloudWatch

Amazon cloudwatch monitors CPU utilisation

CloudWatch Alarm detects CPU above 70%

Amazon SNS sends notifications 

Email notification receives alerts 

project evidence:

screenshot of ec2, cloudwatch alarms and SNS (simple notification service)

Project 4: Secure Cloud Network Using AWS VPC

Project Status

Completed

Project Overview

Designed and configured a secure AWS Virtual Private Cloud (VPC) with separate public and private subnets, an Internet Gateway, route tables, and security groups.

AWS Services Used

* Amazon VPC
* Public and Private Subnets
* Internet Gateway
* Route Tables
* Security Groups

Implementation

1. Created a VPC with CIDR block 10.0.0.0/16.
2. Created a public subnet using 10.0.1.0/24.
3. Created a private subnet using 10.0.2.0/24.
4. Created and attached an Internet Gateway.
5. Configured a public route table with internet access.
6. Configured a private route table with local routing only.
7. Created a security group allowing HTTP traffic and restricted SSH access.

Skills Demonstrated

* AWS network architecture
* VPC configuration
* Subnet design
* Route table configuration
* Internet Gateway configuration
* Network security fundamentals

Learning Outcome

Learned how to design a basic AWS network that separates public-facing resources from private resources and controls network traffic using routing and security groups.

Evidence

Screenshots of the VPC, subnets, Internet Gateway, route tables, and security group.