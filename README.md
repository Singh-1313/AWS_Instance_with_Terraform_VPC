# Terraform : Create AWS instance with custom created VPC

A list of all the resources that need to be created in order to run an EC2 instance inside a virtual private network, as this will help us understand better.

-> VPC 

-> VPC’s subnet 

-> VPC has an associated Internet gateway.

-> The route, which is a part of VPC, directs the traffic to IG. 

-> To make our subnet a public subnet, we need to associate a routing table with it. 

-> VPC’s security group. 

-> For SSH access, a key pair is used. 

-> Within our public subnet, we have an EC2 instance with a security group and a generated key pair. 

# Commands used:

-> terraform init 

-> terraform plan 

-> terraform apply 

-> terraform destroy 


# Files used:

-> Provider.tf

-> Variable.tf

-> terraform.tf
