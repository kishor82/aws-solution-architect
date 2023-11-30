# Amazon Identity and Access Management (IAM)
Amazon Identity and Access Management (IAM) is a web service provided by Amazon Web Services (AWS) that enables secure control access to AWS resources. IAM allows you to manage users, groups, roles, and their permissions within your AWS environment. Here's a brief overview:

1.  **Users:**

    -   An IAM user is an entity that you create in AWS to represent the person or application that uses it.
    -   Each IAM user has a unique name and security credentials, and you can control the permissions for each user individually.
2.  **Groups:**

    -   IAM groups are a way to manage permissions for multiple users in a more efficient manner.
    -   Instead of attaching policies to individual users, you can create groups, assign policies to groups, and then add users to those groups.
3.  **Roles:**

    -   IAM roles are similar to users, but they are not associated with a specific person or identity.
    -   Roles are intended to be assumed by users, AWS services, or AWS resources for a specific set of permissions.
4.  **Policies:**

    -   IAM policies are JSON documents that define permissions and can be attached to users, groups, or roles.
    -   Policies specify what actions are allowed or denied on what AWS resources.
5.  **Permissions:**

    -   IAM provides fine-grained access control over AWS resources.
    -   You can control access to services and resources based on the principle of least privilege.
6.  **Multi-Factor Authentication (MFA):**

    -   IAM supports multi-factor authentication, adding an extra layer of security by requiring users to present two or more separate forms of identification.
7.  **Identity Federation:**

    -   IAM allows you to grant temporary access to users who are authenticated by an external identity provider (IdP) such as Microsoft Active Directory.
8.  **IAM Roles for AWS Services:**

    -   Many AWS services require permissions to interact with other services on your behalf. IAM roles can be assumed by AWS services to grant them the necessary permissions.
9.  **Access Key and Secret Access Key:**
    -   IAM users can have access keys, which are used to interact with AWS programmatically through the AWS Command Line Interface (CLI), SDKs, or API requests.
11.  **IAM Access Advisor:**

    -   Access Advisor helps you analyze and set permissions by providing data about service-last-accessed information.
12.  **IAM Conditions:**

    -   IAM policies support conditions, allowing you to specify when a policy should take effect.
13.  **IAM Policy Simulator:**

    -   The IAM Policy Simulator helps you test the effects of IAM policies by simulating various API actions against resources in your account.

IAM is a foundational service in AWS, and it plays a crucial role in securing and managing access to AWS resources. It follows the principle of least privilege, allowing organizations to control and audit access to their cloud resources effectively.


# **Amazon EC2 (Elastic Compute Cloud):**

1.  **Overview:**

    -   EC2 is a web service provided by AWS that allows users to run virtual servers (instances) in the cloud.
    -   It provides scalable compute capacity in the form of virtual machines, allowing users to easily scale their computing resources up or down.
2.  **Instances:**

    -   EC2 instances are virtual servers with varying capacities, allowing users to choose instances based on their specific needs.
    -   Instances come in various types (e.g., general-purpose, compute-optimized, memory-optimized) to cater to different workloads.
3.  **Images:**

    -   Users can create Amazon Machine Images (AMIs) of their EC2 instances, capturing the configuration, data, and applications. This allows for easy replication and scaling.
4.  **Instance Types:**

    -   Instances are available in different families and sizes, allowing users to choose the right combination of CPU, memory, storage, and networking capacity.
5.  **Security Groups:**

    -   EC2 instances are associated with security groups, acting as virtual firewalls. Users can define inbound and outbound traffic rules for added security.
6.  **Key Pairs:**

    -   Users can use key pairs for secure login to their instances. Key pairs are used to encrypt and decrypt login information.
7.  **Elastic Load Balancing (ELB):**

    -   ELB distributes incoming application traffic across multiple EC2 instances to ensure no single instance is overwhelmed, improving fault tolerance and availability.
8.  **Auto Scaling:**

    -   Auto Scaling enables users to automatically adjust the number of EC2 instances in a group based on demand. It helps ensure application availability and allows for cost optimization.
9.  **Elastic Block Store (EBS):**

    -   EC2 instances can be attached to EBS volumes, providing scalable and high-performance block storage that persists independently from the life of an instance.
10.  **Regions and Availability Zones:**

    -   EC2 instances can be launched in different geographic regions and availability zones to achieve high availability and fault tolerance.
11.  **Reserved Instances and Spot Instances:**

    -   Users can choose between on-demand, reserved, and spot instances, offering flexibility in pricing models based on usage patterns.
12.  **Instance Metadata and User Data:**

    -   Instances can access metadata about themselves and receive user data at launch time. This information is useful for customizing the behavior of instances.

EC2 is a fundamental service in AWS, providing the foundational infrastructure for various types of cloud-based applications. It is widely used for hosting websites, running applications, and performing various compute-intensive tasks in the cloud.lege, allowing organizations to control and audit access to their cloud resources effectively.
