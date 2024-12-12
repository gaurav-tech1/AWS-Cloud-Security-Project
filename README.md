# AWS-Cloud-Security-Project
Description:
This repository contains the implementation of an AWS Cloud Security Project designed to secure resources for a fictional financial institution (Financial Bank). The project adheres to AWS best practices, the AWS Well-Architected Framework, and the principle of least privilege, ensuring a robust security posture across various AWS services. Key focus areas include securing Amazon S3 buckets, protecting VPCs, and leveraging AWS KMS for encryption, alongside continuous monitoring and logging of user activities.

Key Objectives:
Securing Amazon S3: The project configures bucket policies, enables versioning, and activates inventory logging and object-level logging to safeguard data and ensure compliance with security standards.
Securing VPCs: Security controls such as VPC flow logs, route table configurations, network ACLs, and firewall setups are implemented to optimize cost, restrict unauthorized access, and enhance network security while maintaining scalability and performance.
Data Encryption with AWS KMS: KMS customer-managed keys are used to encrypt sensitive data stored in S3, EC2 EBS volumes, and Secrets Manager, ensuring data confidentiality and integrity.
Monitoring & Logging: AWS CloudTrail, CloudWatch, and AWS Config are employed to log user activity, track configuration changes, and generate alerts for suspicious activity, providing visibility and ensuring compliance with internal security policies.
Additional Features:
Restricting access based on the principle of least privilege for different user groups such as Account Manager and Financial Advisor.
Enforcing compliance through continuous monitoring of AWS resources.
Setting up alerting and change management mechanisms to notify stakeholders of security-related events.
This project serves as a practical demonstration of how to implement cloud security best practices in AWS, focusing on securing critical infrastructure and sensitive data for financial institutions.
