## Ex.4 Deployment and configuration of a Private Cloud  in AWS
```
NAME: PRAVESH N
REG NO: 212223230154
```
## Aim:
To set up of a Private Cloud  in AWS.

## Setting up of a private cloud in AWS:

Setting up a private cloud within AWS, also known as a Virtual Private Cloud (VPC),
involves creating a logically isolated virtual network that you can use to launch AWS
resources. This provides you with full control over your virtual networking environment,
including resource placement, connectivity, and security.
Amazon Virtual Private Cloud (Amazon VPC) gives you full control over your virtual
networking environment, including resource placement, connectivity, and security. Get
started by setting up your VPC in the AWS service console. Next, add resources to it such as
Amazon Elastic Compute Cloud (EC2) and Amazon Relational Database Service (RDS)
instances. Finally, define how your VPCs communicate with each other across accounts,
Availability Zones, or AWS Regions.

## Procedure:
## 1. Plan Your VPC:
## ● Determine your needs:
Define your use case, including application requirements, security needs, and
compliance standards.
## ● Plan IP address ranges:
Choose appropriate IP address ranges for your VPC and subnets to avoid conflicts.
## ● Select Availability Zones:
Decide which Availability Zones (AZs) you'll use for your resources, considering
redundancy and performance.
## ● Plan internet connectivity:
Determine if you need public internet access and how to configure it.
## ● Define security:
Plan your security groups, network ACLs, and access controls to ensure a secure
environment.

## 3. Create Your VPC:
Sign in to AWS Management Console: Access the VPC console and navigate to the VPC dashboard.
 Choose "Create VPC": Initiate the VPC creation process.
Configure VPC details: Enter the VPC name, CIDR block, Availability Zones, and
other necessary settings.
Create subnets: Define subnets within your VPC to isolate different parts of your
network.
Create route tables: Specify how traffic is routed within and outside the VPC.
 Create security groups: Define access control rules for your resources.

## 4. Deploying Resources:
Launch EC2 instances: Create and launch virtual machines within your VPC.
 Set up RDS instances: Deploy databases for your applications.
Configure networking: Connect your resources to the appropriate subnets, security
groups, and route tables.
Deploy other AWS services: Integrate other services like S3 for storage and Lambda for serverless computing.

## 5.Managing and Monitoring:
Use AWS CloudWatch: Monitor your VPC and resources for performance and
health.
Configure logging and auditing: Track access and activity within your VPC for
security and compliance.
Implement security best practices: Regularly review and update your security
configuration.
Scale and adjust as needed: Adjust your VPC infrastructure to meet changing
demands.

##  Output:

<img width="1141" height="1079" alt="Screenshot 2025-10-23 112636" src="https://github.com/user-attachments/assets/03e8afd4-acdb-429f-a119-6a4caaea4f49" />


<img width="1149" height="1079" alt="Screenshot 2025-10-23 112727" src="https://github.com/user-attachments/assets/fb00c71a-6f34-4624-bd22-2492093d3088" />

<img width="1148" height="1079" alt="Screenshot 2025-10-23 112737" src="https://github.com/user-attachments/assets/1e342682-8956-42cd-a7c1-161c6dc43a4f" />

<img width="1142" height="1019" alt="Screenshot 2025-10-23 113510" src="https://github.com/user-attachments/assets/91aadc30-717c-4998-b733-12d00bc4b2e4" />

<img width="1149" height="1025" alt="Screenshot 2025-10-23 113619" src="https://github.com/user-attachments/assets/019f38d0-8f63-40e9-af83-8cc55edd339e" />

<img width="1154" height="1079" alt="Screenshot 2025-10-23 114058" src="https://github.com/user-attachments/assets/4e36fc90-0739-4b24-bd5c-18488e007f88" />

<img width="1149" height="1071" alt="Screenshot 2025-10-23 114122" src="https://github.com/user-attachments/assets/429f8994-5c51-4be7-9dbc-7bcae59ff2ff" />


## Result:

Thus, a private cloud on AWS involves using VPCs has been created for  a dedicated, isolated network where we can manage our resources and control access according to our requirements.

