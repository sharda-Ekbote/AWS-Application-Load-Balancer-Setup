AWS-Application-Load-Balancer-Setup

To configure an Application Load Balancer (ALB) to distribute incoming HTTP traffic across multiple EC2 web servers. 
By using a target group and health checks,you will ensure high availability and redundancy for a simple web application.



Architecture Components

**Application Load Balancer (ALB): Operates at the application layer (Layer 7) to route traffic based on content.

**Target Group: A logical grouping of EC2 instances that receive traffic from the load balancer.

**EC2 Instances: Two web servers (Server-1 and Server-2) running Apache (httpd).

**Security Groups: Firewall rules configured to allow public HTTP traffic on Port 80
