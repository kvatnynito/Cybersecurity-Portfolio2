# Cybersecurity Portfolio 2 — AWS Cloud Security & Engineering

## Overview

This portfolio is a planned AWS-focused cybersecurity and cloud engineering portfolio.

The purpose of Portfolio 2 is to build cloud security and cloud engineering skills after completing the foundational homelab work in Portfolio 1. This portfolio will focus on AWS account security, IAM, secure cloud networking, logging, monitoring, S3 security, EC2 hardening, vulnerability management, automation, and Infrastructure as Code.

Portfolio 2 is designed to show hands-on growth from traditional infrastructure security into AWS cloud security and cloud engineering.

---

## Status

**Planned**

This portfolio has not been implemented yet.

The repositories in this portfolio are currently structured as planned projects and templates. Implementation will begin after the required Portfolio 1 homelab foundation is completed.

Current status:

- [ ] Portfolio 1 foundation completed
- [ ] AWS account security started
- [ ] AWS VPC architecture started
- [ ] AWS logging and monitoring started
- [ ] AWS S3 security started
- [ ] AWS EC2 hardening started
- [ ] AWS automation and IaC started
- [ ] Final Portfolio 2 documentation completed

---

## Portfolio Direction

Portfolio 1 focuses on building a local cybersecurity homelab using Proxmox, pfSense, network segmentation, Active Directory, Splunk, and vulnerable systems.

Portfolio 2 expands those infrastructure and security concepts into AWS.

The planned progression is:

1. Secure the AWS account
2. Design secure AWS networking
3. Build logging, monitoring, and detection visibility
4. Secure S3 cloud storage
5. Harden and assess EC2 workloads
6. Automate AWS workflows and introduce Infrastructure as Code

---

## Portfolio 1 to Portfolio 2 Progression

| Portfolio 1 Concept | Portfolio 2 AWS Equivalent |
|---|---|
| Proxmox virtualization | AWS cloud infrastructure |
| pfSense firewalling | Security groups and NACLs |
| LAN segmentation | VPC and subnet segmentation |
| Active Directory environment | IAM and cloud identity concepts |
| Splunk log analysis | CloudTrail, CloudWatch, GuardDuty |
| Vulnerable systems | EC2 workload assessment |
| Manual documentation | Automation and Infrastructure as Code |

---

## Project Repositories

### 1. AWS Account Security & IAM

