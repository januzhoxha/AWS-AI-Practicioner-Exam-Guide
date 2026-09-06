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

* According to the AWS Shared Responsibility Model for managed service like RDS, the customer is responsible for their data and application code. Optimizing application-specific queries to ensure efficient database performance is an application-level task that falls under the customer's responsibility.

* **AWS Trust and Safety** - is the dedicated group responsible for investigating and taking action on reports of abusive or malicious activity originating from AWS resources, including AWS-owned IP addresses. This ensures the safety and integrity of the AWS network.

* **AWS Professional Services** - provides consulting, implementation support, and guidance to help customers with their cloud adoption, migration, and optimization projects.

* **AWS Concierge Support** - is a feature of the Enterprise Support plan and primarily assists customers with billing and account management inquiries, not with security or abuse-related issues.

* **Cassandra** - is a NoSQL wide-column store database and is not a supported engine on Amazon RDS. The AWS-managed service for Cassandra-compatible workloads is Amazon Keyspaces.

* **Redis** - is an in-memory data store, often used as a cache or message broker and is not a supported database engine on Amazon RDS. The corresponding managed AWS service for Redis is Amazon ElastiCache.

* **AWS Glue** - is a fully managed Extract, Transform, and Load(ETL) Service. Its primary purpose is to discover, prepare, and integrate data from multiple sources for analytics, machine learning, and application development.

* **Amazon QuickSight** - is a fully managed, cloud-native business intelligence(BI) service. It is used to create interactive visualizations, dashboards, and perfrom ad-hoc analysis to gain business insights from data, making it a primary analytics service.

* **CapEx** - is short for capital expenditure. Capital expenditure is the cost a business incurs to acquire assets that will provide benefits beyond the current year. CapEx is also reffered to as PP&E, which stands for Property, Plant, and Equipment.

* **AWS Trusted Advisor** - is an online tool that provides real-time guidance to help you provision your resources following AWS best practices. The security pillar of Trusted Advisor includes specific checks for identifying Amazon S3 buckets with unrestricted access and verifying whether MFA is enabled on the root account.

* **AWS CLI** - is the recommended efficient method for developers to perform quick, one-time operations. It provides direct access to every AWS API from the command line, enabling fast execution without navigating a GUI. Per official documentation, the CLI is considered the "daily driver for most DevOps engineers and architects" due to its speed and scriptability. Using commands like *aws s3 ls* and *aws s3 cp* accomplishes the task in seconds.

* **Total Cost of Ownership (TCO)** - is a financial estimate that includes all direct and indirect costs of a product or system over its entire lifecycle. It is a key concept used to compare the costs of running infrastructure on-premises (with high CapEx) versus on the AWS cloud (with high OpEx), taking into account factors like hardware, software, maintenance, power, cooling, and administrative overhead.

* **AWS Allocation Tags** - act as metadata to categorize and track AWS costs. By tagging resources with identifiers like project names, dedpartments, or cost centers, organizations can organize their spending, generate detailed cost reports, and effectively manage their cloud budget.

* **AWS Cost Explorer** - is specifically designed to let you visualize, understand, and manage your AWS costs and usage over time. It provides an interface with interactive charts and detailed reports to explore and analyze spending patterns.

* The primary purpose of a cross-account IAM role is to delegate access securely. It allows an identity(like a user or a service) in one AWS account to assume a role in a different account. This grants temporary permissions to access resources in the second account without needing to create and manage long-term credentials in that account.

* **AWS Region** - represents the highest-level and largest geographical boundary within the AWS Flobal Infrastructure. Each Region is a separate geographic are that is completely isolated from other Regions and contains multiple, isolated Availability Zones to provide fault tolerance and stability.

* **AWS Marketplace** - is a *curated* digital catalog that enables customers to find, buy, and deploy third-party software and services that run on AWS. It streamlines procurement and deployment of solutions.

* **AWS Fargate** - is a serverless compute engine for containers. It is eligible for Compute Savings Plans, which apply to its compute usage, offering a flexible way to reduce costs for containerized applications.

* **Amazon Transcribe** - Sppech-to-Text
* **Amazon Polly** - Text-to-Speech

* **OpEx** - Operational Expenditure
* **CapEx** - Capital Expenditure

* **AWS Enterprise Support plan** - offers 24/7 techincal support via phone,email, and chat, the full set of AWS Trusted Advisor checks, plus premium features like designated TAM.

