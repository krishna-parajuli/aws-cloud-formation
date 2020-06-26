# aws-cloud-formation
trying out cloudformation script 

We have two provisioning file and two scripts to deploy.
## network.yaml
This file is responsible for the networking resources. We add the following as a result of creating stack using this template.
  - VPC
  - IGW
  - IGW attachment
  - Public Subnets(2)
  - Private Subnets(2)
  - NAT gateway Elastic IP (2)
  - NAT gateway in Public subnets (2)
  
  - Public Route Table
  - Default Public Route
  - Public Subnet Route Table Associations(2)
  
  - Private Route Table(2)
  - Default Private Route(2)
  - Private Subnet Route Table Association (2)

