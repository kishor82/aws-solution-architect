
### IAM (Identity and Access Management):

**Q1:**
A company needs to grant temporary access to a developer from another organization. What AWS service should be used to achieve this?

A. IAM roles\
B. IAM users\
C. Security groups\
D. Resource-based policies

**Answer:** A. IAM roles

---

**Q2:**
Which statement is true regarding IAM policies?

A. IAM policies are written in YAML format.\
B. IAM policies have a deny effect by default.\
C. IAM policies define permissions for groups only.\
D. IAM policies must include both "Allow" and "Deny" statements.

**Answer:** B. IAM policies have a deny effect by default.

---

### EC2 (Elastic Compute Cloud):

**Q3:**
An organization needs to ensure the highest level of performance and minimal downtime for its application. What EC2 instance type would you recommend?

A. On-Demand Instances\
B. Reserved Instances\
C. Spot Instances\
D. Dedicated Hosts

**Answer:** D. Dedicated Hosts

---

**Q4:**
What is the purpose of an Amazon Machine Image (AMI) in EC2?

A. To encrypt EBS volumes attached to EC2 instances.\
B. To launch EC2 instances with pre-configured operating systems and applications.\
C. To manage access permissions for EC2 instances.\
D. To create a backup of the EC2 instance state.

**Answer:** B. To launch EC2 instances with pre-configured operating systems and applications.

---

### ELB (Elastic Load Balancing):

**Q5:**
Which type of load balancer in ELB is best suited for distributing traffic across multiple availability zones?

A. Application Load Balancer\
B. Network Load Balancer\
C. Classic Load Balancer\
D. Internal Load Balancer

**Answer:** A. Application Load Balancer

---

**Q6:**
How does Elastic Load Balancing contribute to the fault tolerance of an application?

A. By providing real-time analytics of application traffic.\
B. By distributing incoming traffic across multiple EC2 instances.\
C. By creating automated backups of EC2 instances.\
D. By encrypting data in transit between clients and servers.

**Answer:** B. By distributing incoming traffic across multiple EC2 instances.

---


### EC2 Auto Scaling:

**Q1:**

**What is the primary purpose of AWS Auto Scaling in the context of infrastructure management?**

-   A) To provision new instances manually.
-   B) To automatically adjust the number of instances based on defined conditions.
-   C) To handle DNS resolution for incoming traffic.
-   D) To distribute traffic across multiple instances using a load balancer.

**Answer:**

-   B) _To automatically adjust the number of instances based on defined conditions._
---

**Q2:**

**Which AWS service allows you to define the launch settings for instances in an Auto Scaling Group?**

-   A) AWS Lambda
-   B) Amazon RDS
-   C) Amazon EC2 Auto Scaling
-   D) AWS Elastic Beanstalk

**Answer:**

-   C) _Amazon EC2 Auto Scaling_
---
**Q3:**


**What role do Launch Configurations play in an Auto Scaling Group?**

-   A) They define the pricing model for instances.
-   B) They specify launch settings for instances.
-   C) They control access to EC2 instances.
-   D) They are responsible for handling DNS requests.

**Answer:**

-   B) _They specify launch settings for instances._
---
**Q4:**

**How does Auto Scaling handle instances that fail health checks?**

-   A) It terminates the instance and launches a new one.
-   B) It automatically isolates the instance from the network.
-   C) It increases the instance's health threshold.
-   D) It ignores the health check results.

**Answer:**

-   A) _It terminates the instance and launches a new one._
---
**Q5:**

**Can Auto Scaling Groups be associated with Elastic Load Balancers (ELB)?**

-   A) No, Auto Scaling Groups and ELB cannot be used together.
-   B) Yes, instances launched by Auto Scaling Groups can be automatically registered with ELB.
-   C) Only if manual configuration is performed.
-   D) Only in specific regions.

**Answer:**

-   B) _Yes, instances launched by Auto Scaling Groups can be automatically registered with ELB._
---
**Q6:**

**What advantage does Auto Scaling with AWS Spot Instances offer?**