* **AWS Business support plan** - also does the same stuff as enterprise

* **AWS Shield Advanced** - is a paid service that offers a high level of protection against sophisticated and larger-scale DDoS attacks. A key feature of Shield Advanced is providing 24x7 access to the AWS DDoS Response Team(DRT) for expert assistance during an attack.

* **Amazon Redshift** - is a fully managed petabyte-scale data warehouse service specifically designed for running complex analytical queries on large datasets. Its columnar storage and massively parallel processing (MPP) architecture make it the ideal choice for this use case.

* The primary function of an Elastic Load Balancer is to distribute incoming application traffic across multiple targets, such as EC2 instances, containers, and IP addresses. This improves availability, fault and tolerance, and scalability by acting as a single point of contact for clients.

* The 'License Included' model means that the cost of the software license is bundled into the Amazon EC2 instance pricing. This is the ideal option for customers who do not have a pre-existing license and want to run commercial software like Microsoft Windows Server on AWS.

* **Amazon GuardDuty** - is an intelligent threat detection service that continuously monitors for malicious activity and unauthorized behaviour. It uses machine learning, anomaly detection, and integrated threat intelligence to automatically identify threats such as unusual API activity.

* **AWS Backup** - is a fully managed service desinged to centralize and automate data protection (backups) across various AWS Services.

* **AWS Secrets Manager** - is a dedicated service designed to help you protect secrets needed to access your applications, services, and IT resources. The service enables you to easily rotate, manage and retrieve database credentials, API keys, and other secrets.

* A primary financial benefit of consolidated blling is that by aggregating the usage from all linked accountss, the organization's total usage is higher, which can help it reach volume pricing tiers more quickly.This results in a lower overall cost than if each account were billed individually.


* **AWS Schema Conversion Tool** - AWS SCT is specifically desigjed to assess and convert the source database schema, including tables, views, stored procedures, and other code objects, from one database engine(like Oracle) to a format compatible with a different target engine.

* AWS Shield Standard is automatically enabled for all AWS customers at no additional cost. It provides essential protection against most common, frequently occurring network and transport layer (Layer 3 and Layer 4) DDoS attacks that target AWS services.

* **Right Sizing** - is the process of matching instance types and sizes to your workload performance and capacity requirements at the lowest possible cost. It involves choosing the smallest or most optimal hardware and software footprint that meets the workloads' needs, thereby minimizing costs and maximizing efficiency without sacrificing performance.

* The Developer support plan is more cost-effective than the Business plan.

* **Economies of scale** - is the economic principle where the cost per unit decreases as the scale of operations increases. As AWS expands its global infrastructure, it achieves lower operational costs and passes these savings onto its customer through reduced prices.

* AWS IAM allows to securely control access to aws services and resources.It allows you to manage users, groups, and roles, and use policies to grant or deny permissions, ensuring that only authorized entities can perform actions on your resources.

* **Route Tables** - are a set of rules called routes that are used to determine where network traffic from your subnet or gateway is directed. Every subnet in a VPC must be associated with a route table, making it a fundamental component for controlling traffic flow.

* **Amazon S3 Standard** - is the default storage class designde for frequently accessed data. It offers high durability, availability, and performance for data that requires low latency and high throughput, providing milisecond access times.

* **AWS Organizations** - is the service specifically designed for centrally managing and governing your environment as you grow and scale your AWS resources. It allows you to group multiple AWS accounts, centrally apply policies to enforce governance, and consolidate billing into a single payment method for all accounts.

* **AWS Budgets** - allows you to set custom budgets to track your costs and usage and sends alerts when you exceed (or are forecasted to exceed) your defined thresholds. It specifically supports creating reservation utilization and coverage budgets for both Reserved Instances (RIs) and Savings Plans.

* You can host databases on EC2 because with RDS You have specific versions of popular database engines, meanwhile with EC2 you can choose whatever database engine you want.

* **Elasticity** - is the core cloud concept that describes the ability to acquire resources as you need them and release them when you no longer need them. This allows you to scale up or down to meet demans without being locked into long-term contracts.

* An EBS Volume is created within a specific Availiability Zone and can only be attached to a single EC2 instance that resides in that same Availability Zone. This co-location ensures the low-latency, high-performance connectivity reqquired for block storage.

