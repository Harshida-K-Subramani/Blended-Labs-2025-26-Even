# Lab 3 – Introduction to Amazon Elastic Compute Cloud (EC2)

## Author

* **Name**: HARSHIDA K S
* **Register Number**: 212224040108
* **Date of Submission**: 17.03.2026

---

## Objective

The objective of this experiment is to understand the fundamentals of Amazon Elastic Compute Cloud (EC2). This lab focuses on launching and managing a virtual server, understanding instance types and AMIs, connecting to an EC2 instance, monitoring its status, and performing basic instance operations such as start, stop, and terminate.

---

## Prerequisites

* Basic understanding of cloud computing concepts
* AWS account or AWS Academy Lab access
* Web browser with internet connectivity
* Basic knowledge of Linux commands (optional)

---

## Tools Used

* AWS Management Console
* Amazon EC2
* Key Pair
* Security Group
* SSH Client (PuTTY / Terminal)

---

## Tasks Performed

### Task 1: Explore Amazon EC2 Dashboard

Explore the EC2 service dashboard in the AWS Management Console. Observe the different sections such as Instances, AMIs, Instance Types, Key Pairs, Security Groups, and Elastic IPs.

---

### Task 2: Launch an EC2 Instance

Launch a new EC2 instance using Amazon Linux 2 AMI. Select an appropriate instance type (t2.micro) under the free tier. Configure basic settings such as instance name, key pair, and security group.

---

### Task 3: Configure Security Group

Configure a security group to allow inbound access:

* SSH (Port 22) from your IP address
* HTTP (Port 80) from anywhere (0.0.0.0/0)

This security group acts as a firewall for the instance.

---

### Task 4: Connect to EC2 Instance

Connect to the running EC2 instance using SSH. Use the downloaded key pair and connect via terminal or PuTTY.

For Amazon Linux:

```
ssh -i "keyname.pem" ec2-user@<Public-IP>
```

---

### Task 5: Perform Basic Instance Operations

Perform the following operations from the EC2 console:

* Stop the instance
* Start the instance
* Reboot the instance

Observe the state changes of the instance.

---

### Task 6: Monitor EC2 Instance

Monitor the EC2 instance using the Monitoring tab. Observe metrics such as CPU utilization, network in/out, and instance status checks.

---

### Task 7: Terminate EC2 Instance

Terminate the EC2 instance after completing the experiment to avoid unnecessary AWS charges.

---

## Workflow (Student Explanation)

1. Logged into the AWS Management Console and navigated to the EC2 dashboard to explore available services like instances, AMIs, and security groups.
2. Launched a new EC2 instance using Amazon Linux 2 AMI, selected t2.micro instance type, created a key pair, and configured basic settings.
3. Configured the security group to allow SSH (port 22) from my IP and HTTP (port 80) from anywhere.
4. Connected to the EC2 instance using SSH from the terminal using the key pair file and verified successful login.
5. Performed instance operations such as stop, start, and reboot, and observed the status changes in the console.
6. Monitored the instance using the Monitoring tab and checked metrics like CPU utilization and network activity.
7. Finally, terminated the EC2 instance to avoid unnecessary charges.
---

## Output Screenshots (Attach 3)

### Screenshot 1: EC2 Dashboard / Instance List

<img width="1920" height="1080" alt="Screenshot 2026-02-26 105238" src="https://github.com/user-attachments/assets/bb5e200c-2285-4959-8ce2-c852bbf6dad0" />


---

### Screenshot 2: SSH Connection to Instance

![i-022d7038315850988](https://github.com/user-attachments/assets/46683a98-8249-4c4c-b196-6a52b2294690)


---

### Screenshot 3: Instance Monitoring / Status

<img width="1920" height="1080" alt="Screenshot 2026-02-26 115442" src="https://github.com/user-attachments/assets/620bd7c9-ed11-4348-ac91-4ebf031816fe" />

---

## Result 

This experiment provided hands-on experience with Amazon EC2 by demonstrating how to launch, connect, manage, and monitor a virtual server in AWS. It helped in understanding the concept of Infrastructure as a Service (IaaS) and how compute resources can be provisioned and controlled on demand in the cloud.
