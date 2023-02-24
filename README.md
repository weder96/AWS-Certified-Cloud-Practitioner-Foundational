 # This space's mission is to use the 7 best ways to apply <i>ACTIVE</i> learning in AWS Cloud Practitioner Certification studies.
1. Write it all down!
2. Griffe and doodle!
3. Question yourself at the end of a reading or class
4. Search more!
5. Do exercises
6. Create mind maps
7. Teach someone!

# Goal
In addition to the above objective, it is also possible to organize in a single topic several possibilities of studies, for the study
AWS Cloud Practitioner Certification, focusing on others who already report how to get there, and also linking content that
were and can be of great help to new students.

# AWS Cloud Practitioner Exam Guide

The AWS Certified Cloud Practitioner exam (CLF-C01) is intended for individuals who have the knowledge and skills required to effectively demonstrate a general understanding of the AWS cloud, independent of specific technical roles covered by other AWS certifications (e.g., solutions - Associate, Developer - Associate or SysOps Administrator - Associate).
This exam allows individuals to validate their AWS cloud knowledge with an industry-recognized credential.

This guide is in the works to help anyone who wants to take the AWS Certified Cloud Practitioner certification, cover it up and share some of my thoughts and ideas for those planning to take the exam.
The AWS Cloud Practitioner certification is a great entry point into the world of Amazon AWS.

<img src="./images/extra/aws_certifications.png" alt="certifications" />

Our focus is AWS Cloud Practitioner Certification, which is the gateway to others.

# What is AWS Cloud Practitioner Certification?
<details>
<summary> What is AWS Cloud Practitioner Certification? </summary>

Amazon has multiple AWS cloud certification paths.
The AWS Certified Cloud Practitioner certification is an entry-level certification that is intended to demonstrate a basic level of Amazon AWS cloud knowledge and skills.
This exam is suitable for professionals in technical, managerial, and sales roles.

To become certified, you must pass a single exam. Amazon recommends that you have at least <b>6 months of experience</b> before taking the exam. I had no prior experience with Amazon AWS prior to studying for the exam. I, however, seek in all ways to evolve.

The Certified Cloud Practitioner certification page provides links to numerous study resources, including AWS white papers, links to book the exam, sample test questions, and more.

</details>

# The content covered in the exam is as follows:

Domain 1 --> Cloud Concepts --> <b>26%</b> <br/>
Domain 2 --> Security and Compliance --> <b>25%</b> <br/>
Domain 3 --> Technology --> <b>33%</b> <br/>
Domain 4 --> Billing and Pricing --> <b>16%</b> <br/>


# Domain 1: Cloud Concepts
### 1.1 Defines the AWS Cloud and its value proposition
- Define the benefits of the AWS cloud including:
    - Security
    - Reliability
    - High Availability
    - Elasticity
    - Agility
    - Pay-as-you go pricing
    - Scalability
    - Global Reach
    - Economy of scale

- Explain how the AWS cloud allows users to focus on business value
    - Shifting technical resources to revenue-generating activities as opposed to managing infrastructure

### 1.2 Identify aspects of AWS Cloud economics
- Define items that would be part of a Total Cost of Ownership proposal
    - Understand the role of operational expenses (OpEx)
    - Understand the role of capital expenses (CapEx)
    - Understand labor costs associated with on-premises operations
    - Understand the impact of software licensing costs when moving to the cloud
- Identify which operations will reduce costs by moving to the cloud
    - Right-sized infrastructure
    - Benefits of automation
    - Reduce compliance scope (for example, reporting)
    - Managed services (for example, RDS, ECS, EKS, DynamoDB)

### 1.3 Explain the different cloud architecture design principles
- Explain the design principles
    - Design for failure
    - Decouple components versus monolithic architecture
    - Implement elasticity in the cloud versus on-premises
    - Think parallel

# Domain 2: Security and Compliance
### 2.1 Define the AWS shared responsibility model
- Recognize the elements of the Shared Responsibility Model
- Describe the customer’s responsibly on AWS
    - Describe how the customer’s responsibilities may shift depending on the service used (for example with RDS, Lambda, or EC2)
- Describe AWS responsibilities

### 2.2 Define AWS Cloud security and compliance concepts
- Identify where to find AWS compliance information
    - Locations of lists of recognized available compliance controls (for example, HIPPA, SOCs)
    - Recognize that compliance requirements vary among AWS services
- At a high level, describe how customers achieve compliance on AWS
    - Identify different encryption options on AWS (for example, In transit, At rest)
