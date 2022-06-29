# AWSLampStack
AWS CloudFormation template for Tutorial - Install a LAMP Web Server on Amazon Linux 2
Step 1: Prepare the LAMP server
Step 2: Test your LAMP server
Step 3: Secure the database serve
Step 4: Install php

Pre-requisites
  To run the following Automation document, you must have permissions to run Automation workflows and create the resources below. The Automation workflow runs in the       context of the current Amazon Identity and Access Management (IAM) user.

Resources Created
This CloudFormation stack helps to create the following resources.
A Virtual Private Cloud (VPC) with a route table, public subnet via an Internet Gateway (IGW), network ACL, and Security Group
A Security Group allowing access to HTTP/80
An IAM Instance Profile Role so the EC2 instance can register with Amazon Systems Manager
An EC2 instance launched using the latest Amazon Linux AMI