-   A) It provides unlimited computing resources.
-   B) It allows you to use spare EC2 capacity at a lower cost.
-   C) It ensures the highest level of security.
-   D) It is only suitable for non-production environments.

**Answer:**

-   B) _It allows you to use spare EC2 capacity at a lower cost._
---

### CloudFront:

**Q1:** A company wants to accelerate the delivery of its web content and improve the user experience. Which AWS service should be recommended for this purpose?

A. Amazon S3
B. AWS Global Accelerator
C. AWS CloudFront
D. Amazon Route 53

**Answer:** C. AWS CloudFront
---

**Q2:** What is the primary benefit of using AWS CloudFront in front of an S3 bucket?

A. Improved durability
B. Lower storage costs
C. Faster content delivery
D. Enhanced security controls

**Answer:** C. Faster content delivery
---

### Global Accelerator:

**Q3:** An organization wants to improve the availability and performance of their applications across multiple AWS regions. Which service should be suggested for achieving low-latency global routing?

A. Amazon CloudFront
B. AWS Global Accelerator
C. Amazon Route 53
D. AWS Direct Connect

**Answer:** B. AWS Global Accelerator
---

**Q4:** What is the key advantage of using AWS Global Accelerator over traditional global load balancing solutions?

A. Lower cost
B. Simplified DNS management
C. Enhanced security features
D. Global static IP addresses

**Answer:** D. Global static IP addresses
---

### AWS Lambda:

**Q1: What is the primary purpose of AWS Lambda?**

A. To manage databases
B. To create virtual machines
C. To run code in response to events
D. To deploy and manage containers

**Answer: C. To run code in response to events**
---

**Q2: Which programming languages are supported by AWS Lambda?**

A. Java only
B. Python only
C. Node.js, Python, Java, Go, and more
D. C# only

**Answer: C. Node.js, Python, Java, Go, and more**

---

### Amazon API Gateway:

**Q3: What is the main function of Amazon API Gateway?**

A. To store and retrieve data
B. To create and manage virtual networks
C. To design and publish APIs
D. To manage IAM roles

**Answer: C. To design and publish APIs**
---

**Q4: Which protocols does Amazon API Gateway support?**

A. HTTP and FTP
B. RESTful and SOAP
C. MQTT and AMQP
D. SSH and Telnet

**Answer: B. RESTful and SOAP**

---

### AWS Step Functions:

**Q5: What is the purpose of AWS Step Functions?**

A. To store and retrieve data
B. To create and manage databases
C. To automate and orchestrate workflows
D. To manage virtual machines

**Answer: C. To automate and orchestrate workflows**
---

**Q6: How are workflows defined in AWS Step Functions?**

A. JSON-based language
B. YAML-based language
C. SQL queries
D. Python scripts

**Answer: A. JSON-based language**

---

### Amazon DynamoDB:

**Q7: What type of database is Amazon DynamoDB?**

A. Relational database
B. Graph database
C. NoSQL database
D. In-memory database

**Answer: C. NoSQL database**
---

**Q8: What is the primary benefit of using Amazon DynamoDB?**

A. Strong consistency
B. Manual scaling
C. Server management
D. ACID transactions

**Answer: A. Strong consistency**
---

### Amazon S3 (Simple Storage Service):

**Q1: What is the maximum size of an individual object that you can store in Amazon S3?**

A. 1 TB\
B. 5 TB\
C. 10 GB\
D. 50 GB

**Answer:** B. 5 TB

---

**Q2: What storage class in Amazon S3 is designed for infrequently accessed data but requires rapid access when needed?**

A. S3 Standard\
B. S3 Intelligent-Tiering\
C. S3 Standard-IA (Infrequent Access)\
D. Glacier

**Answer:** C. S3 Standard-IA (Infrequent Access)

---

**Q3: How is data organized in an S3 bucket?**

A. In folders and subfolders\
B. In a flat structure\
C. In tables and rows\
D. In hierarchical databases

**Answer:** B. In a flat structure

---

**Q4: What is the maximum number of S3 buckets allowed per AWS account by default?**

A. 50\
B. 100\
C. 150\
D. Unlimited