- Describe who enables encryption on AWS for a given service
- Recognize there are services that will aid in auditing and reporting
    - Recognize that logs exist for auditing and monitoring (do not have to understand the logs)
    - Define Amazon CloudWatch, AWS Config, and AWS CloudTrail
- Explain the concept of least privileged access

### 2.3 Identify AWS access management capabilities
- Understand the purpose of User and Identity Management
    - Access keys and password policies (rotation, complexity)
    - Multi-Factor Authentication (MFA)
    - AWS Identity and Access Management (IAM)
        - Groups/users
        - Roles
        - Policies, managed policies compared to custom policies
    - Tasks that require use of root accounts Protection of root accounts

### 2.4 Identify resources for security support
- Recognize there are different network security capabilities
    - Native AWS services (for example, security groups, Network ACLs, AWS WAF)
    - 3rd party security products from the AWS Marketplace
- Recognize there is documentation and where to find it (for example, best practices, whitepapers, official documents)
    - AWS Knowledge Center, Security Center, security forum, and security blogs
    - Partner Systems Integrators- Know that security checks are a component of AWS Trusted Advisor

# Domain 3: Technology
### 3.1 Define methods of deploying and operating in the AWS Cloud
- Identify at a high level different ways of provisioning and operating in the AWS cloud
    - Programmatic access, APIs, SDKs, AWS Management Console, CLI, Infrastructure as Code
- Identify different types of cloud deployment models
    -All in with cloud/cloud native
    -Hybrid
    -On-premises
- Identify connectivity options
    - VPN
    - AWS Direct Connect
    - Public internet

### 3.2 Define the AWS global infrastructure
- Describe the relationships among Regions, Availability Zones, and Edge Locations
- Describe how to achieve high availability through the use of multiple Availability Zones
    - Recall that high availability is achieved by using multiple Availability Zones
    - Recognize that Availability Zones do not share single points of failure
- Describe when to consider the use of multiple AWS Regions
    - Disaster recovery/business continuity
    - Low latency for end-users
    - Data sovereignty
- Describe at a high level the benefits of Edge Locations
    - Amazon CloudFront
    - AWS Global Accelerator

### 3.3 Identify the core AWS services
- Describe the categories of services on AWS (compute, storage, network, database)
- Identify AWS compute services
    - Recognize there are different compute families
    - Recognize the different services that provide compute (for example, AWS Lambda compared to Amazon Elastic Container Service (Amazon ECS), or Amazon EC2, etc.)
    - Recognize that elasticity is achieved through Auto Scaling
    - Identify the purpose of load balancers
- Identify different AWS storage services
    - Describe Amazon S3
    - Describe Amazon Elastic Block Store (Amazon EBS)
    - Describe Amazon S3 Glacier
    - Describe AWS Snowball
    - Describe Amazon Elastic File System (Amazon EFS)
    - Describe AWS Storage Gateway
- Identify AWS networking services
    - Identify VPC
    - Identify security groups
    - Identify the purpose of Amazon Route 53
    - Identify VPN, AWS Direct Connect
- Identify different AWS database services
    - Install databases on Amazon EC2 compared to AWS managed databases
    - Identify Amazon RDS
    - Identify Amazon DynamoDB
    - Identify Amazon Redshift
### 3.4 Identify resources for technology support
- Recognize there is documentation (best practices, whitepapers, AWS Knowledge Center, forums, blogs)
- Identify the various levels and scope of AWS support
    - AWS Abuse
    - AWS support cases
    - Premium support
    - Technical Account Managers
- Recognize there is a partner network (marketplace, third-party) including Independent Software Vendors and System Integrators
- Identify sources of AWS technical assistance and knowledge including professional services, solution architects, training and certification, and the Amazon Partner Network
- Identify the benefits of using AWS Trusted Advisor

# Domain 4: Billing and Pricing
### 4.1 Compare and contrast the various pricing models for AWS (for example, On-Demand Instances, Reserved Instances, and Spot Instance pricing)
- Identify scenarios/best fit for On-Demand Instance pricing
- Identify scenarios/best fit for Reserved-Instance pricing
    - Describe Reserved-Instances flexibility
    - Describe Reserved-Instances behavior in AWS Organizations
- Identify scenarios/best fit for Spot Instance pricing

### 4.2 Recognize the various account structures in relation to AWS billing and pricing
- Recognize that consolidated billing is a feature of AWS Organizations
- Identify how multiple accounts aid in allocating costs across departments

### 4.3 Identify resources available for billing support
- Identify ways to get billing support and information
    - Cost Explorer, AWS Cost and Usage Report, Amazon QuickSight, third-party partners, and AWS Marketplace tools
    - Open a billing support case
    - The role of the Concierge for AWS Enterprise Support Plan customers
