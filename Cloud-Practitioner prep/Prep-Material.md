## Cloud-Practitioner Exam Notes - Not ordered! ##

* **Fault Tolerance** - The ability of a system to withstand component failures and remain operational.

* **Amazon Rekognition** - is the AWS service specifically designed to provide image and video analysis. It uses pre-trained deep learning models to identify objects, people, text, scenes, and activities, making it easy to add this functionality to applications without requiring machine learning expertise.

* **Reliability** - The Reliability pillar is focused on ensuring a workload performs its intended function correctly and consistently. A core principle of this pillar is designing for **high availiability** and **fault tolerance**, which includes the ability to withstand and automatically recover from failures, such as an entire Availability Zone Outage.

* **Amazon RDS** - Also Known as Amazon Relational Database Service is a managed service designed specifically to set up, operate, and scale relational databases in the cloud. It supports multiple popular database engines like MySQL, PostgreSQL, and SQL Server.

* **Amazon SQS** - Also known as Amazon Simple Queue Service is a fully managed queuing service designed specifically to decouple and scale microservices, distributed systems, and serverless applications. It stores messages in a durable queue, allowing the order processing application to send messages without needing the fraud Detection application to be immediately available, thus achieving loose coupling.

* **Enterprise Support Plan** - is designed for mission-critical workloads and is the only plan that includes a designated Technical Account Manager(TAM). The TAM provides proactive guidance, architectural reviews, and serves as a primary point of contact for strategic support.

* **NAT Gateway** - Also known as Network Address Translation Gateway is a managed AWS Service designed for enabling instances in a private subnet to initiate outbound traffic to the internet or other AWS services, but prevents the internet from initiating a connection with those instances, thus fulfillinf the security requirement.

* **IGW** - Internet Gateway is a VPC Component that allows two-way communication between instances in a public subnet and the Internet.

* **VGW** - Virtual Private Gateway is the component on the AWS side of a Site-to-Site VPN connection. It is used to establish secure, encrypted connectivity between a VPC and an on-premises network over the internet.

* **AWS Direct Connect** - is a cloud service that establishes a dedicated, private network connection from an on-premises data center to AWS. It is used for hybrid cloud connectivity.

* **Stateful** - When an inbound request that matches an 'allow' rule is received, the security group remembers this connection. The subsequent outbond response traffic dor that same connection is automatically permitted, even if there are no explicit outbound rules that would otherwise allow it.

* **RI** - Reserved Instances provide a significant discount(up to 72%) compared to On-Demand pricing in exchange for a 1 or 3-year commitment to a specific instance family in a particular region. 

* **Savings Plans** - are a flexible pricing model that offers significant savings(up to 72%) over On-Demand prices in exchange for a commitment to a consistent amount of usage(measured in $/hour) for a 1 year or 3 year term. *This is ideal for predictable,long-term workloads*

* **Installation and management of the guest operating system** - For **Infrastructure as a Service(IaaS)** offerings like **Amazon EC2**, the customer is responsible for the guest operating system. This includes installing, patching, configuring, and securing the OS, as well as any application and data running on the instance.

* **Modifying the AWS Support Plan is a sensitive, account-level billing action. For security and contractual reasons, AWS restricts this capability exclusively to the AWS account root user.**

* **AWS Whitepapers** - are authoritative technical documents that provide in-depth information on topics like architecture, security, and exonomics. They are an excellent resource for understanding architectural best practices and concepts for various AWS solutions.

* **AWS Documentation** - is the official and most comprehensive source for detailed technical information, including developer guides, API references, tutorials, and step-by-step instructions for implementing and using every AWS service.

* **Amazon WorkSpaces** - is a fully managed Desktop-as-a-Service(DaaS) solution that provides users with a persistent, cloud-based virtual desktop they can access from anywhere on supported devices.

* **Amazon EBS** - Also known as Amazon Elastic Block Store provides persistent, high-performance block-level storage volumes that function like virtual hard drives. These volumes can be attached to Amazon EC2 instances and persist independently of the instance's lifecycle.

* **Amazon FSx** - is a managed file storage service that provides shared file systems, similar to a network-attached storage (NAS) device. It is not a block-level storage service for individual EC2 instances.

* **High Availiability** - means designing a system with redundancy and failover mechanisms so that it can remain operational and accessible with minimal downtime, even if one or more of its components fail.

* **Performance Efficiency** - is a pillar that focuses on using IT and computing resources efficiently to meet system requirements. By using a CDN to cache content at edge locations closer to users, the service reduces latency and improves load times, which is a direct application of this pillar's principles.

* **AWS Prescriptive Guidance** - is a framework that provides a curated collection of solutions, implementation guides, patterns, and reference architectures based on AWS best practices to help accelerate a customer's cloud journey.

* **AWS Knowledge Center** - is the primary resource for finding troubleshooting articles, answers to frequently asked technical questions(FAQs), and best practice guides creayed by AWS support engineers. It covers a wide range of AWS services, including those focused on security.

* **CIDR Block** - is a range of IP addresses that share a common network prefix and are grouped together using Classless Inter-Domain Routing notation.

* The smallest allowed CIDR block size for a VPC is /28. This provides 16 total IP addresses, although AWS reserves 5 of them, leavinf 11 usable IP addresses.

* **Total IPs = 2^(32-prefix)**

* **AWS WAF** - also known as AWS Web Application Firewall is a service that protects web applications from common web exploits(Layer 7 attacks) like SQL injection or cross-site scripting.

* **NACL** - is a stateless firewall that operates at the subnet level, controlling traffic in and out of one or more subnets. --> It doesnt remember anything(Must write and Outbound rule).

* **Security Group** - acts as a stateful, virtual firewall for an EC2 instance to control inbound and outbound traffic

* **Amazon EBS(Repetition)** - also known as Amazon Elastic Block Store, provides persistent block-level storage volumes for use with Amazon EC2 instances. It functions like a virtual hard drive that can be attached to a single EC2 instance, on which you can install an operating system and file system.

* **AWS IoT Core** -is a manged cloud service specifically designed to let you connect billions of IoT devices to the AWS Cloud securely and reliably. It acts as a message broker or cloud gateway, allowing devices to communicate with each other and with other AWS services.

* **AWS Shield Standard** - is automatically enabled for all AWS customers at no additional cost. It provides essential protection against most common, frequently ocurring network and transport layer (Layer 3 and 4) DDoS attacks that target AWS services.

* **Amazon EKS** - Also known as Amazon Elastic Kubernetes Service is a managed service for running Kubernetes.However, by default, it still requires you to manage a cluster of EC2 instances (worker nodes) to run your containers. While EKS can be used with AWS Fargate for a serverless experience, EKS itself is the orchestration service, not the serverless compute engine.

* **AWS Fargate** - is a serverless, pay-as-you-go compute engine specifically designed for containers. It allows you to run containers without managing the underlying EC2 instances or servers. Fargate integrates with both Amazon ECS and Amazon EKS.

* **IAM** - Identity Access Manager, access keys, which consist of an access key ID and a secret access key, are long-term credentials used to authenticate and authorize programmatic requests to AWS services. They are specifically designed for use with the AWS Command Line Interface(CLI), Software Development Kits(SDKs), and direct API calls.

