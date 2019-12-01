AWS PrivateLink Demo:
=====================

Here we create 3 AWS Cloudformation stacks.
First, for creating an ECR repository.
Second, containing a VPC and 2 private subnets, no igw, an internal load balancer, with ECS cluster, cloudwatch logs, with AWS privatelinks for s3, cloudwatch and ECR to allow these AWS services to be reachable without using an IGW and going over the public internet.
Third, containing the ECS service and tasks.

Enjoy!!
