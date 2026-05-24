## AWS Application Load Balancer with Auto Scaling Group Project

Designed and implemented a scalable and highly available web infrastructure on AWS using EC2, Application Load Balancer (ALB), Target Groups, and Auto Scaling Groups.

### Project Overview

* Created multiple Ubuntu EC2 instances configured with Nginx web server.
* Implemented path-based routing using Application Load Balancer.
* Configured separate Target Groups for different application paths such as `/green/` and `/red/`.
* Set up health checks to monitor instance availability and traffic routing.
* Attached EC2 instances to dedicated Target Groups.
* Configured Security Groups with inbound rules for HTTP and SSH access.
* Created and configured an Auto Scaling Group using Launch Templates to automatically maintain desired instance capacity.
* Verified load balancing functionality through ALB DNS endpoints and health monitoring.

### AWS Services Used

* Amazon EC2
* Application Load Balancer (ALB)
* Target Groups
* Auto Scaling Groups
* Launch Templates
* Security Groups
* Amazon VPC
* CloudWatch Monitoring

### Key Features Implemented

* Path-based routing
* Dynamic traffic distribution
* Automatic instance scaling
* Health check monitoring
* High availability architecture
* Scalable web server deployment

### Technical Skills Demonstrated

* AWS Infrastructure Management
* Linux Administration
* Nginx Configuration
* Networking and Security
* Load Balancing
* Auto Scaling Configuration
* Troubleshooting and Debugging
* Cloud Architecture Design

### Architecture Flow

Client Request → Application Load Balancer → Target Groups → EC2 Instances running Nginx

### Outcome

Successfully deployed a scalable AWS web infrastructure capable of routing traffic based on URL paths, distributing requests across multiple EC2 instances, and automatically scaling resources based on demand.

<img width="1851" height="853" alt="Screenshot From 2026-05-24 21-29-42" src="https://github.com/user-attachments/assets/ef8f09b0-5d5d-4619-83f7-d3b83055bac6" />
<img width="1851" height="853" alt="Screenshot From 2026-05-24 21-29-32" src="https://github.com/user-attachments/assets/68f620e8-7a2d-487d-ae65-cb3baec386b5" />
