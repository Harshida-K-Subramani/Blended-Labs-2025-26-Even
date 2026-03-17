# Lab 6 – Scale and Load Balance Your Architecture

## Title

Scale and Load Balance Your Architecture
Author : your name   Reg no : yours   Date :

---

## Objective

The objective of this lab is to understand how to design a scalable and highly available architecture on AWS using Auto Scaling and Elastic Load Balancing. This experiment focuses on distributing incoming traffic across multiple EC2 instances, automatically scaling resources based on demand, and validating fault tolerance.

---

## Prerequisites

* Basic knowledge of Amazon EC2 and VPC
* Completion of previous labs (IAM, EC2, EBS, Database Server)
* AWS Academy Lab access
* Stable internet connection

---

## Tools Used

* AWS Management Console
* Amazon EC2
* Elastic Load Balancer (ELB / ALB)
* Auto Scaling Groups (ASG)
* Amazon CloudWatch

---

## Tasks Performed

### Task 1: Review Existing Architecture

Students review the existing EC2-based application architecture created in previous experiments.

### Task 2: Create a Launch Template

Students create a launch template that defines the EC2 instance configuration including AMI, instance type, security group, and user data.

### Task 3: Create an Auto Scaling Group

Students create an Auto Scaling Group using the launch template and configure minimum, maximum, and desired instance capacity.

### Task 4: Configure an Application Load Balancer

Students create an Application Load Balancer and configure target groups for routing traffic to EC2 instances.

### Task 5: Register Auto Scaling Group with Load Balancer

Students attach the Auto Scaling Group to the target group of the load balancer.

### Task 6: Configure Scaling Policies

Students configure scaling policies based on CPU utilization using Amazon CloudWatch alarms.

### Task 7: Test Load Balancing and Scaling

Students test the setup by generating traffic and observing automatic scaling and load distribution.

---

## Workflow (To be filled by Student)

1. Logged into the AWS Management Console and reviewed the existing EC2 architecture created in previous labs.
2. Created a Launch Template by selecting an AMI, instance type, key pair, security group, and added user data for application setup.
3. Configured an Auto Scaling Group (ASG) using the launch template and set minimum, desired, and maximum number of instances.
4. Created an Application Load Balancer (ALB) and configured listeners and a target group.
5. Attached the Auto Scaling Group to the target group so that traffic is distributed across instances.
6. Set up scaling policies using CloudWatch alarms based on CPU utilization (scale out and scale in conditions).
7. Generated traffic to test the system and observed automatic scaling and load balancing across EC2 instances.
8. Verified fault tolerance by stopping an instance and confirming that the ASG launched a new instance automatically.

## Output Screenshots 

<img width="1920" height="1080" alt="cc6op1" src="https://github.com/user-attachments/assets/c77bedf8-f361-47cb-ba85-14adff91cb23" />

<img width="1920" height="1080" alt="cc6op2" src="https://github.com/user-attachments/assets/d661dbe9-3604-4b68-b71d-2b22498d1cb5" />

<img width="1920" height="1080" alt="cc6op3" src="https://github.com/user-attachments/assets/d688f540-d610-4921-b944-ac1c15490648" />

<img width="1920" height="1080" alt="cc6op4" src="https://github.com/user-attachments/assets/9e8bc65c-b3e0-472b-981a-f7eb5c2a6296" />

<img width="1920" height="1080" alt="cc6op5" src="https://github.com/user-attachments/assets/6b76ed8d-580b-49c5-aea6-8c6c6e4700e4" />

<img width="1920" height="1080" alt="cc6op6" src="https://github.com/user-attachments/assets/4797cfad-d667-49a4-919f-99dafc009773" />



## Result

This experiment demonstrated how to build a scalable and fault-tolerant cloud architecture using Auto Scaling Groups and Elastic Load Balancing. The system automatically adjusted resources based on workload and ensured continuous service availability by distributing traffic across multiple instances.
