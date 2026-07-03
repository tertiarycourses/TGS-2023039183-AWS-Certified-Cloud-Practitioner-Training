# Learner Guide - AWS Certified Cloud Practitioner Training

> Course: AWS Certified Cloud Practitioner Training  
> Course Code: TGS-2023039183  
> Registration: https://www.tertiarycourses.com.sg/wsq-aws-certified-cloud-practitioner-training.html

This learner guide supports a practical AWS Certified Cloud Practitioner course. It is designed for learners building foundational AWS cloud literacy and preparing for the AWS Certified Cloud Practitioner exam.

## Learning Outcomes

By the end of the labs, you should be able to:

- Explain AWS Cloud concepts, regions, availability zones, edge locations, and global services.
- Describe the shared responsibility model and AWS security foundations.
- Compare IAM users, groups, roles, and policies.
- Match compute services such as EC2, Lambda, containers, and Elastic Beanstalk to use cases.
- Compare storage services such as S3, EBS, EFS, FSx, and AWS Backup.
- Select database and analytics services such as RDS, Aurora, DynamoDB, Redshift, Athena, Glue, and QuickSight.
- Explain VPC, subnets, route tables, security groups, load balancing, CloudFront, and Route 53.
- Use AWS billing, pricing, monitoring, budget, and support tools.
- Apply Well-Architected, migration, disaster recovery, and sustainability concepts at a foundational level.
- Prepare for exam-style questions across cloud concepts, security, services, billing, pricing, and support.

## Recommended Setup

1. Use a trainer-provided AWS account where available.
2. If using your own account, enable MFA and create a budget alert before starting labs.
3. Create a working folder named `TGS-2023039183-AWS-CCP-Labs`.
4. Save screenshots and notes for each lab.
5. Delete temporary resources after each hands-on exercise.

## Cost Safety Rules

- Do not create paid resources unless your trainer instructs you to.
- Prefer Free Tier eligible resources.
- Stop or terminate EC2 instances after practice.
- Delete S3 objects and buckets created for labs.
- Review Billing and Cost Management after hands-on labs.
- Keep a budget alert active during the course.

## Lab 1 - AWS Account Setup, Console Tour, and Cloud Concepts

### Objectives

- Sign in safely.
- Navigate the AWS Management Console.
- Understand regions, availability zones, and edge locations.
- Review shared responsibility and Well-Architected basics.

### Procedure

1. Sign in to the AWS account assigned by your trainer.
2. Confirm the account and region.
3. Use the region selector to compare regional views.
4. Identify examples of regional services and global services.
5. Review AWS global infrastructure concepts.
6. Open AWS Well-Architected documentation or tool.
7. Record the six pillars.
8. Review the shared responsibility model.
9. Create a table with AWS responsibilities and customer responsibilities.
10. Review the AWS Certified Cloud Practitioner exam overview.
11. Save your notes.

### Checkpoint

You should be able to explain region, availability zone, edge location, shared responsibility, and Well-Architected concepts.

## Lab 2 - IAM, Security, and Shared Responsibility

### Objectives

- Understand IAM identities and permissions.
- Review MFA and least privilege.
- Locate CloudTrail events.
- Map security services to use cases.

### Procedure

1. Open IAM.
2. Review account security recommendations.
3. Verify MFA where permitted.
4. Compare root user, IAM user, group, role, and policy.
5. Open an AWS managed policy and review its JSON structure.
6. Identify effect, action, and resource.
7. Open CloudTrail Event history.
8. Review a recent console event.
9. Locate Security Hub, GuardDuty, and Inspector for service awareness.
10. Save security notes.

### Checkpoint

You should be able to describe IAM basics, least privilege, MFA, CloudTrail, and security service use cases.

## Lab 3 - Compute Services

### Objectives

- Compare AWS compute services.
- Understand EC2 and Lambda basics.
- Review containers and elasticity.
- Match compute choices to scenarios.

### Procedure

1. Open EC2.
2. Review instance types, AMIs, and the EC2 dashboard.
3. Launch a Free Tier eligible instance only if permitted.
4. Review instance state and monitoring.
5. Terminate the instance before leaving the lab.
6. Open Lambda and review function concepts.
7. Open ECS and EKS for container awareness.
8. Review Auto Scaling and elasticity.
9. Create a comparison table for EC2, Lambda, ECS, EKS, and Elastic Beanstalk.
10. Save your notes.

### Checkpoint

You should be able to choose a compute service for simple workload scenarios.

## Lab 4 - Storage Services

### Objectives

- Compare object, block, and file storage.
- Practice basic S3 operations if permitted.
- Review storage classes and lifecycle policies.
- Understand backup options.