- Identify where to find pricing information on AWS services
    - AWS Simple Monthly Calculator
    - AWS Services product pages
    - AWS Pricing API
- Recognize that alarms/alerts exist
- Identify how tags are used in cost allocation


## The AWS Certified Cloud Practitioner exam (CLF-C01) 

The AWS Certified Cloud Practitioner exam (CLF-C01) is intended for individuals who have the knowledge and skills necessary to effectively
demonstrate a general understanding of the AWS cloud, independent of specific technical roles covered by other AWS certifications (eg, Solutions Architect - Associate, Developer - Associate, or SysOps Administrator - Associate).
This exam allows individuals to validate their AWS cloud knowledge with an industry-recognized credential.

# Exam details
Prices: $100

Exam duration: 90 minutes

Exam content:
Two types of questions on the exam
Multiple choice: has one correct answer and three incorrect answers (distractors).
Multiple answer: has two correct answers from five options.

Always choose the best answer(s). incorrect answers
will be plausible and are designed to be attractive to candidates who don't know the correct answer.

Unanswered questions are scored as incorrect. There is no penalty for guessing.

Exam results:
The AWS Certified Cloud Practitioner exam (CLF-C01) is a pass or fail exam. The exam is scored against a minimum standard
established by AWS professionals who are guided by certification industry best practices and guidelines.
Exam results are reported as a scaled score from 100 to 1000, with a minimum passing score of 700.
The score shows how well you performed on the exam as a whole and whether or not you passed.
Validity of the exam: 2 years; Recertification is required every 2 years for all AWS Certifications.

# Exam preparation guide
Exam preparation can be accomplished through self-study with textbooks, practice exams, and on-site classroom programs. This book provides you with all the information and knowledge to help you pass the AWS Certified Cloud Practitioner Exam.
IPSpecialist provides full support for candidates to pass the exam.

