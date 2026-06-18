# AWS Core Services (Deep Dive)

This subdirectory contains files, architecture diagrams, and deployment logs for AWS Core Services tasks.

## 📋 Task Checklist & Progress

- [ ] **Task 1: AWS Account Setup**
  * **Objective**: Create a secure AWS foundation — MFA on root, IAM admin user, and AWS Organizations structure.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-01-aws-account-setup/](./tasks/task-01-aws-account-setup/)`
- [ ] **Task 2: IAM Deep Dive (Part of Account Setup)**
  * **Objective**: Create groups, attach least-privilege policies, and set up a role for EC2.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-02-iam-deep-dive-part-of-account/](./tasks/task-02-iam-deep-dive-part-of-account/)`
- [ ] **Task 3: EC2 + ALB + Auto Scaling**
  * **Objective**: Deploy a Node.js app on EC2 behind an ALB with Auto Scaling (min 2, max 10), targeting 60% CPU.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-03-ec2-alb-auto-scaling/](./tasks/task-03-ec2-alb-auto-scaling/)`
- [ ] **Task 4: (Chapter Extension): 3-Tier VPC Design and Deployment**
  * **Objective**: Design and deploy a 3-tier VPC: public (ALB), private (app), isolated (DB) across 3 AZs.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-04-chapter-extension-3-tier-vpc-design/](./tasks/task-04-chapter-extension-3-tier-vpc-design/)`
- [ ] **Task 5: RDS Aurora MySQL Setup**
  * **Objective**: Set up RDS Aurora MySQL with Multi-AZ, read replica, automated backup, encryption at rest.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-05-rds-aurora-mysql-setup/](./tasks/task-05-rds-aurora-mysql-setup/)`
- [ ] **Task 6: CloudFront Distribution in Front of S3**
  * **Objective**: Build a CloudFront distribution backed by S3 with OAC, configure cache behaviours, and add security headers via Lambda@Edge.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-06-cloudfront-distribution-in-front-of-s3/](./tasks/task-06-cloudfront-distribution-in-front-of-s3/)`
- [ ] **Task 7: Cost Dashboard**
  * **Objective**: Enable Cost Explorer, set up budgets with alerts at 50%, 80%, and 100%.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-07-cost-dashboard/](./tasks/task-07-cost-dashboard/)`
- [ ] **Task 8: EventBridge Rule for EC2 State Changes**
  * **Objective**: Create an EventBridge rule that triggers Lambda on EC2 state changes and sends a Slack notification.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-08-eventbridge-rule-for-ec2-state-changes/](./tasks/task-08-eventbridge-rule-for-ec2-state-changes/)`
- [ ] **Task 9: Lambda Triggered by S3 — Image Processor**
  * **Objective**: Create a Lambda function triggered by S3 put events that processes images and saves thumbnails.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-09-lambda-triggered-by-s3-image-processor/](./tasks/task-09-lambda-triggered-by-s3-image-processor/)`
- [ ] **Task 10: ECS Fargate Service with ALB**
  * **Objective**: Deploy an ECS Fargate service with ALB, service discovery, and auto scaling.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-10-ecs-fargate-service-with-alb/](./tasks/task-10-ecs-fargate-service-with-alb/)`
- [ ] **Task 11: CloudFormation 3-Tier Architecture**
  * **Objective**: Deploy the full 3-tier architecture (ALB, ASG, RDS) using CloudFormation.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-11-cloudformation-3-tier-architecture/](./tasks/task-11-cloudformation-3-tier-architecture/)`
- [ ] **Task 12: Implement IMDSv2 on All EC2 Instances**
  * **Objective**: Enforce IMDSv2 on all running EC2 instances and verify metadata service security.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-12-implement-imdsv2-on-all-ec2-instances/](./tasks/task-12-implement-imdsv2-on-all-ec2-instances/)`
- [ ] **Task 13: (See Practical Task 11 in Chapter 12 for the full CLI command)**
  * **Objective**: Complete the hands-on exercise detailed in the handbook.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-13-see-practical-task-11-in-chapter/](./tasks/task-13-see-practical-task-11-in-chapter/)`

---
[⬅️ Back to Cloud Engineering Module](../README.md)
