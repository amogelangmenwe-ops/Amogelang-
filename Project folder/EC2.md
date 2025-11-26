<img width="564" height="522" alt="image" src="https://github.com/user-attachments/assets/77bda727-c6e6-4369-a46a-4946a5a5ef8a" />


⚙️ Amazon EC2 Project
Overview

This project demonstrates how to deploy and manage a virtual server using Amazon EC2 (Elastic Compute Cloud). EC2 allows you to launch scalable, customizable virtual machines in the cloud, giving you full control over the operating system, software, security, and performance settings.

What This Project Covers

Launching an EC2 instance

Connecting via SSH or EC2 Instance Connect

Installing and configuring software (e.g., web server, app runtime)

Setting up security groups and inbound/outbound rules

Managing key pairs for secure access

Configuring instance storage and monitoring performance

Optional: Setting up a load balancer or auto scaling

Why EC2 Is Important

Amazon EC2 gives you flexible computing power without buying physical servers. It’s ideal for hosting websites, running applications, processing workloads, and creating development or testing environments. You can scale resources up or down as needed, only paying for what you use.

🧩 Challenges I Faced
1. Configuring Security Groups

At first, setting up the correct inbound and outbound rules was confusing. I had to troubleshoot blocked connections because ports weren’t open or rules were too restrictive. Understanding how security groups work was a learning curve.

2. SSH Connection Issues

Connecting to the EC2 instance through SSH wasn’t smooth in the beginning. I faced issues with key pairs, file permissions, and incorrect user names for different AMIs. It took time to figure out the correct approach for each instance type.

3. Managing Permissions (IAM Roles)

Assigning the right IAM roles and permissions for accessing other AWS services was tricky. I had to learn how to grant minimum required permissions without accidentally blocking needed access.

4. Instance Configuration & Software Setup

Installing and configuring software on the instance took longer than expected. Some packages failed to install due to missing dependencies or outdated repositories, so I had to troubleshoot and fix them manually.

5. Cost Management Awareness

Since EC2 is billed by usage, I had to be careful about leaving instances running. Learning how to monitor cost and shut down resources properly was an important part of the process.

6. Understanding Elastic IP and Networking

Networking concepts like Elastic IPs, VPCs, subnets, and routing initially felt overwhelming. Getting everything to work together correctly required research and trial-and-error.
