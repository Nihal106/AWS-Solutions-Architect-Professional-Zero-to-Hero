<escape>
<p align="center">
  <img src="assets/banner.png" alt="AWS Solutions Architect Professional Zero to Hero Banner" width="100%">
</p>

<p align="center">

![AWS](https://img.shields.io/badge/AWS-FF9900?style=for-the-badge\&logo=amazonaws\&logoColor=white)
![SAP-C02](https://img.shields.io/badge/SAP--C02-Solutions%20Architect%20Professional-purple?style=for-the-badge)
![Level](https://img.shields.io/badge/Level-Intermediate%20to%20Advanced-blue?style=for-the-badge)
![Well-Architected](https://img.shields.io/badge/Well--Architected-Framework-FF9900?style=for-the-badge)
![Hands-on](https://img.shields.io/badge/Hands--On-Labs-success?style=for-the-badge)

</p>

# AWS Solutions Architect Professional — Zero to Hero

> From AWS architecture fundamentals to enterprise solution design — comprehensive explanations, architecture patterns, hands-on labs, real-world scenarios, interview preparation, and production-ready projects.

---

# ☁️ About This Repository

**AWS Solutions Architect Professional – Zero to Hero** is a structured, architecture-focused learning repository designed to help you master AWS from beginner to professional level while preparing for the **AWS Certified Solutions Architect – Professional (SAP-C02)** certification.

Unlike traditional certification notes, this repository focuses on:

* Enterprise architecture design
* AWS Cloud Adoption Framework (CAF)
* Landing Zone architecture using AWS Organizations & Control Tower
* AWS Well-Architected Framework
* Production-ready hands-on labs
* Real-world design scenarios
* Architecture diagrams and decision-making
* Interview preparation

Every section is organized into its own folder with a dedicated `README.md` covering architecture concepts, service comparisons, implementation guides, hands-on labs, and production scenarios.

---

# 🎯 Learning Outcomes

By the end of this repository, you'll be able to:

* Translate business and technical requirements into AWS solution architectures.
* Apply the AWS Well-Architected Framework to design secure, reliable, high-performing, and cost-effective solutions.
* Design enterprise Landing Zones using AWS Organizations and Control Tower.
* Apply the AWS Cloud Adoption Framework (CAF) to cloud transformation projects.
* Build secure multi-account governance using Organizational Units, Service Control Policies, IAM Identity Center, and AWS Resource Access Manager.
* Design highly available networking using VPC, Transit Gateway, Direct Connect, VPN, Route 53, CloudFront, Global Accelerator, and PrivateLink.
* Select the appropriate compute platform using EC2, Auto Scaling, ECS, EKS, Lambda, App Runner, and Elastic Beanstalk.
* Design scalable application architectures using APIs, messaging, event-driven patterns, and serverless technologies.
* Choose the right storage and database services for different workload requirements.
* Implement observability using CloudWatch, CloudTrail, AWS Config, X-Ray, and Systems Manager.
* Design disaster recovery strategies using Multi-AZ, Multi-Region, Pilot Light, Warm Standby, and Active-Active architectures.
* Plan enterprise migration and modernization using AWS Migration Hub, Application Migration Service, DMS, SCT, and Snow Family.
* Evaluate architectural trade-offs involving performance, security, reliability, complexity, and cost.
* Build production-ready AWS projects from scratch.

---

# 📚 Repository Contents

This repository follows a structured **Zero-to-Hero roadmap**, progressing from architecture fundamentals to enterprise-scale AWS solution design.

---

# 1. Architecture Fundamentals

This section introduces the core concepts of AWS solution architecture and builds the foundation required for SAP-C02. It focuses on understanding business problems, translating requirements into architecture, evaluating design options, and making decisions based on reliability, security, performance, cost, and operational needs.

📂 **[Explore → Architecture Fundamentals](./01-Architecture-Fundamentals/README.md)**

| #    | Sub-Topic                                                                                                           | Description                                                                                            |
| ---- | ------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------ |
| 1.1  | [Introduction to Solution Architecture](./01-Architecture-Fundamentals/01-Introduction-to-Solution-Architecture.md) | What solution architecture is and how architects translate business problems into technology solutions |
| 1.2  | [AWS Global Infrastructure](./01-Architecture-Fundamentals/02-AWS-Global-Infrastructure.md)                         | Regions, Availability Zones, Local Zones, Edge Locations, and Global Infrastructure                    |
| 1.3  | [Business Requirements](./01-Architecture-Fundamentals/03-Business-Requirements.md)                                 | Functional vs Non-functional requirements                                                              |
| 1.4  | [Architecture Decision Making](./01-Architecture-Fundamentals/04-Architecture-Decision-Making.md)                   | Evaluating alternatives, trade-offs, and decision frameworks                                           |
| 1.5  | [Architecture Quality Attributes](./01-Architecture-Fundamentals/05-Architecture-Quality-Attributes.md)             | Reliability, scalability, security, performance, maintainability, and resiliency                       |
| 1.6  | [AWS Design Principles](./01-Architecture-Fundamentals/06-AWS-Design-Principles.md)                                 | Design for failure, automation, loose coupling, least privilege, and stateless design                  |
| 1.7  | [Architecture Patterns](./01-Architecture-Fundamentals/07-Architecture-Patterns.md)                                 | Monolith, microservices, serverless, event-driven, and API-centric architectures                       |
| 1.8  | [Scalability, Availability & Resiliency](./01-Architecture-Fundamentals/08-Scalability-Availability-Resiliency.md)  | Designing systems that continue operating during failures                                              |
| 1.9  | [Architecture Trade-offs](./01-Architecture-Fundamentals/09-Architecture-Trade-offs.md)                             | Cost vs performance, consistency vs availability, and other architectural trade-offs                   |
| 1.10 | [Architecture Documentation & ADRs](./01-Architecture-Fundamentals/10-Architecture-Documentation-and-ADRs.md)       | Architecture diagrams, logical views, ADRs, and documentation                                          |

---

# 2. AWS Well-Architected Framework

This section explains how AWS recommends designing secure, reliable, high-performing, cost-efficient, and sustainable workloads using the **AWS Well-Architected Framework**.

📂 **[Explore → AWS Well-Architected Framework](./02-AWS-Well-Architected-Framework/README.md)**

| #   | Sub-Topic                                                                                  | Description                                                       |
| --- | ------------------------------------------------------------------------------------------ | ----------------------------------------------------------------- |
| 2.1 | [Framework Overview](./02-AWS-Well-Architected-Framework/01-Framework-Overview.md)         | Introduction to the Well-Architected Framework                    |
| 2.2 | [Operational Excellence](./02-AWS-Well-Architected-Framework/02-Operational-Excellence.md) | Continuous improvement and operational best practices             |
| 2.3 | [Security](./02-AWS-Well-Architected-Framework/03-Security.md)                             | Identity, detection, infrastructure protection, and data security |
| 2.4 | [Reliability](./02-AWS-Well-Architected-Framework/04-Reliability.md)                       | Recovery, fault tolerance, and resiliency                         |
| 2.5 | [Performance Efficiency](./02-AWS-Well-Architected-Framework/05-Performance-Efficiency.md) | Selecting efficient resources and optimizing workloads            |
| 2.6 | [Cost Optimization](./02-AWS-Well-Architected-Framework/06-Cost-Optimization.md)           | Eliminating unnecessary expenses                                  |
| 2.7 | [Sustainability](./02-AWS-Well-Architected-Framework/07-Sustainability.md)                 | Designing environmentally responsible workloads                   |
| 2.8 | [Well-Architected Tool](./02-AWS-Well-Architected-Framework/08-Well-Architected-Tool.md)   | Reviewing workloads using AWS Well-Architected Tool               |

---

# 3. AWS Cloud Adoption Framework & Landing Zones

This section explains how organizations adopt AWS at enterprise scale using the **AWS Cloud Adoption Framework (CAF)**, **AWS Organizations**, and **AWS Control Tower**.

📂 **[Explore → AWS Cloud Adoption Framework & Landing Zones](./03-Multi-Account-and-Governance/README.md)**

| #    | Sub-Topic                                                                                      | Description                                  |
| ---- | ---------------------------------------------------------------------------------------------- | -------------------------------------------- |
| 3.1  | [AWS CAF Overview](./03-Multi-Account-and-Governance/01-AWS-CAF-Overview.md)                   | Introduction to AWS Cloud Adoption Framework |
| 3.2  | [Business Perspective](./03-Multi-Account-and-Governance/02-Business-Perspective.md)           | Business transformation and outcomes         |
| 3.3  | [People Perspective](./03-Multi-Account-and-Governance/03-People-Perspective.md)               | Skills, roles, and organizational readiness  |
| 3.4  | [Governance Perspective](./03-Multi-Account-and-Governance/04-Governance-Perspective.md)       | Compliance, risk, and governance             |
| 3.5  | [Platform Perspective](./03-Multi-Account-and-Governance/05-Platform-Perspective.md)           | Building cloud foundations                   |
| 3.6  | [Security Perspective](./03-Multi-Account-and-Governance/06-Security-Perspective.md)           | Enterprise security planning                 |
| 3.7  | [Operations Perspective](./03-Multi-Account-and-Governance/07-Operations-Perspective.md)       | Cloud operations and management              |
| 3.8  | [AWS Organizations](./03-Multi-Account-and-Governance/08-AWS-Organizations.md)                 | Organizational Units, SCPs, and governance   |
| 3.9  | [AWS Control Tower](./03-Multi-Account-and-Governance/09-AWS-Control-Tower.md)                 | Landing Zone implementation                  |
| 3.10 | [Landing Zone Architecture](./03-Multi-Account-and-Governance/10-Landing-Zone-Architecture.md) | Enterprise multi-account architecture        |

---

# 4. Identity & Security

This section focuses on securing AWS environments using identity management, encryption, threat detection, and Zero Trust security principles.

📂 **[Explore → Identity & Security](./04-Identity-and-Security/README.md)**

| #   | Sub-Topic                                                                   | Description                        |
| --- | --------------------------------------------------------------------------- | ---------------------------------- |
| 4.1 | [IAM Fundamentals](./04-Identity-and-Security/01-IAM-Fundamentals.md)       | Users, Groups, Roles, and Policies |
| 4.2 | [IAM Identity Center](./04-Identity-and-Security/02-IAM-Identity-Center.md) | Enterprise authentication          |
| 4.3 | [AWS STS](./04-Identity-and-Security/03-AWS-STS.md)                         | Temporary credentials              |
| 4.4 | [KMS](./04-Identity-and-Security/04-KMS.md)                                 | Encryption and key management      |
| 4.5 | [Secrets Manager](./04-Identity-and-Security/05-Secrets-Manager.md)         | Managing secrets securely          |
| 4.6 | [GuardDuty](./04-Identity-and-Security/06-GuardDuty.md)                     | Threat detection                   |
| 4.7 | [Security Hub](./04-Identity-and-Security/07-Security-Hub.md)               | Security posture management        |
| 4.8 | [AWS WAF & Shield](./04-Identity-and-Security/08-WAF-and-Shield.md)         | Web application protection         |

---

# 5. Network Architecture

Design secure, scalable, and highly available AWS networking using VPC, Transit Gateway, Direct Connect, VPN, Route 53, CloudFront, and PrivateLink.

📂 **[Explore → Network Architecture](./05-Network-Architecture/README.md)**

| #   | Sub-Topic                                                                          | Description                       |
| --- | ---------------------------------------------------------------------------------- | --------------------------------- |
| 5.1 | [VPC Fundamentals](./05-Network-Architecture/01-VPC-Fundamentals.md)               | Building AWS virtual networks     |
| 5.2 | [Subnets & Route Tables](./05-Network-Architecture/02-Subnets-and-Route-Tables.md) | Public and private networking     |
| 5.3 | [Internet & NAT Gateway](./05-Network-Architecture/03-Internet-and-NAT-Gateway.md) | Internet connectivity             |
| 5.4 | [Transit Gateway](./05-Network-Architecture/04-Transit-Gateway.md)                 | Hub-and-spoke networking          |
| 5.5 | [Direct Connect](./05-Network-Architecture/05-Direct-Connect.md)                   | Dedicated enterprise connectivity |
| 5.6 | [CloudFront](./05-Network-Architecture/06-CloudFront.md)                           | Global content delivery           |
| 5.7 | [PrivateLink](./05-Network-Architecture/07-PrivateLink.md)                         | Private service connectivity      |

---

# 6. Compute Architecture

This section explains how to design scalable, highly available, and cost-effective compute architectures on AWS. It covers virtual machines, containers, serverless computing, Auto Scaling, workload placement, purchasing options, and enterprise compute design decisions.

📂 **[Explore → Compute Architecture](./06-Compute-Architecture/README.md)**

| # | Sub-Topic | Description |
|---|-----------|-------------|
| 6.1 | [Amazon EC2 Fundamentals](./06-Compute-Architecture/01-Amazon-EC2-Fundamentals.md) | Virtual machines, instance lifecycle, and EC2 architecture |
| 6.2 | [EC2 Instance Types](./06-Compute-Architecture/02-EC2-Instance-Types.md) | General Purpose, Compute Optimized, Memory Optimized, Storage Optimized, and Accelerated Computing |
| 6.3 | [EC2 Purchasing Options](./06-Compute-Architecture/03-EC2-Purchasing-Options.md) | On-Demand, Reserved Instances, Savings Plans, Spot Instances, and Dedicated Hosts |
| 6.4 | [Launch Templates](./06-Compute-Architecture/04-Launch-Templates.md) | Standardizing EC2 deployments |
| 6.5 | [Auto Scaling Groups](./06-Compute-Architecture/05-Auto-Scaling-Groups.md) | Scaling workloads automatically |
| 6.6 | [Elastic Load Balancing](./06-Compute-Architecture/06-Elastic-Load-Balancing.md) | ALB, NLB, and Gateway Load Balancer |
| 6.7 | [Amazon ECS](./06-Compute-Architecture/07-Amazon-ECS.md) | Container orchestration with ECS |
| 6.8 | [Amazon EKS](./06-Compute-Architecture/08-Amazon-EKS.md) | Kubernetes on AWS |
| 6.9 | [AWS Lambda](./06-Compute-Architecture/09-AWS-Lambda.md) | Serverless compute architecture |
| 6.10 | [Elastic Beanstalk](./06-Compute-Architecture/10-Elastic-Beanstalk.md) | Platform-as-a-Service deployments |
| 6.11 | [AWS App Runner](./06-Compute-Architecture/11-AWS-App-Runner.md) | Simplified container deployments |
| 6.12 | [AWS Batch & Outposts](./06-Compute-Architecture/12-AWS-Batch-and-Outposts.md) | Batch workloads and hybrid compute |

---

# 7. Application Architecture

This section covers modern application architecture patterns on AWS, including monolithic, microservices, serverless, API-first, and event-driven designs for building scalable enterprise applications.

📂 **[Explore → Application Architecture](./07-Application-Architecture/README.md)**

| # | Sub-Topic | Description |
|---|-----------|-------------|
| 7.1 | [Three-Tier Architecture](./07-Application-Architecture/01-Three-Tier-Architecture.md) | Classic web application architecture |
| 7.2 | [Microservices Architecture](./07-Application-Architecture/02-Microservices-Architecture.md) | Independent service-based design |
| 7.3 | [Serverless Architecture](./07-Application-Architecture/03-Serverless-Architecture.md) | Event-driven serverless applications |
| 7.4 | [API Gateway Design](./07-Application-Architecture/04-API-Gateway-Design.md) | Designing scalable APIs |
| 7.5 | [Event-Driven Patterns](./07-Application-Architecture/05-Event-Driven-Patterns.md) | Asynchronous architectures |
| 7.6 | [Caching Strategies](./07-Application-Architecture/06-Caching-Strategies.md) | CloudFront, ElastiCache, and application caching |
| 7.7 | [Application Modernization](./07-Application-Architecture/07-Application-Modernization.md) | Modernizing legacy workloads |

---

# 8. Messaging & Integration

This section explores how AWS services communicate across distributed systems using messaging, events, orchestration, and integration patterns.

📂 **[Explore → Messaging & Integration](./08-Messaging-and-Integration/README.md)**

| # | Sub-Topic | Description |
|---|-----------|-------------|
| 8.1 | [Amazon SNS](./08-Messaging-and-Integration/01-Amazon-SNS.md) | Publish-subscribe messaging |
| 8.2 | [Amazon SQS](./08-Messaging-and-Integration/02-Amazon-SQS.md) | Queue-based messaging |
| 8.3 | [Amazon EventBridge](./08-Messaging-and-Integration/03-Amazon-EventBridge.md) | Event routing |
| 8.4 | [AWS Step Functions](./08-Messaging-and-Integration/04-AWS-Step-Functions.md) | Workflow orchestration |
| 8.5 | [Amazon MQ](./08-Messaging-and-Integration/05-Amazon-MQ.md) | Managed message brokers |
| 8.6 | [Integration Patterns](./08-Messaging-and-Integration/06-Integration-Patterns.md) | Fan-out, queue buffering, and orchestration |

---

# 9. Storage Architecture

This section explains how AWS storage services work together to build secure, scalable, durable, and cost-efficient storage solutions for enterprise workloads.

📂 **[Explore → Storage Architecture](./09-Storage-Architecture/README.md)**

| # | Sub-Topic | Description |
|---|-----------|-------------|
| 9.1 | [Amazon S3 Fundamentals](./09-Storage-Architecture/01-Amazon-S3-Fundamentals.md) | Object storage fundamentals |
| 9.2 | [S3 Storage Classes](./09-Storage-Architecture/02-S3-Storage-Classes.md) | Choosing the right storage tier |
| 9.3 | [S3 Lifecycle Policies](./09-Storage-Architecture/03-S3-Lifecycle-Policies.md) | Automating storage transitions |
| 9.4 | [Versioning & Replication](./09-Storage-Architecture/04-Versioning-and-Replication.md) | Data protection |
| 9.5 | [Amazon EBS](./09-Storage-Architecture/05-Amazon-EBS.md) | Block storage |
| 9.6 | [Amazon EFS](./09-Storage-Architecture/06-Amazon-EFS.md) | Shared file storage |
| 9.7 | [Amazon FSx](./09-Storage-Architecture/07-Amazon-FSx.md) | Managed file systems |
| 9.8 | [AWS Storage Gateway](./09-Storage-Architecture/08-AWS-Storage-Gateway.md) | Hybrid storage |
| 9.9 | [AWS Backup](./09-Storage-Architecture/09-AWS-Backup.md) | Centralized backup management |

---

# 10. Database Architecture

This section helps you select the right AWS database service based on workload requirements, scalability, consistency, performance, and operational considerations.

📂 **[Explore → Database Architecture](./10-Database-Architecture/README.md)**

| # | Sub-Topic | Description |
|---|-----------|-------------|
| 10.1 | [Amazon RDS](./10-Database-Architecture/01-Amazon-RDS.md) | Managed relational databases |
| 10.2 | [Amazon Aurora](./10-Database-Architecture/02-Amazon-Aurora.md) | High-performance relational database |
| 10.3 | [Amazon DynamoDB](./10-Database-Architecture/03-Amazon-DynamoDB.md) | NoSQL database |
| 10.4 | [Amazon ElastiCache](./10-Database-Architecture/04-Amazon-ElastiCache.md) | In-memory caching |
| 10.5 | [Amazon Redshift](./10-Database-Architecture/05-Amazon-Redshift.md) | Data warehouse |
| 10.6 | [Amazon Neptune](./10-Database-Architecture/06-Amazon-Neptune.md) | Graph database |
| 10.7 | [Amazon DocumentDB](./10-Database-Architecture/07-Amazon-DocumentDB.md) | Document database |
| 10.8 | [AWS DMS & SCT](./10-Database-Architecture/08-AWS-DMS-and-SCT.md) | Database migration |

---

# 11. Data Analytics

This section introduces AWS analytics services for processing, transforming, querying, streaming, and visualizing data at scale.

📂 **[Explore → Data Analytics](./11-Data-Analytics/README.md)**

| # | Sub-Topic | Description |
|---|-----------|-------------|
| 11.1 | [AWS Glue](./11-Data-Analytics/01-AWS-Glue.md) | ETL service |
| 11.2 | [Amazon Athena](./11-Data-Analytics/02-Amazon-Athena.md) | SQL queries on S3 |
| 11.3 | [Amazon EMR](./11-Data-Analytics/03-Amazon-EMR.md) | Big data processing |
| 11.4 | [Amazon Kinesis](./11-Data-Analytics/04-Amazon-Kinesis.md) | Streaming analytics |
| 11.5 | [Lake Formation](./11-Data-Analytics/05-Lake-Formation.md) | Data lake governance |
| 11.6 | [Amazon QuickSight](./11-Data-Analytics/06-Amazon-QuickSight.md) | Business intelligence |

---

# 12. Containers & Serverless

This section covers container orchestration, serverless computing, and modern deployment strategies for cloud-native applications.

📂 **[Explore → Containers & Serverless](./12-Containers-and-Serverless/README.md)**

| # | Sub-Topic | Description |
|---|-----------|-------------|
| 12.1 | [Docker Fundamentals](./12-Containers-and-Serverless/01-Docker-Fundamentals.md) | Container basics |
| 12.2 | [Amazon ECS](./12-Containers-and-Serverless/02-Amazon-ECS.md) | Container orchestration |
| 12.3 | [AWS Fargate](./12-Containers-and-Serverless/03-AWS-Fargate.md) | Serverless containers |
| 12.4 | [Amazon EKS](./12-Containers-and-Serverless/04-Amazon-EKS.md) | Kubernetes |
| 12.5 | [AWS Lambda](./12-Containers-and-Serverless/05-AWS-Lambda.md) | Event-driven serverless |
| 12.6 | [Amazon API Gateway](./12-Containers-and-Serverless/06-Amazon-API-Gateway.md) | API management |

---

# 13. Observability & Operations

This section explains how to monitor, automate, secure, and operate production AWS environments using native observability and management services.

📂 **[Explore → Observability & Operations](./13-Observability-and-Operations/README.md)**

| # | Sub-Topic | Description |
|---|-----------|-------------|
| 13.1 | [Amazon CloudWatch](./13-Observability-and-Operations/01-Amazon-CloudWatch.md) | Metrics, logs, and alarms |
| 13.2 | [AWS CloudTrail](./13-Observability-and-Operations/02-AWS-CloudTrail.md) | API auditing |
| 13.3 | [AWS Config](./13-Observability-and-Operations/03-AWS-Config.md) | Configuration compliance |
| 13.4 | [AWS X-Ray](./13-Observability-and-Operations/04-AWS-X-Ray.md) | Distributed tracing |
| 13.5 | [AWS Systems Manager](./13-Observability-and-Operations/05-AWS-Systems-Manager.md) | Fleet management |
| 13.6 | [AWS Trusted Advisor](./13-Observability-and-Operations/06-AWS-Trusted-Advisor.md) | Best practice recommendations |
| 13.7 | [AWS Compute Optimizer](./13-Observability-and-Operations/07-AWS-Compute-Optimizer.md) | Resource optimization |

---

# 14. Disaster Recovery & Business Continuity

This section focuses on designing resilient architectures that minimize downtime and data loss during failures and disasters.

📂 **[Explore → Disaster Recovery & Business Continuity](./14-Disaster-Recovery-and-BCP/README.md)**

| # | Sub-Topic | Description |
|---|-----------|-------------|
| 14.1 | [Backup Strategies](./14-Disaster-Recovery-and-BCP/01-Backup-Strategies.md) | Backup planning |
| 14.2 | [Multi-AZ Architecture](./14-Disaster-Recovery-and-BCP/02-Multi-AZ-Architecture.md) | High availability |
| 14.3 | [Multi-Region Design](./14-Disaster-Recovery-and-BCP/03-Multi-Region-Design.md) | Regional resilience |
| 14.4 | [Pilot Light Strategy](./14-Disaster-Recovery-and-BCP/04-Pilot-Light.md) | Minimal standby |
| 14.5 | [Warm Standby](./14-Disaster-Recovery-and-BCP/05-Warm-Standby.md) | Reduced recovery time |
| 14.6 | [Active-Active Architecture](./14-Disaster-Recovery-and-BCP/06-Active-Active-Architecture.md) | Multi-region active deployments |
| 14.7 | [RPO & RTO Planning](./14-Disaster-Recovery-and-BCP/07-RPO-and-RTO-Planning.md) | Recovery planning |

---

# 15. Migration & Modernization

This section explains how organizations migrate, modernize, and transform workloads on AWS using proven enterprise frameworks and migration services.

📂 **[Explore → Migration & Modernization](./15-Migration-and-Modernization/README.md)**

| # | Sub-Topic | Description |
|---|-----------|-------------|
| 15.1 | [AWS Cloud Adoption Framework](./15-Migration-and-Modernization/01-AWS-Cloud-Adoption-Framework.md) | Enterprise cloud adoption |
| 15.2 | [Migration Hub](./15-Migration-and-Modernization/02-Migration-Hub.md) | Migration management |
| 15.3 | [Application Migration Service](./15-Migration-and-Modernization/03-Application-Migration-Service.md) | Server migration |
| 15.4 | [AWS DMS](./15-Migration-and-Modernization/04-AWS-DMS.md) | Database migration |
| 15.5 | [AWS SCT](./15-Migration-and-Modernization/05-AWS-SCT.md) | Schema conversion |
| 15.6 | [AWS Snow Family](./15-Migration-and-Modernization/06-AWS-Snow-Family.md) | Offline migration |

---

# 16. Cost Optimization

This section helps you optimize AWS costs without compromising performance, security, or reliability.

📂 **[Explore → Cost Optimization](./16-Cost-Optimization/README.md)**

| # | Sub-Topic | Description |
|---|-----------|-------------|
| 16.1 | [Savings Plans](./16-Cost-Optimization/01-Savings-Plans.md) | Flexible savings |
| 16.2 | [Reserved Instances](./16-Cost-Optimization/02-Reserved-Instances.md) | Long-term discounts |
| 16.3 | [Spot Instances](./16-Cost-Optimization/03-Spot-Instances.md) | Low-cost compute |
| 16.4 | [Cost Explorer](./16-Cost-Optimization/04-Cost-Explorer.md) | Spending analysis |
| 16.5 | [AWS Budgets](./16-Cost-Optimization/05-AWS-Budgets.md) | Budget alerts |
| 16.6 | [Trusted Advisor Cost Checks](./16-Cost-Optimization/06-Trusted-Advisor-Cost-Checks.md) | Cost recommendations |

---

# 17. Professional Design Scenarios

Apply everything learned throughout the repository to solve complex enterprise architecture challenges similar to SAP-C02 exam scenarios.

📂 **[Explore → Professional Design Scenarios](./17-Professional-Scenarios/README.md)**

| # | Sub-Topic | Description |
|---|-----------|-------------|
| 17.1 | [Multi-Account Enterprise Design](./17-Professional-Scenarios/01-Multi-Account-Enterprise-Design.md) | Enterprise governance |
| 17.2 | [Hybrid Connectivity](./17-Professional-Scenarios/02-Hybrid-Connectivity.md) | Direct Connect and VPN |
| 17.3 | [Financial Governance](./17-Professional-Scenarios/03-Financial-Governance.md) | Cost governance |
| 17.4 | [Security Scenarios](./17-Professional-Scenarios/04-Security-Scenarios.md) | Enterprise security |
| 17.5 | [Disaster Recovery Scenarios](./17-Professional-Scenarios/05-Disaster-Recovery-Scenarios.md) | Resilience design |

---

# 18. Architecture Diagrams

This section contains production-ready AWS reference architectures and visual design patterns used throughout the repository.

📂 **[Explore → Architecture Diagrams](./18-Architecture-Diagrams/README.md)**

| # | Diagram | Description |
|---|---------|-------------|
| 18.1 | [Three-Tier Architecture](./18-Architecture-Diagrams/01-Three-Tier-Architecture.md) | Classic web architecture |
| 18.2 | [Serverless Architecture](./18-Architecture-Diagrams/02-Serverless-Architecture.md) | Event-driven design |
| 18.3 | [Landing Zone Architecture](./18-Architecture-Diagrams/03-Landing-Zone-Architecture.md) | Multi-account enterprise setup |
| 18.4 | [Transit Gateway Architecture](./18-Architecture-Diagrams/04-Transit-Gateway-Architecture.md) | Hub-and-spoke networking |
| 18.5 | [Disaster Recovery Architecture](./18-Architecture-Diagrams/05-Disaster-Recovery-Architecture.md) | Multi-region resilience |

---

# 19. Interview Questions

Prepare for AWS Solutions Architect interviews with service-wise, scenario-based, and architecture design questions.

📂 **[Explore → Interview Questions](./19-Interview-Questions/README.md)**

| # | Section | Description |
|---|---------|-------------|
| 19.1 | [EC2 Interview Questions](./19-Interview-Questions/01-EC2-Interview-Questions.md) | Compute questions |
| 19.2 | [Networking Interview Questions](./19-Interview-Questions/02-Networking-Interview-Questions.md) | VPC and networking |
| 19.3 | [Storage Interview Questions](./19-Interview-Questions/03-Storage-Interview-Questions.md) | S3, EBS, and EFS |
| 19.4 | [Scenario-Based Questions](./19-Interview-Questions/04-Scenario-Based-Questions.md) | Real interview scenarios |

---

# 20. Capstone Projects

Build complete enterprise AWS projects that combine multiple AWS services into production-ready architectures.

📂 **[Explore → Capstone Projects](./20-Capstone-Projects/README.md)**

| # | Project | Description |
|---|---------|-------------|
| 20.1 | [Highly Available Web Application](./20-Capstone-Projects/01-Highly-Available-Web-Application.md) | ALB + Auto Scaling + RDS |
| 20.2 | [Serverless Image Processor](./20-Capstone-Projects/02-Serverless-Image-Processor.md) | Lambda + S3 + API Gateway |
| 20.3 | [Microservices Platform](./20-Capstone-Projects/03-Microservices-Platform.md) | ECS + Service Discovery |
| 20.4 | [Enterprise Landing Zone](./20-Capstone-Projects/04-Enterprise-Landing-Zone.md) | Control Tower + Organizations |
| 20.5 | [Multi-Region Disaster Recovery](./20-Capstone-Projects/05-Multi-Region-Disaster-Recovery.md) | Active-Active architecture |

---
# 🗂 Repository Structure

```text
AWS-Solutions-Architect-Professional-Zero-to-Hero
│
├── README.md
├── ROADMAP.md
├── CONTRIBUTING.md
├── LICENSE
├── assets/
│   ├── banner.png
│   ├── logo.png
│   └── icons/
│
├── 01-Architecture-Fundamentals/
├── 02-AWS-Well-Architected-Framework/
├── 03-Multi-Account-and-Governance/
├── 04-Identity-and-Security/
├── 05-Network-Architecture/
├── 06-Compute-Architecture/
├── 07-Application-Architecture/
├── 08-Messaging-and-Integration/
├── 09-Storage-Architecture/
├── 10-Database-Architecture/
├── 11-Data-Analytics/
├── 12-Containers-and-Serverless/
├── 13-Observability-and-Operations/
├── 14-Disaster-Recovery-and-BCP/
├── 15-Migration-and-Modernization/
├── 16-Cost-Optimization/
├── 17-Professional-Scenarios/
├── 18-Architecture-Diagrams/
├── 19-Interview-Questions/
└── 20-Capstone-Projects/
```

---

# 📈 Learning Path

```text
Architecture Fundamentals
        │
        ▼
AWS Well-Architected Framework
        │
        ▼
Cloud Adoption Framework & Landing Zones
        │
        ▼
Identity & Security
        │
        ▼
Networking & Compute
        │
        ▼
Application Architecture
        │
        ▼
Storage & Databases
        │
        ▼
Monitoring & Operations
        │
        ▼
Migration & Disaster Recovery
        │
        ▼
Professional Design Scenarios
        │
        ▼
Capstone Projects
```

---

# 👨‍💻 Who Is This Repository For?

This repository is designed for:

* Students learning AWS from scratch
* Cloud Engineers
* DevOps Engineers
* Solutions Architects
* Full Stack Developers transitioning into Cloud
* Professionals preparing for **AWS Certified Solutions Architect – Professional (SAP-C02)**

---

# 🤝 Contributing

Contributions are welcome.

If you'd like to improve documentation, add architecture diagrams, create new labs, or fix issues, feel free to open a Pull Request.

---

# ⭐ Support the Project

If this repository helps you learn AWS, consider giving it a **Star ⭐** to support the project and help others discover it.

---

# 📄 License

This project is licensed under the **MIT License**. </escape>
