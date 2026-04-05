# aws-ec2cloud_automation-project

A scalable web server deployed using EC2 with security groups and public access configuration with cpu monitoring and amazon EventBridge 

This project demonstrates how to deploy and manage a cloud server using AWS EC2. 
It includes setting up a web server, configuring security, monitoring with CloudWatch, 
and automating instance start/stop using EventBridge to optimize cost.

# Features 
1. using EC2 for serverless virtual machines
2. using public configuration with http and ssl security groups
3. using cloud watch to monitor resources
4. using eventbridge fr scheduling automation over the resoure (EC2)



# Tech Stack 
AWS EC2 
linux ubuntu 
security group 
HTTP protocol 


# problem statmenet 
Many users launch cloud servers but fail to manage costs, monitor performance, 
or automate routine tasks. This project solves that by creating a system that 
is accessible, monitored, and automated.

# services used 
- AWS EC2 (Virtual Server)
- Security Groups (Firewall)
- Apache (Web Server)
- AWS CloudWatch (Monitoring)
- SNS (Notifications)
- EventBridge (Automation)

# steps performed 
1. Launched EC2 instance (Amazon Linux)
2. Configured Security Groups (SSH, HTTP)
3. Connected via SSH
4. Installed and started Apache server
5. Deployed a basic web page
6. Set up CloudWatch alarm for CPU utilization
7. Configured SNS for email alerts
8. Created EventBridge rules to automate start/stop

# key learnings 
- Understanding of cloud infrastructure setup
- Importance of security groups and access control
- Monitoring system behavior using CloudWatch
- Automating cloud operations to reduce manual effort and cost


# future improvements
- Add HTTPS using SSL certificate
- Use domain instead of public IP
- Implement load balancing
