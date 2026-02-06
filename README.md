# AWS Labs

AWS Cloud Foundations – Hands-On Security Labs

Overview

This repository documents hands-on AWS labs completed to build a practical foundation in cloud infrastructure, security and governance.

The focus is on:

* access control and identity management

* secure deployment basics

* monitoring and operational visibility

* audit-style security thinking

Scope & Level

Level: Entry-level / undergraduate / placement

Focus: Security fundamentals, governance and decision-making

Not included: Advanced automation, IaC, or production architectures



Labs Completed:


1. IAM & Access Control

Objective: To understand how identity, authentication, and authorisation are managed in AWS.

What I did

* Created IAM users and roles

* Applied policies following the principle of least privilege

* Explored how permissions affect service access

Key learning

- Misconfigured access control is a major security risk

- Role separation reduces blast radius

- IAM is foundational for security, audit and compliance
  

2. EC2 Deployment & Monitoring

Objective: To deploy a basic compute resource and understand operational visibility.

What I did

* Launched and configured an EC2 instance

* Configured security groups to restrict traffic

* Reviewed health checks and CloudWatch metrics

Key learning

- Security configuration is required even for simple deployments

- Monitoring supports availability and security

- Visibility enables early detection and response
  

3. S3 Storage & Permissions

Objective: To understand secure data storage and access management.

What I did

* Created S3 bucket
* Enabled versioning to protect against accidental object deletion

  <img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/8b234a65-7bd2-4660-a96c-2ffdfef82b9b" />


* Configured bucket policies and permissions

 <img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/5fe8d766-920b-4546-b8cb-6d345dd8b5f8" />
  <img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/62e25fe4-28fc-4522-aec9-804018654932" />


* Reviewed risks of public exposure

Key learning

- Storage misconfiguration is a common cause of data leakage

- Secure defaults must be verified, not assumed

- Regular permission review is essential
  

4. Basic Security Audit

Objective: To apply an audit-style mindset to identify cloud security risks.

What I did

* Reviewed IAM, EC2 and S3 configurations

* Identified over-privileged access and weaknesses

* Considered documentation, prioritisation and escalation

Key learning

- Security assurance relies on evidence

- Risks must be clearly articulated and prioritised

- Governance is essential in regulated environments


Risk Reflection & Improvements

Key risks identified: 

* Overly broad IAM permissions

* Inadequate monitoring

* Storage exposure through misconfiguration


Potential improvements:

* Tighter role-based access reviews

* More consistent alerting

* Structured, periodic audits


Skills Demonstrated

- AWS IAM (users, roles, policies, least privilege)

- EC2 deployment and security groups

- S3 access control

- Basic cloud security auditing

- Risk identification and prioritisation

- Security governance awareness

Final Reflection:

These labs reinforced the importance of embedding security and governance early in cloud systems.
Rather than aiming for “perfect security”, the focus was on defensible, documented decisions, aligned with practices used in regulated and safety-critical environments.
