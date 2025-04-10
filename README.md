# 🛡️ AWS VPC and Website Deployment

Designed and implemented a secure, scalable, and high-availability Virtual Private Cloud (VPC) architecture on AWS for website deployment.

## 🛠️ Tools & Services Used
- Amazon VPC
- EC2 (Elastic Compute Cloud)
- Security Groups
- NAT Gateway
- Route Tables
- Application Load Balancer

## 🌐 Architecture Overview

- **VPC Configuration**:  
  Created a custom VPC with multiple **public** and **private subnets** across different availability zones for high availability and isolation.

- **Subnet Management**:  
  Public subnets used for web-facing services; private subnets for backend and internal components.

- **EC2 Instances**:  
  Launched and configured EC2 instances in respective subnets for hosting the application and web services.

- **Security**:  
  Applied **Security Groups** to control inbound/outbound traffic and enforce least privilege access.

- **Routing & Internet Access**:  
  Configured **route tables** for traffic flow and **NAT Gateway** for secure internet access from private subnets.

- **Load Balancing**:  
  Deployed an **Application Load Balancer (ALB)** to distribute traffic efficiently across EC2 instances, ensuring fault tolerance and scalability.

## 🚀 Deployment Outcome
- Fully functional and publicly accessible website hosted on AWS
- Enhanced network security and performance
- Modular design ready for scaling and future integrations

---

> This project demonstrates core networking skills and secure infrastructure deployment using AWS cloud-native tools.