**Answer:** B. 100

---

**Q5: How can you secure data in transit when uploading files to S3?**

A. Use server-side encryption\
B. Use SSL/TLS for data transfer\
C. Use access control lists (ACLs)\
D. Enable versioning

**Answer:** B. Use SSL/TLS for data transfer

---

**Q6: What is the URL format for accessing objects in an S3 bucket over HTTPS?**

A. https://s3.amazonaws.com/bucket/object\
B. https://s3.aws-region.amazonaws.com/bucket/object\
C. https://bucket.s3.amazonaws.com/object\
D. https://bucket.aws-region.s3.amazonaws.com/object

**Answer:** C. https://bucket.s3.amazonaws.com/object

These questions cover various aspects of Amazon S3, including storage classes, security, organization, and limits. Adjust the difficulty based on your preparation level. Good luck with your exam preparation!


### Amazon VPC:

**Q1:**
A company wants to establish a secure and private connection between its on-premises data center and an Amazon VPC. What AWS service should they use for this purpose?

A. Amazon VPN
B. Amazon VPC Peering
C. AWS Direct Connect
D. Amazon Route 53

**Answer:** C. AWS Direct Connect

---

**Q2:**
Which of the following is used to control inbound and outbound traffic to Amazon EC2 instances within a VPC?

A. Security Groups
B. VPC Peering
C. Network ACLs
D. Subnet Routing

**Answer:** A. Security Groups

---

**Q3:**
You need to design a solution where instances in a private subnet can securely access Amazon S3 without going over the public internet. What AWS service or feature would you use?

A. VPC Peering
B. VPC Endpoints
C. NAT Gateway
D. AWS Direct Connect

**Answer:** B. VPC Endpoints

---

**Q4:**
If a company wants to ensure high availability for their web application, which AWS service can they use to distribute incoming traffic across multiple EC2 instances in different availability zones?

A. Elastic Load Balancer (ELB)
B. Amazon CloudFront
C. Amazon Route 53
D. AWS Auto Scaling

**Answer:** A. Elastic Load Balancer (ELB)

---

**Q5:**
What is the primary purpose of a Network Access Control List (ACL) in Amazon VPC?

A. To filter traffic between subnets
B. To define security rules for instances
C. To manage IAM permissions
D. To route traffic between VPCs

**Answer:** A. To filter traffic between subnets

### AWS CloudWatch:

**Q1:**
Which AWS service is primarily used for monitoring and collecting metrics from various AWS resources?

A. AWS CloudTrail\
B. AWS CloudWatch\
C. AWS Config\
D. AWS Lambda

**Answer:** B. AWS CloudWatch

**Q2:**
What is the main purpose of AWS CloudWatch Alarms?

A. To store log data\
B. To automate infrastructure deployment\
C. To set thresholds and trigger notifications based on metric conditions\
D. To track changes in AWS resource configurations

**Answer:** C. To set thresholds and trigger notifications based on metric conditions

### AWS CloudTrail:

**Q1:**
What does AWS CloudTrail primarily provide?

A. Continuous monitoring and recording of configuration changes\
B. Collection and tracking of metrics\
C. Governance, compliance, and risk auditing\
D. Inventory management of AWS resources

**Answer:** C. Governance, compliance, and risk auditing

**Q2:**
Which type of information is included in AWS CloudTrail logs?

A. User and resource activity details\
B. Real-time log analytics\
C. Application log files\
D. AWS resource health status

**Answer:** A. User and resource activity details

### AWS Config:

**Q1:**
What is the main purpose of AWS Config?

A. Continuous monitoring of log files\
B. Configuration management and tracking changes to AWS resource configurations\
C. Real-time analysis of system performance\
D. Automated deployment of AWS resources

**Answer:** B. Configuration management and tracking changes to AWS resource configurations

**Q2:**
How does AWS Config enhance security?

A. By providing real-time log analytics\
B. By automating infrastructure deployment\
C. By continuously monitoring and recording configuration changes\
D. By storing log files in an encrypted form

**Answer:** C. By continuously monitoring and recording configuration changes
