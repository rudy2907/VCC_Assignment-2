# VCC_Assignment-2

In this assignment we were required to use GCP cloud to create a Virtual Machine to leverage autoscaling and security.

Architecture Diagram explained

A scalable, safe, and effective cloud infrastructure is guaranteed by the GCP Auto-Scaling VM Deployment Architecture.  The program is first accessed by users through HTTP/HTTPS queries that are routed via a global load balancer.  To balance the load and improve performance, this load balancer divides traffic among several Virtual Machine (VM) instances in a Managed Instance Group (MIG). Depending on CPU usage, the MIG dynamically modifies the number of virtual machine instances. Auto-scaling starts more instances if CPU use exceeds a predetermined threshold. On the other hand, extra instances are stopped when demand declines in order to save money. To guarantee consistent deployment parameters, these instances are set up using an instance template.  A Virtual Private Cloud (VPC) with firewall rules that only permit necessary communication, such HTTP (Port 80) and HTTPS (Port 443), is used to enforce security. Role-based access control is assigned via Identity and Access Management (IAM), guaranteeing that only authorized users have access to resources. Logs Explorer monitors instance activity, and Monitoring Alerts alert administrators to excessive CPU utilization so that scaling measures can be taken.  This architecture is perfect for applications that need dynamic scalability and continuous uptime since it offers high availability, security, and cost effectiveness.

