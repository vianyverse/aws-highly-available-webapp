
# Highly Available Web Application on AWS

## Project Overview
This project demonstrates the deployment of a highly available web application using AWS services.

The application uses an Application Load Balancer to distribute incoming traffic across multiple EC2 instances. Auto Scaling maintains the required number of instances and CloudWatch monitors application infrastructure.

## AWS Services Used
- Amazon VPC
- Amazon EC2
- Application Load Balancer (ALB)
- Auto Scaling Group
- Amazon CloudWatch
- Amazon S3
- Internet Gateway
- Security Groups

## Architecture
The application is deployed across two Availability Zones.

- Internet users access the application through the Application Load Balancer.
- The Load Balancer distributes traffic to EC2 instances.
- Auto Scaling maintains two instances.
- CloudWatch monitors CPU utilization.
- Amazon S3 stores the website backup.

See the architecture diagram in the `architecture` folder.

## Key Features
- High availability across two Availability Zones
- Load balancing
- Automatic instance replacement
- CloudWatch monitoring and CPU alarm
- S3 backup with versioning enabled
- Security groups to control network traffic

## Project Structure

```text
aws-highly-available-webapp/
├── architecture/
├── documentation/
├── screenshots/
├── website/
└── README.md
```

## Website
The sample website is available in the `website` folder as `index.html`.

## Documentation
The detailed project report is available in the `documentation` folder.

## Learning Outcomes
- AWS networking and VPC configuration
- EC2 deployment
- Load balancing and Auto Scaling
- CloudWatch monitoring
- S3 backup and versioning
- High availability concepts

## Author
Cloud Computing Project

## Note
This project was created for learning and educational purposes.