Repository: [P2-1-aws-account-security-iam](https://github.com/kvatnynito/P2-1-aws-account-security-iam)

Planned focus:

- AWS account security
- Root account MFA
- IAM users, groups, roles, and policies
- Least privilege
- Billing alerts
- AWS Budgets
- CloudTrail baseline logging

Purpose:

Secure the AWS account foundation before deploying cloud infrastructure.

---

### 2. AWS Secure VPC Architecture

Repository: [P2-2-aws-secure-vpc-architecture](https://github.com/kvatnynito/P2-2-aws-secure-vpc-architecture)

Planned focus:

- Amazon VPC design
- Public and private subnets
- Route tables
- Internet Gateway concepts
- Security groups
- Network ACLs
- Cloud network segmentation
- Cost-conscious network design

Purpose:

This project translates local network segmentation concepts from Portfolio 1 into AWS cloud networking - Build the AWS network.

---

### 3. AWS Logging, Monitoring & Detection

Repository: [P2-3-aws-logging-monitoring-detection](https://github.com/kvatnynito/P2-3-aws-logging-monitoring-detection)

Planned focus:

- AWS CloudTrail
- Amazon CloudWatch
- Amazon GuardDuty
- Amazon EventBridge
- Cloud investigation workflow
- Detection notes
- Alerting concepts
- Logging cost control

Purpose:

This project develops AWS-native visibility and detection workflows for cloud security monitoring - Turn on logging/monitoring.

---

### 4. AWS S3 Security & Data Protection

Repository: [P2-4-aws-s3-security-data-protection](https://github.com/kvatnynito/P2-4-aws-s3-security-data-protection)

Planned focus:

- Amazon S3 security
- Public access controls
- Bucket policies
- IAM access control
- Encryption
- Versioning
- Access logging concepts
- Misconfiguration review and remediation

Purpose:

This project focuses on securing cloud object storage and reducing data exposure risk - Secure S3 storage.

---

### 5. AWS EC2 Hardening & Vulnerability Management

Repository: [P2-5-aws-ec2-hardening-vulnerability-management](https://github.com/kvatnynito/P2-5-aws-ec2-hardening-vulnerability-management)

Planned focus:

- EC2 workload hardening
- SSH access control
- Security group exposure review
- Patch management
- Vulnerability assessment
- AWS Systems Manager concepts
- Amazon Inspector concepts
- Remediation documentation

Purpose:

This project applies endpoint hardening and vulnerability management concepts to AWS-hosted workloads - Harden EC2 workloads.

---

### 6. AWS Automation & Infrastructure as Code

Repository: [P2-6-aws-automation-iac](https://github.com/kvatnynito/P2-6-aws-automation-iac)

Planned focus:

- AWS CLI
- Bash automation
- Python and boto3
- Terraform basics
- Security validation checks
- Cleanup automation
- Infrastructure as Code
- Cost-conscious automation

Purpose:

This project introduces automation and repeatable cloud infrastructure workflows - Automate everything.

---

## Planned Repository Sequence

The projects are intentionally ordered to follow a realistic cloud build path:

| Order | Repository | Reason |
|---|---|---|
| 1 | AWS Account Security & IAM | Secure the account before deploying resources |
| 2 | AWS Secure VPC Architecture | Design the cloud network foundation |
| 3 | AWS Logging, Monitoring & Detection | Establish visibility and investigation workflows |
| 4 | AWS S3 Security & Data Protection | Secure cloud object storage |
| 5 | AWS EC2 Hardening & Vulnerability Management | Harden and assess cloud workloads |
| 6 | AWS Automation & Infrastructure as Code | Automate validation, deployment, and cleanup |

---

## Planned Skills Developed

This portfolio is intended to build hands-on experience with:

- AWS account security
- AWS IAM
- Least-privilege access
- AWS billing and cost controls
- Amazon VPC
- Public and private subnet design
- Route tables
- Security groups
- Network ACLs
- AWS CloudTrail
- Amazon CloudWatch
- Amazon GuardDuty
- Amazon EventBridge
- Amazon S3 security
- Bucket policies
- Encryption and versioning
- Amazon EC2 hardening
- Patch management
- Vulnerability management
- AWS Systems Manager concepts
- AWS CLI
- Bash scripting
- Python/boto3
- Terraform basics
- Infrastructure as Code
- Cloud security documentation

---

## AWS Services Covered

Planned AWS services and features include:

| AWS Service / Feature | Portfolio Use |
|---|---|
| AWS IAM | Identity and access management |
| AWS Budgets | Cost monitoring and billing alerts |
| AWS CloudTrail | Account activity logging |
| Amazon VPC | Cloud network design |
| Subnets | Network segmentation |
| Route Tables | Traffic control |
| Internet Gateway | Public internet routing |
| Security Groups | Instance-level traffic control |
| Network ACLs | Subnet-level traffic filtering |
| Amazon CloudWatch | Logs, metrics, and alarms |
| Amazon GuardDuty | Threat detection |
| Amazon EventBridge | Event routing and alerting concepts |
| Amazon S3 | Cloud object storage |
| AWS KMS | Encryption concept review |
| Amazon EC2 | Cloud compute workload |
| AWS Systems Manager | EC2 management and patching concepts |
| Amazon Inspector | Vulnerability assessment concepts |
| AWS CLI | Command-line resource management |
| Terraform | Infrastructure as Code |

---

## Security and Cost-Control Principles

This portfolio will follow the following principles:

- Do not commit secrets or credentials
- Do not commit AWS access keys
- Do not commit private SSH keys
- Redact screenshots before uploading
- Use harmless test data only
- Configure billing alerts before deploying resources
- Use one AWS region where possible
- Avoid unnecessary paid services
- Avoid NAT Gateway unless intentionally required
- Stop or delete unused EC2 instances
- Delete unused EBS volumes and snapshots
- Review billing after lab sessions
- Document cleanup steps

---

## Relationship to AWS Solutions Architect Associate

This portfolio is designed to support practical learning for the **AWS Certified Solutions Architect – Associate** certification.

The portfolio is not a certification study guide.

Instead, it is a hands-on project set that supports AWS architecture and security understanding through practical labs, documentation, and planned implementation.

Relevant AWS SAA areas include:

- IAM
- VPC design
- Subnetting
- Route tables
- Security groups
- S3 security
- EC2 workload placement
- Monitoring and logging
- Cost-aware design
- Resilient and secure architecture
- Infrastructure automation basics

---

## Career Alignment

This portfolio is intended to support entry-level growth toward roles such as:

- Cloud Security Analyst
- Junior Cloud Engineer
- Cloud Support Associate
- Security Analyst with cloud responsibilities
- SOC Analyst with AWS exposure
- Infrastructure Security Analyst
- Cloud Operations Analyst

The goal is to show practical AWS security and engineering growth, not just certification study.

---

## Resume Positioning

After implementation, this portfolio may support resume bullets such as:

> Built an AWS cloud security portfolio covering IAM, VPC segmentation, CloudTrail logging, CloudWatch monitoring, GuardDuty detection review, S3 data protection, EC2 hardening, vulnerability management, and automation.

> Designed secure AWS lab architectures using least-privilege IAM, public/private subnet segmentation, security groups, logging controls, and cost-aware resource management.

> Automated AWS resource inventory, security validation, and cleanup workflows using AWS CLI, Bash, Python/boto3, and Terraform basics.

---

## Implementation Status

This portfolio is currently in the planning stage.

No project should be represented as completed until implementation has been performed, documented, and validated.

Each repository will be updated with screenshots, notes, evidence, lessons learned, and final summaries as work begins.

---

## Portfolio Summary

Portfolio 2 is planned as an AWS-focused cloud security and engineering portfolio.

It builds on the local infrastructure and security foundation from Portfolio 1 and expands into AWS cloud architecture, monitoring, storage security, workload hardening, vulnerability management, and automation.

The long-term goal is to demonstrate practical readiness for cloud security, cloud engineering, and security analyst roles with AWS exposure.
