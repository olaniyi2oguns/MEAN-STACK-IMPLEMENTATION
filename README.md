# MEAN-STACK-IMPLEMENTATION
MEAN Stack Deployment on Ubuntu 22.04 (AWS) This documentation explains how to deploy a MEAN (MongoDB, Express, AngularJS, Node.js) stack application on an Ubuntu 22.04 AWS EC2 instance. Each step includes the commands to execute and the rationale behind it.

## Table of Contents

1. ### Prerequisites
2. ### Step 1: Update Ubuntu and Install Node.js 20
3. ### Step 2: Install MongoDB Community Edition 6.0
4. ### Step 3: Set Up the MEAN Application
5. ### Create the Project Directory
6. ### Server Setup with Node.js and Express
7. ### Configure Routes and Database Models
8. ### Step 4: Build the Front-End with AngularJS
9. ### Step 5: Running and Testing the Application
10. ### Troubleshooting

## Prerequisites

- AWS Account & EC2 Instance:
You need an AWS account and an EC2 instance running Ubuntu 22.04 LTS.
Reason: Ubuntu 22.04 is a supported LTS release that provides stability and security updates.

- Security Group Configuration:
Ensure that the EC2 instance’s security group allows inbound traffic on port 3300 (or your chosen port) so that your application is accessible externally.

- SSH/Terminal Access:
Use SSH or AWS CloudShell to connect to your instance.

## Step 1: Update Ubuntu and Install Node.js 20
1.1 Update and Upgrade the System

`sudo apt update`

`sudo apt upgrade -y`

