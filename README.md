# 3_Tier_Architecture
A Cloud formation template that creates a 3-tier architecture

This AWS Cloudformation template deploys a 3-tier architecture in the eu-west-1 region
  Resources created
  2 public subnets for web apps
  1 public subnet for bastion host
  2 private subnets for hosting applications and talk to the bastion host public subnet
  2 private subnet for hosting the database
  2 Application load balancers, 1 ALB in public subnet and the other in private subnet
  1 internet gateway
  1 natgateway in Bastion host public subnet
