🚀 AWS Hands-On Lab Project: Implementing an Advance Application Load Balancer (ALB)

I gained hands-on experience implementing an Application Load Balancer (ALB) on Amazon Web Services (AWS) to distribute incoming web traffic across multiple EC2 instances.

🤖 Objective:

To improve application availability and distribute incoming HTTP/HTTPS traffic across three EC2 instances using an AWS Application Load Balancer.

🛠️ Step-by-Step Implementation

Step 1: Create a Security Group

• Open the Amazon EC2 Dashboard.

• Create a new security group.

• Configure inbound rules for SSH (22), HTTP (80), and HTTPS (443), as required.

• Use appropriate source restrictions for secure access.


Step 2: Launch Three EC2 Instances

• Launch three Amazon Linux EC2 instances.

• Attach the required security group.

• Configure the instances with the necessary web server setup using user data.

• Ensure each instance can serve web traffic.


Step 3: Create a Target Group

• Navigate to EC2 → Target Groups.

• Create a target group for the instances.

• Select the appropriate target type and HTTP protocol.

• Register all three EC2 instances.

• Configure health checks and create the target group.


Step 4: Create an Application Load Balancer:

• Navigate to EC2 → Load Balancers and select Application Load Balancer.

• Enter a load balancer name and choose the internet-facing scheme if public access is required.

• Select the required Availability Zones and subnets.

• Attach a suitable security group.

• Configure an HTTP listener on port 80 and forward traffic to the target group.

• Create the load balancer and verify that the targets become healthy.


🎯 Key Learning Outcomes:

• Understanding how an Application Load Balancer works.

• Distributing incoming requests across multiple EC2 instances.

• Configuring target groups and health checks.

• Understanding listeners, security groups, and Availability Zones.

• Learning how load balancing supports application availability and scalability.


💡Real-World Use Case

• When a website receives requests from many users, an Application Load Balancer can distribute traffic across multiple backend servers instead of sending every request to a single server. 

• This helps improve availability and supports scalable web applications.


📌 AWS Services Used:

Amazon EC2 | Application Load Balancer (ALB) | Target Groups | Security Groups | Availability Zones

The running process check it in linkedin site 🔗 www.linkedin.com/in/divya-priya2026