### Procedure

1. Open S3.
2. Create a bucket only if permitted.
3. Keep Block Public Access enabled.
4. Upload a sample object.
5. Review object properties and versioning.
6. Review lifecycle rules and storage classes.
7. Open EC2 Volumes for EBS awareness.
8. Open EFS and FSx service pages.
9. Open AWS Backup.
10. Create a storage comparison table.
11. Delete any S3 objects and buckets created.
12. Save your notes.

### Checkpoint

You should be able to explain S3, EBS, EFS, FSx, and AWS Backup use cases.

## Lab 5 - Databases and Analytics

### Objectives

- Compare managed database services.
- Identify relational, NoSQL, cache, warehouse, and analytics services.
- Review backup and availability concepts.
- Match services to business scenarios.

### Procedure

1. Open RDS and review engine options.
2. Review Multi-AZ, read replica, backup, and patching concepts.
3. Open Aurora and note how it relates to RDS.
4. Open DynamoDB and review table and key concepts.
5. Open ElastiCache, Redshift, Athena, Glue, and QuickSight.
6. Create a selection table for OLTP, NoSQL, cache, warehouse, ad hoc query, ETL, and BI use cases.
7. Note which services are serverless or managed.
8. Save your notes.

### Checkpoint

You should be able to choose a database or analytics service for common foundational scenarios.

## Lab 6 - Networking and Content Delivery

### Objectives

- Understand VPC basics.
- Compare security groups and network ACLs.
- Review load balancing, CDN, and DNS services.
- Draw a simple cloud network.

### Procedure

1. Open VPC.
2. Review VPCs, subnets, route tables, internet gateways, and NAT gateways.
3. Review security group rules.
4. Compare security groups and network ACLs.
5. Draw a simple VPC with public and private subnets.
6. Open Elastic Load Balancing.
7. Open CloudFront and review distribution concepts.
8. Open Route 53 and review hosted zones and DNS record concepts.
9. Save your notes.

### Checkpoint

You should be able to explain VPC, subnet, route, security group, load balancer, CDN, and DNS basics.

## Lab 7 - Monitoring, Pricing, Billing, Budgets, and Support

### Objectives

- Review monitoring and auditing tools.
- Create cost awareness artifacts.
- Use AWS Pricing Calculator.
- Compare support plans.

### Procedure

1. Open CloudWatch and review metrics, alarms, logs, and dashboards.
2. Open CloudTrail and review event history.
3. Open AWS Health Dashboard.
4. Open Billing and Cost Management.
5. Review Cost Explorer if enabled.
6. Create a budget alert only if permitted.
7. Open AWS Pricing Calculator.
8. Create a simple estimate.
9. Compare Savings Plans and Reserved Instances at a high level.
10. Compare support plans.
11. Save your notes.

### Checkpoint

You should be able to explain tools for monitoring, audit, billing, budgeting, cost estimation, and support.

## Lab 8 - Architecture, Migration, Sustainability, and Exam Review

### Objectives

- Apply Well-Architected thinking.
- Map migration and disaster recovery services.
- Review sustainability concepts.
- Complete timed practice.

### Procedure

1. Review the Well-Architected pillars.
2. Choose a simple workload.
3. Map AWS services to compute, storage, database, networking, security, monitoring, and cost.
4. Identify reliability, security, and cost optimization improvements.
5. Review Migration Hub, Application Migration Service, and Database Migration Service.
6. Review disaster recovery strategies.
7. Review sustainability practices.
8. Complete a timed 30-question practice set.
9. Mark weak topics by exam domain.
10. Create a final revision plan.

### Checkpoint

You should be ready to explain AWS Cloud Practitioner concepts and answer foundational exam-style questions.

## Final Submission Checklist

- Lab notes or screenshots
- Shared responsibility table
- Compute, storage, database, networking, and support comparison tables
- Budget or Pricing Calculator evidence
- Architecture review notes
- Timed practice score
- Weak-topic revision plan

## Suggested Course Flow

| Segment | Focus | Labs |
| --- | --- | --- |
| Segment 1 | Cloud concepts, account setup, IAM, security | Labs 1-2 |
| Segment 2 | Compute, storage, database, networking services | Labs 3-6 |
| Segment 3 | Billing, monitoring, support, architecture, exam review | Labs 7-8 |

## Clean Up

1. Terminate EC2 instances created for labs.
2. Delete S3 buckets and objects created for labs.
3. Delete temporary Lambda functions if created.
4. Keep budget alerts active until the trainer confirms cleanup.
5. Save your notes for final revision.