* **Patch Management** - is a classic example of a shared control. AWS is responsible for patching the underlying infrastructure, including the hypervisor and physical hardware. The customer, however is responsible for patching their own guest operating systems and any applications they have installed.

* Go Serverless = Performance Efficiency

* **Amazon Comprehend** - Uses NLP as a metric to find if text expresses positive, negative or neutral sentiment, it does not require any machine learning expertise.

* **Amazon EFS(Elastic File System)** - provides a fully managed, scalable,elastic file system that uses the Network File System (NFS) protocol. It can ve mounted concurrently by multiple EC2 instances, providing a shared file system interface, which is directly analogous to a cloud-based Network Attached Storage(NAS) solution.

* **AWS AppSync** - is a fully managed service that uses GraphQL to make it easy to develop data-driven applications. It directly addresses the requirements by handling real-time data synchronization across clients, providing offline data access with conflict resolution and simplifying data querting from various sources.

* **AWS re:Post** - is an AWS-managed Q&A service that serves as an online community for users to ask technical questions and receive crowd-sourced, expert-reviewed answers from other customers, AWS partners, and AWS employees.

* Rehosting = Lift and shift

* Athena is connected to S3 Buckets *ad-hoc*

* **AWS Auto Scaling** - monitors your applications and automatically adjusts compute capacity(adding or removing EC2 instances) based on demand. This ensures that you maintain steady, predictable performance at the lowest possible cost.

* **Amazon Kendra** - is an intelligent enterprise search service powered by machine learning and natural language processing(NLP). It is specifically designed to index and search across multiple internal data silos like wikis, intranets, and file shares, allowing users to find information by asking questions in natural language.

* **Amazon DynamoDB** - is a fully managed, serverless, key-value NoSQL database designed to run high-performance applications at any scale. It delivers consistent, single-digit millisecong latency, making it the perfect choice for applications with these requirements.

* In AWS Organization the bill for all member accounts is sent to the management account(formerly master account).

* The People perspective of the AWS Cloud Adoption Framework(CAF) directly addresses the human elements of cloud adoption. It focuses on preparing the workforce through skills development, training, role definition, and managing the organizational and cultural changes required for a successful transition to the cloud.

* **Amazon ElastiCache** - is a managed in-memory data store and cache service that supports popular open-source engines like Redis and Memcached. It is the ideal solution for offloading frequent read requests from a relational database to provide low-latency responses, which is exactly what is needed duting a high-traffic flash sale.

* Within AWS Organizations, the cost benefits of Reserved Instances (RIs) are automatically applied to any matching instance usage across all accounts in the organization.

* **AWS Storage Gateway** - is a hybrid cloud storage service specifically designed to connect an on-premises software or hardware appliance with cloud-based storage.It provides seamless and secure integration between an organization's on-premises IT environment and AWS's storage infrastructure.

* Adopting a consumption model means you pay only for the computing resources you consume and increase or decrease usage depending on business requirements, rather than making large upfront capital investments.

* A VPC Peering connection is a networking connection between two VPCs that enables you to route traffic between them using private IPv4 or IPv6 addresses. Instances in either VPC can communicate with each other as if they are part of the same network.

* An Internet Gateway(IGW) must be attached to a Virtual Private Cloud (VPC) to allow communication between instances and the internet.
The Internet Gateway is a horizontally scaled, redundant, and highly available BPC component that allows communication between your VPC and the internet.

* **AWS Compute Optimizer** - analyzes the historical configuration and utilization metrics of your AWS compute resources, such as EC2 instances. It provides rightsizing recommendations to help you choose the optimal instance type to improve performance and reduce costs.

* **The Retain strategy** - is used for applications that are kept in the source(on-premises) environment. This is the perfect fit for the scenario described, where a company is not yet ready to migrate an application due to factors like complex dependencies, and will revisit it at a later date.

* **Amazon Connect** - is an easy-to-use,cloud-based contact center service that can be set up in minutes. It provides a cost-effective and scalable solution for businesses to offer customer service without the need for traditional, expensive contact center infrastructure.

* **AWS CodeBuild** - is a fully managed continuous integration service that compiles source code, runs tests, and produces software packages that are ready to deploy. It is the essential AWS service for the build/compilation stage of a CI/CD pipeline.

* **AWS CodePipeline** - is a fully managed continuous integration and continuous delivery service. It automates the build, test, and deploy phases of your release process, making it the key servic e for orchestrating the CI/CD workflow.

