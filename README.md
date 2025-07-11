# AWS-WordPress-Deployment


## Overview
Deployed a highly available WordPress website on AWS using:
- EC2
- RDS (MySQL)
- S3 (for backups)
- Route53 (Domain management)
- Auto Scaling and Load Balancer

## Deployment Architecture
1. Launch EC2 instance (Amazon Linux 2)
2. Install Apache, PHP, and MySQL client.
3. Connect EC2 instance to RDS instance.
4. Configure security groups for HTTP(80), HTTPS(443), and SSH(22)
5. Attach Elastic IP to EC2
6. Setup Route53 hosted zone and create A record pointing to Elastic IP.
7. Install WordPress on EC2 and connect with RDS database.
8. Enable Auto Scaling Group and Load Balancer for high availability.

## Outcome
- 99.9% uptime
- Fault-tolerant and scalable infrastructure
- Secure VPC configuration