<b>Step 1:</b> Consultar o Guia do Exame na AWS 
[https://aws.amazon.com/certification/certified-cloud-practitioner/?nc1=h_ls](https://aws.amazon.com/certification/certified-cloud-practitioner/?nc1=h_ls)

Guia do Exame

[AWS-Certified-Cloud-Practitioner_Exam-Guide](https://d1.awsstatic.com/training-and-certification/docs-cloud-practitioner/AWS-Certified-Cloud-Practitioner_Exam-Guide.pdf)

<b>Step 2:</b> Take the AWS Training Class
These courses and training materials will help you prepare for the exam:
AWS Training <a href="https://aws.amazon.com/en/training/">(aws.amazon.com/training)</a>

And in the above link get the study materials
<a href="https://d1.awsstatic.com/training-and-certification/ramp-up_guides/Ramp-Up_Guide_CloudPractitioner.pdf"> Pdf with the information</a>

The above file has important information like LEARNING RESOURCE, DURATION and TYPE, which gives you a path to follow, what ahead will be highlighted each theme and how each question is formed.

<b>Step 3:</b> Review the exam guide and sample questions
Review the exam template and study the sample questions available on the AWS website

<b>Step 4:</b> practice with individualized labs and study officer Documentations

Sign up for AWS Free Tier accounts to use limited free services and
Practice labs. Also, you can study the official documentation on the website.

<b>Step 5:</b> study the AWS whitepapers

1. Expand your technical knowledge with white papers written by the AWS team.
2. AWS Whitepapers (aws.amazon.com/whitepapers) Kindle, .pdf and other Materials
3. Amazon Web Services White Paper Overview, April 2017
4. Architecting for the Cloud: AWS Best Practices Whitepaper, February 2016
5. White Paper How AWS Pricing Works, March 2016
6. The Total Cost of (Not) Ownership of Web Applications in the Cloud White Paper, August 2012
7. AWS Support Plans Comparison Page

<b>Step 6:</b> Review the AWS FAQ
Browse these FAQs to find answers to the most common questions.

<b>Step 6:</b> take a mock exam
Test your knowledge online in a timed environment by registering at aws.training.

<b>Step 7:</b> schedule your exam and get certified
Schedule your exam at a testing center near you at aws.training.


## Which key tools, technologies, and concepts might be covered on the exam?

The following is a non-exhaustive list of the tools and technologies that could appear on the exam. This list is subject to change and is provided to help you understand the general scope of services, features, or technologies on the exam. The general tools and technologies in this list appear in no particular order.

AWS services are grouped according to their primary functions. While some of these technologies will likely be covered more than others on the exam, the order and placement of them in this list are no indication of relative weight or importance:

-  [APIs](https://github.com/weder96/aws-certification-learning/tree/main/module-12#section-6)
-  [Cost Explorer](https://github.com/weder96/aws-certification-learning/tree/main/module-2#section-04)
-  [AWS Cost and Usage Report](https://github.com/weder96/aws-certification-learning/tree/main/module-2#section-06)
-  [AWS Command Line Interface (CLI)](https://github.com/weder96/aws-certification-learning/tree/main/module-20#section-5)
-  [Elastic Load Balancers](https://github.com/weder96/aws-certification-learning/tree/main/module-5#section-3)
-  [Amazon EC2 instance types (for example, Reserved, On-Demand, Spot)](https://github.com/weder96/aws-certification-learning/tree/main/module-6#section-1)
-  [AWS global infrastructure (for example, AWS Regions, Availability Zones)](https://github.com/weder96/aws-certification-learning/tree/main/module-3)
-  [Infrastructure as Code (IaC)](https://github.com/weder96/aws-certification-learning/tree/main/module-23#section-01)
-  [Amazon Machine Images (AMIs)](https://github.com/weder96/aws-certification-learning/tree/main/module-6#section-15)
-  [AWS Management Console](https://github.com/weder96/aws-certification-learning/tree/main/module-20#section-12)
-  [AWS Marketplace](https://github.com/weder96/aws-certification-learning/tree/main/module-17#section-11)
-  [AWS Professional Services](https://aws.amazon.com/professional-services/?nc1=h_ls)
-  [AWS Personal Health Dashboard](https://github.com/weder96/aws-certification-learning/tree/main/module-20#section-14)
-  [Security groups](https://github.com/weder96/aws-certification-learning/tree/main/module-4#section-28)
-  [AWS Service Catalog](https://github.com/weder96/aws-certification-learning/tree/main/module-20#section-16)
-  [AWS Service Health Dashboard](https://aws.amazon.com/premiumsupport/technology/aws-health-dashboard/)
-  [Service quotas](https://docs.aws.amazon.com/servicequotas/latest/userguide/intro.html)
-  [AWS software development kits (SDKs)](https://github.com/weder96/aws-certification-learning/tree/main/module-17#section-12)
-  [AWS Support Center](https://github.com/weder96/aws-certification-learning/tree/main/module-1#section-06)
-  [AWS Support tiers](https://github.com/weder96/aws-certification-learning/tree/main/module-1#section-06)
-  [Virtual private networks (VPNs)](https://github.com/weder96/aws-certification-learning/tree/main/module-5#section-9)


## AWS services and features

### **Analytics:**
1. <img src="./images/solid/check.png" width="20px" target="_blank">[Amazon Athena](https://github.com/weder96/aws-certification-learning/tree/main/module-11#section-02)
2. <img src="./images/solid/check.png" width="20px" target="_blank">[Amazon Kinesis](https://github.com/weder96/aws-certification-learning/tree/main/module-11#section-05)
3. <img src="./images/solid/check.png" width="20px" target="_blank">[Amazon QuickSight](https://github.com/weder96/aws-certification-learning/tree/main/module-11#section-15)


----------------------------------------------------------------------------------------------------------------------------
### **Application Integration:**
1. <img src="./images/solid/check.png" width="20px" target="_blank"> [Amazon Simple Notification Service (Amazon SNS)](https://github.com/weder96/aws-certification-learning/tree/main/module-12#section-1)
2. <img src="./images/solid/check.png" width="20px" target="_blank">[Amazon Simple Queue Service (Amazon SQS)](https://github.com/weder96/aws-certification-learning/tree/main/module-12#section-2)


----------------------------------------------------------------------------------------------------------------------------
### **Compute and Serverless:**
1.  <img src="./images/solid/check.png" width="20px">[AWS Batch](https://github.com/weder96/aws-certification-learning/tree/main/module-6#section-9)
2.  <img src="./images/solid/check.png" width="20px">[Amazon EC2](https://github.com/weder96/aws-certification-learning/tree/main/module-6#section-1)
3.  <img src="./images/solid/check.png" width="20px">[AWS Elastic Beanstalk](https://github.com/weder96/aws-certification-learning/tree/main/module-6#section-8)
4.  <img src="./images/solid/check.png" width="20px">[AWS Lambda](https://github.com/weder96/aws-certification-learning/tree/main/module-14#section-1)
5.  <img src="./images/solid/check.png" width="20px">[Amazon Lightsail](https://github.com/weder96/aws-certification-learning/tree/main/module-6#section-6)
6.  <img src="./images/solid/check.png" width="20px">[Amazon WorkSpaces](https://github.com/weder96/aws-certification-learning/tree/main/module-6#section-14)


----------------------------------------------------------------------------------------------------------------------------
### **Containers:**
1.  <img src="./images/solid/check.png" width="20px">[Amazon Elastic Container Service (Amazon ECS)](https://github.com/weder96/aws-certification-learning/tree/main/module-18#section-02)
2.  <img src="./images/solid/check.png" width="20px">[Amazon Elastic Kubernetes Service (Amazon EKS)](https://github.com/weder96/aws-certification-learning/tree/main/module-18#section-03)
3.  <img src="./images/solid/check.png" width="20px">[AWS Fargate](https://github.com/weder96/aws-certification-learning/tree/main/module-18#section-04)


----------------------------------------------------------------------------------------------------------------------------
### **Database:**
1.  <img src="./images/solid/check.png" width="20px">[Amazon Aurora](https://github.com/weder96/aws-certification-learning/tree/main/module-8#section-12)
2.  <img src="./images/solid/check.png" width="20px">[Amazon DynamoDB](https://github.com/weder96/aws-certification-learning/tree/main/module-8#section-03)
3.  <img src="./images/solid/check.png" width="20px">[Amazon ElastiCache](https://github.com/weder96/aws-certification-learning/tree/main/module-8#section-05)
4.  <img src="./images/solid/check.png" width="20px">[Amazon RDS](https://github.com/weder96/aws-certification-learning/tree/main/module-8#section-02)
5.  <img src="./images/solid/check.png" width="20px">[Amazon Redshift](https://github.com/weder96/aws-certification-learning/tree/main/module-8#section-04)


----------------------------------------------------------------------------------------------------------------------------
### Developer Tools:
1. <img src="./images/solid/check.png" width="20px"> [AWS CodeBuild](https://github.com/weder96/aws-certification-learning/tree/main/module-26#section_04)
2. <img src="./images/solid/check.png" width="20px"> [AWS CodeCommit](https://github.com/weder96/aws-certification-learning/tree/main/module-26#section_06)
3. <img src="./images/solid/check.png" width="20px"> [AWS CodeDeploy](https://github.com/weder96/aws-certification-learning/tree/main/module-26#section_07)
4. <img src="./images/solid/check.png" width="20px"> [AWS CodePipeline](https://github.com/weder96/aws-certification-learning/tree/main/module-26#section_10)
5. <img src="./images/solid/check.png" width="20px"> [AWS CodeStar](https://github.com/weder96/aws-certification-learning/tree/main/module-26#section_03)


----------------------------------------------------------------------------------------------------------------------------
### **Customer Engagement:**
1. <img src="./images/solid/check.png" width="20px"> [Amazon Connect](https://github.com/weder96/aws-certification-learning/tree/main/module-27#section_02)


----------------------------------------------------------------------------------------------------------------------------
### **Management, Monitoring, and Governance:**
1. <img src="./images/solid/check.png" width="20px"> [AWS Auto Scaling](https://github.com/weder96/aws-certification-learning/tree/main/module-10#section-1)
2. <img src="./images/solid/check.png" width="20px"> [AWS Budgets](https://github.com/weder96/aws-certification-learning/tree/main/module-2#section-02)
3. <img src="./images/solid/check.png" width="20px"> [AWS CloudFormation](https://github.com/weder96/aws-certification-learning/tree/main/module-20#section-2)
4. <img src="./images/solid/check.png" width="20px"> [AWS CloudTrail](https://github.com/weder96/aws-certification-learning/tree/main/module-20#section-3)
5. <img src="./images/solid/check.png" width="20px"> [Amazon CloudWatch](https://github.com/weder96/aws-certification-learning/tree/main/module-20#section-4)
6. <img src="./images/solid/check.png" width="20px"> [AWS Config](https://github.com/weder96/aws-certification-learning/tree/main/module-20#section-7)
7. <img src="./images/solid/check.png" width="20px"> [AWS Cost and Usage Report](https://github.com/weder96/aws-certification-learning/tree/main/module-2#section-06)
8. <img src="./images/solid/check.png" width="20px"> [Amazon EventBridge (Amazon CloudWatch Events)](https://github.com/weder96/aws-certification-learning/tree/main/module-12#section-7)
9. <img src="./images/solid/check.png" width="20px"> [AWS License Manager](https://github.com/weder96/aws-certification-learning/tree/main/module-20#section-9)
10. <img src="./images/solid/check.png" width="20px"> [AWS Managed Services](https://github.com/weder96/aws-certification-learning/tree/main/module-17#section-5)
11. <img src="./images/solid/check.png" width="20px"> [AWS Organizations](https://github.com/weder96/aws-certification-learning/tree/main/module-15#section-18)
12. <img src="./images/solid/check.png" width="20px"> [AWS Secrets Manager](https://github.com/weder96/aws-certification-learning/tree/main/module-4#section-14)
13. <img src="./images/solid/check.png" width="20px"> [AWS Systems Manager](https://github.com/weder96/aws-certification-learning/tree/main/module-20#section-17)
14. <img src="./images/solid/check.png" width="20px"> [AWS Systems Manager Parameter Store](https://github.com/weder96/aws-certification-learning/tree/main/module-4#section-13)
15. <img src="./images/solid/check.png" width="20px"> [AWS Trusted Advisor](https://github.com/weder96/aws-certification-learning/tree/main/module-20#section-18)


----------------------------------------------------------------------------------------------------------------------------
### **Networking and Content Delivery:**
1. <img src="./images/solid/check.png" width="20px"> [Amazon API Gateway](https://github.com/weder96/aws-certification-learning/tree/main/module-5#section-10)
2. <img src="./images/solid/check.png" width="20px"> [Amazon CloudFront](https://github.com/weder96/aws-certification-learning/tree/main/module-5#section-1)
3. <img src="./images/solid/check.png" width="20px"> [AWS Direct Connect](https://github.com/weder96/aws-certification-learning/tree/main/module-5#section-2)
4. <img src="./images/solid/check.png" width="20px"> [Amazon Route 53](https://github.com/weder96/aws-certification-learning/tree/main/module-5#section-6)
5. <img src="./images/solid/check.png" width="20px"> [Amazon VPC](https://github.com/weder96/aws-certification-learning/tree/main/module-5#section-8)


----------------------------------------------------------------------------------------------------------------------------
### **Security, Identity, and Compliance:**
1. <img src="./images/solid/check.png" width="20px"> [AWS Artifact](https://github.com/weder96/aws-certification-learning/tree/main/module-4#section-02)
2. <img src="./images/solid/check.png" width="20px"> [AWS Certificate Manager (ACM)](https://github.com/weder96/aws-certification-learning/tree/main/module-4#section-07)
3. <img src="./images/solid/check.png" width="20px"> [AWS CloudHSM](https://github.com/weder96/aws-certification-learning/tree/main/module-4#section-06)
4. <img src="./images/solid/check.png" width="20px"> [Amazon Cognito](https://github.com/weder96/aws-certification-learning/tree/main/module-4#section-11)
5. <img src="./images/solid/check.png" width="20px"> [Amazon Detective](https://github.com/weder96/aws-certification-learning/tree/main/module-4#section-17)
6. <img src="./images/solid/check.png" width="20px"> [Amazon GuardDuty](https://github.com/weder96/aws-certification-learning/tree/main/module-4#section-03)
7. <img src="./images/solid/check.png" width="20px"> [AWS Identity and Access Management (IAM)](https://github.com/weder96/aws-certification-learning/tree/main/module-15)
8. <img src="./images/solid/check.png" width="20px"> [Amazon Inspector](https://github.com/weder96/aws-certification-learning/tree/main/module-4#section-01)
9. <img src="./images/solid/check.png" width="20px"> [AWS License Manager](https://github.com/weder96/aws-certification-learning/tree/main/module-20#section-9)
10. <img src="./images/solid/check.png" width="20px"> [Amazon Macie](https://github.com/weder96/aws-certification-learning/tree/main/module-4#section-19)
11. <img src="./images/solid/check.png" width="20px"> [AWS Shield](https://github.com/weder96/aws-certification-learning/tree/main/module-4#section-23)
12. <img src="./images/solid/check.png" width="20px"> [AWS WAF](https://github.com/weder96/aws-certification-learning/tree/main/module-4#section-04)


----------------------------------------------------------------------------------------------------------------------------
### **Storage:**
1. <img src="./images/solid/check.png" width="20px"> [AWS Backup](https://github.com/weder96/aws-certification-learning/tree/main/module-7#section-7)
2. <img src="./images/solid/check.png" width="20px"> [Amazon Elastic Block Store (Amazon EBS)](https://github.com/weder96/aws-certification-learning/tree/main/module-7#section-3)
3. <img src="./images/solid/check.png" width="20px"> [Amazon Elastic File System (Amazon EFS)](https://github.com/weder96/aws-certification-learning/tree/main/module-7#section-5)
4. <img src="./images/solid/check.png" width="20px"> [Amazon S3](https://github.com/weder96/aws-certification-learning/tree/main/module-7#section-1)
5. <img src="./images/solid/check.png" width="20px"> [Amazon S3 Glacier](https://github.com/weder96/aws-certification-learning/tree/main/module-7#section-1)
6. <img src="./images/solid/check.png" width="20px"> [AWS Snowball Edge](https://github.com/weder96/aws-certification-learning/tree/main/module-7#section-2)
7. <img src="./images/solid/check.png" width="20px"> [AWS Storage Gateway](https://github.com/weder96/aws-certification-learning/tree/main/module-7#section-6)


----------------------------------------------------------------------------------------------------------------------------
# The AWS services

AWS services allow access to computing resources, storage, databases and various other on-demand IT services. According to Amazon, this form of computing reduces costs, minimizes the risk of failure and maximizes business opportunities.

The AWS portal for Brazil is <a href="https://aws.amazon.com/pt/" alt="PT" > (https://aws.amazon.com/pt/) </a> .

It is possible to try out the main services, completely free of charge, for a period of one year. More information about this free trial is found on this page: <a href="https://aws.amazon.com/en/free/" alt="https://aws.amazon.com/en/free/"> https://aws.amazon.com/pt/free/ </a>.

The AWS Cloud is present in 190 countries across 13 geographic regions, 35 Availability Zones, and over 50 local points of presence. Figure 05 shows this global scope, and it is possible to observe where Amazon's Data Centers are located.


Figure XX - AWS Cloud on-premises coverage and points of presence. <br/>
<img src="./images/extra/regions.png" alt="regions" />
Source: Amazon website. Available at: <https://aws.amazon.com/pt/what-is-aws>. Accessed on: Aug. from 2021.


AWS customers are companies such as Netflix, Dropbox, Airbnb and Spotify. They all turned into computing giants using the services provided by Amazon's Data Centers.

AWS has a very vast set of products and services from different categories (processing, network, development, database, etc.), as we can see in the Figure Below.

Figure XX - Amazon Web Services products and services. <br/>
<img src="./images/extra/service.jpg" alt="service" />
Source: Amazon Services. Available at: <http://images.slideplayer.com/26/8773584/slides/slide_2.jpg>. Accessed on: Aug. from 2021.

# In a Computer World article highlights the 30 most sought after services on AWS

<img src="./images/extra/2nd-watch-30-aws-services-100662918-large970.idge_.jpg" alt="service30" />
Source: Amazon Services. Available at: <https://www.computerworld.com.pt/2016/06/17/30-servicos-mais-procurados-na-aws/>. Accessed on: Aug. from 2021.


# Some techniques that help in the improvement of Learning:

According to <b>Beatriz Oliveira</b> in her title article:

# How I Prepared for the AWS Certified Cloud Practitioner Certification
Available at: <a href="https://medium.com/sysadminas/como-me-preparei-para-a-certifica%C3%A7%C3%A3o-aws-cloud-pratictioner-358d37fb9c60" alt="Article Beatriz Oliveira"> (https://medium.com/sysadminas/como-me-preparei-para-a-certifica%C3%A7%C3%A3o-aws-cloud-pratictioner-358d37fb9c60) </a>


In this article, she reports tips for those who want to get this certification, which I am currently following:

If you already have some experience with AWS, dedicate at least 1 hour a day for about 3 months to study, I believe this is a nice period to study calmly for the test. Amazon recommends this certification for those who have at least 6 months of experience, so I believe that following this recommendation to prepare is very interesting.

Follow the preparation guide available on the AWS website.
<a href="https://d1.awsstatic.com/training-and-certification/docs-cloud-practitioner/AWS-Certified-Cloud-Practitioner_Exam-Guide.pdf"> Preparation Guide </a>

Take free simulations, like the one available on the whizlabs website.
<a href="https://www.whizlabs.com/aws-certified-cloud-practitioner/">https://www.whizlabs.com/aws-certified-cloud-practitioner/</a>

If you can, take the practice exam available on the AWS website
<a href="https://aws.amazon.com/en/certification/certification-prep/"> https://aws.amazon.com/en/certification/certification-prep/ </a>.

Create an account on the AWS website to familiarize yourself with the interface and services while studying.

# Other means I'm using too:
1. Creating Mind Maps. <br/>
2. Specific Books (Subject) and Questions. <br/>
3. Creation of a database of questions about the specific Certification. <br/>
4. Project-Based Learning<br/>
5. Problem-Based Learning<br/>
6. Search youtube classes on the subject. <br/>

#1. Creating Mind Maps.

The mindmaps for AWS services to get AWS Certificates easier. For Vietnamese, you can see the study guide [here](http://notcuder.com/toi-da-lay-chung-chi-aws-solutions-architect-associate-nhu-the-nao/)

Those images are designed with [xmind tool](http://www.xmind.net)

![alt text](https://raw.githubusercontent.com/gitvani/aws-mindmap/master/images/AWS%20Network.jpg)

![alt text](https://raw.githubusercontent.com/gitvani/aws-mindmap/master/images/AWS%20Storage.jpg)

![alt text](https://raw.githubusercontent.com/gitvani/aws-mindmap/master/images/AWS%20Compute.jpg)

![alt text](https://raw.githubusercontent.com/gitvani/aws-mindmap/master/images/AWS%20Database.jpg)

![AWSManagementTools AWSManagementTools](https://raw.githubusercontent.com/gitvani/aws-mindmap/master/images/AWS%20Management%20Tools.jpg)

![AWSApplication AWSApplication](https://raw.githubusercontent.com/gitvani/aws-mindmap/master/images/AWS%20Applications.jpg)


# 2. Specific Books (Subject) and Questions.
<p float="left">
     <img width="100" style="margin-left: 15px;" src="./images/books/studyGuide.jpg" alt="studyGuide" />
     <img width="100" style="margin-left: 15px;" src="./images/books/aws_certification.jpg" alt="aws_certification" />
     <img width="100" style="margin-left: 15px;" src="./images/books/aws_2019.jpg" alt="aws_2019" />
     <img width="100" style="margin-left: 15px;" src="./images/books/aws_2020.jpg" alt="aws_2020" />
     <img width="100" style="margin-left: 15px;" src="./images/books/danielCarter.jpg" alt="danielCarter" />
     <img width="100" style="margin-left: 15px;" src="./images/books/ips.jpg" alt="ips" />
</p>

# 3. Creation of a database of questions about the specific Certification.

<a href="https://www.awslagi.com/practice-questions/" alt="practice-questions">practice-questions</a><br/>
Accessed on: Aug. of 2021.<br/>
It has several questions for training, in the case of AWS Cloud Practitioner, the site has 3 Quiz and 6 Pdfs, with the questions.

# 6. Look for classes on youtube on the subject.

Channels on youtube About the Subject:
<br/><br/>
1. Cabeça na Nuvem Project<br/>
www.cabecananuvem.com<br/>
Introduction to cloud computing concepts and content for AWS Cloud Practitioner certification.<br/>
Cristiano Pelizzari<br/>
linkedin: <a href="https://www.linkedin.com/company/cabe%C3%A7a-na-nuvem/" alt="">https://www.linkedin.com/company/cabe%C3 %A7a-in-the-cloud/</a>

<a href="https://www.youtube.com/watch?v=68pF-rrJyqQ&list=PLMpVQWIR2lKesl8rRdVg4qbQcP64xGI2z" alt=""> PlayList with 86 videos:</a>
<br/>
Accessed on: Aug. of 2021.<br/>

What makes this playlist complete is the question of showing the use of AWS in practice, in addition to having a very specific theoretical part.
and directed, another advantage is that it is in Portuguese.<br/>


2. Freecodecamp
<a href="https://www.youtube.com/watch?v=3hLmDS179YE&t=896s" alt=""> AWS Certified Cloud Practitioner Training 2020 - Full Course</a>
<br/>
Accessed on: Aug. of 2021. <br/>

Video description:<br/>
This course will help you become an AWS Certified Cloud Practitioner. You will gain a thorough understanding of the AWS Cloud platform and be prepared to take the certification exam.<br/>
This knowledge and certification will open up job opportunities. You will be able to prove your expertise in AWS and cloud computing.<br/>
The exam can be taken anywhere as an online proctored exam.<br/>
Another cool detail of this video is the comments, where many credit approval for having studied with this format.<br/>

3. IT & Software

<a href="https://www.youtube.com/watch?v=h5jaLL0jHSQ&t=3939s" alt="">AWS Certified Cloud Practitioner Training Bootcamp</a>
<br/>
Accessed on: Aug. of 2021. <br/>

AWS Certified Cloud Practitioner Training Bootcamp
Latest Exam Version - PREPARE and PASS the AWS Certified Cloud Practitioner (CLF-C01) Exam


# Calculator

https://calculator.aws/#/


# Labs
https://amazon.qwiklabs.com/



# Some of the paths already taken
https://blogs.sap.com/2021/05/24/get-certified-aws-certified-cloud-practitioner-clf-c01/