* **Amazon AppStream 2.0** - is a fully managed, secure application streaming service that centrally hosts and streams desktop applications to any device with a web browser, per AWS documentation. It eliminates the need to rewrite applications and supports on-demand scaling, making it ideal for delivering applications to employees without managing underlying infrastructure.

* **AWS Amplify** - is a set of purpose-built tools and services that lets frontend and mobile developers quickly build full-stack applications on AWS.

* Data transfer between AWS services within the same Availability Zone (AZ) using private IP addresses is typically free of charge. This is a key principle for cost-effective architecture on AWS.

* AWS WAF can be deployed directly on Amazon CloudFront, Application Load Balancer, Amazon API Gateway, AWS AppSync, and several other specific regional resource types.

* **Amazon EventBridge** - is a serverless event bus service specifically designed to connect applications using data from various sources, including AWS services, integrated Software-as-a-Service(SaaS) applications, and custom applications.

* **AWS Elastic Beanstalk** - is a classic example of a Platform as a Service (PaaS). Developers can simply ulpoad their application code, and Elastic Beanstalk automatically handles the deployment, capacity provisioning, load balancing, auto-scaling, and application health monitoring.

* Encryption at rest refers to the practice of securing stored, inactive data by scrambling it into an unreadable format using cryptographic algorithms so that it cannot be accessed without a decryption key.

* **AWS IAM Identity Center** - centrally manages Single Sign-On (SSO) access to multiple AWS accounts and cloud applications. It is specifically designed to connect with external identity providers(IdPs) like Okta and Azure AD, enabling users to log in with their existing corporate credentials.

* Before an allocation tag can be used for filtering in AWS Cost Managment tools it must be activated in the Billing and Cost Management console.

* AWS VPN = Secure and private connection between an on-premises network and an AWS VPC over the public internet

* Amazon S3 is a popular and cost-effective choice for hosting static websites. It can directly serve static contect like HTML, CSS, JavaScript, and image files to users.

* **AWS CloudFormation** - is the service that allows users to provision infrastructure as code using templates written in JSON or YAML.

* **AWS Personal Health Dashboard** - provides a personalized view of AWS service health and events that impact a user's specific AWS resources. It sends alerts and provides remdiation guidance for scheduled maintenance on EC2 instances tied to the user's account.

* **Provisioning** - is about creating resources.

* **Operating** - is about managing and monitoring them.

* **Repurchasing** - also known as 'drop and shop' is the strategy of moving to a different product, typically a Software-as-a-Service(SaaS) solution. This involves decommisioning the legacy on-remises application and purchasing a license for a new cloud-based product.

* **AWS Trusted Advisor** - is an online tool that acts as your customized cloud expert. It inspects your AWS environment and provides real-time guidance to help you provision your resources following AWS best practices across five specific categories: cost optimization, performance, security, fault tolerance, and service limits.

* Purchasing physical servers is an example of Capital Expense(CapEx).

* **AWS Whitepapers** - are authoritative, in-depth technical documents created by AWS. They provide comprehensive guidance, best practices, and reference architectures on a wide range of topics, including security, performance, and architectural principles, making them the ideal resource for this requirement.

* **Amazon SQS** - is a fully managed message queuing service designed specifically to decouple and scale microservices, distributed systems, and serverless applications. It stores messages in a durable queue, allowing the order processing application to send messages without needing the fradud detection application to be immediately available, thus achieving loose coupling.

* **Agility** - in the cloud refers to the ability to rapidly develop, test, and launch applications. Reducing the time to provision new resources from weeks (in a traditional data center) to mere minutes and allows organizations to innovate and respond to market changes much faster.

* A HyperVisor in AWS is a low-level software layer that runs directly on physical server hardware to split it into multiple isolated virtual machines, known as Amazon EC2 instances.

* **Encryption at rest** = protects data while it is tored on a disk, in a database, or on other persistent storage media. The question specifically asks about encrypting data as it is being trasferred.

* **Encryption in transit** = is also known as encryption in motion, it is the process of protecting data as it travels across a network, such as between an application server and a database. 

* **Amazon S3 Intelligent-Tiering** - is specifically designed to optimize storage costs by automatically moving data between a frequent access tier and an infrequent access tier when access patterns change. This is the ideal way.