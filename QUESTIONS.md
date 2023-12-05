
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
