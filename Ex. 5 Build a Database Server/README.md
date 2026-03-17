# Lab 5 – Build a Database Server (AWS)

## Author

* **Name**: HARSHIDA K S
* **Register Number**: 212224040108
* **Date of Submission**: 17.03.2026

---

## Objective

The objective of this experiment is to understand how to deploy and configure a database server in AWS. This lab focuses on launching an EC2 instance, installing a database management system (DBMS), configuring basic database settings, creating a sample database, and validating connectivity to the database server.

---

## Prerequisites

* Basic understanding of cloud computing concepts
* AWS account or AWS Academy Lab access
* An existing VPC and EC2 knowledge (from previous labs)
* Basic knowledge of Linux commands and SQL

---

## Tools Used

* AWS Management Console
* Amazon EC2
* Security Groups
* SSH Client (Terminal / PuTTY)
* MySQL / MariaDB / PostgreSQL (any one)

---

## Tasks Performed

### Task 1: Launch EC2 Instance for Database Server

Launch a new EC2 instance using Amazon Linux 2 AMI. Select an appropriate instance type and configure key pair and security group.

---

### Task 2: Configure Security Group for Database Access

Modify the security group to allow:

* SSH (Port 22) for remote access
* Database port (e.g., MySQL – 3306 or PostgreSQL – 5432)

---

### Task 3: Connect to EC2 Instance

Connect to the EC2 instance using SSH from your local machine.

---

### Task 4: Install Database Server

Install a database server software such as MySQL, MariaDB, or PostgreSQL on the EC2 instance using package manager commands.

---

### Task 5: Start and Configure Database Service

Start the database service and configure basic settings such as root password and user privileges.

---

### Task 6: Create a Sample Database

Create a sample database and a table inside it. Insert a few records into the table.

---

### Task 7: Test Database Connectivity

Test the database server by connecting to it locally or remotely and performing basic SQL queries.

---

## Workflow (Student Explanation)

1. Logged into the AWS Management Console and launched a new EC2 instance using Amazon Linux 2 AMI, selected instance type, created key pair, and configured security group.
2. Modified the security group to allow SSH (port 22) and MySQL port (3306) for database access.
3. Connected to the EC2 instance using SSH from my local system using the key pair.
4. Installed the MySQL database server using package manager commands (sudo yum install mysql-server).
5. Started the MySQL service and enabled it, then secured the installation by setting a root password and configuring basic settings.
6. Created a sample database and table using SQL commands and inserted sample records.
7. Tested the database by running queries to retrieve data and verified that the database server was working correctly.
---

## Output Screenshots (Attach 3)

### Screenshot 1: EC2 Instance for Database Server

<img width="1920" height="1080" alt="Screenshot 2026-03-12 103703" src="https://github.com/user-attachments/assets/22114468-173f-4d2b-87fa-1d606004b66c" />


---

### Screenshot 2: Database Service Running

<img width="1920" height="1080" alt="Screenshot 2026-03-12 104208" src="https://github.com/user-attachments/assets/7c7dac85-6819-4f7c-a13b-6d8603f37e93" />


---

### Screenshot 3: Sample Database and Table

<img width="1920" height="1080" alt="Screenshot 2026-03-12 104408" src="https://github.com/user-attachments/assets/76bf9042-bd96-485c-b914-8eb120698562" />


---

## Result

This experiment demonstrated how to build a database server in AWS using an EC2 instance. By installing and configuring a DBMS, creating a sample database, and testing connectivity, the fundamentals of hosting and managing a cloud-based database server were underst
