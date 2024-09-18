<h1>AWS Three-Tier Architecture Project</h1>

<p>This project demonstrates the deployment of a scalable and secure web application using a three-tier architecture on AWS. It utilizes the following components:</p>

<ul>
    <li><strong>Application Load Balancer (ALB)</strong>: Distributes traffic across EC2 instances in the web tier.</li>
    <li><strong>Auto Scaling Group (ASG)</strong>: Manages the application tier to handle traffic spikes.</li>
    <li><strong>Amazon RDS</strong>: Provides persistent database storage.</li>
</ul>

<p>The architecture ensures high availability, fault tolerance, and security by:</p>

<ul>
    <li>Distributing resources across multiple availability zones.</li>
    <li>Using private subnets for sensitive data.</li>
    <li>Applying Security Groups for traffic control.</li>
</ul>

<p>The setup adheres to AWS best practices, making it resilient and scalable.</p>

