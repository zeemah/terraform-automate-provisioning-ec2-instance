# automate provisioing ec2 with terraform 

## overview
I'm using Terraform config file & Terraform syntax to create resources, data sources and variables

* Provision an ec2 instance on AWS infrastructure
* Run nginx docker container on ec2 instance

### Prequisite before creating the ec2 instance

* Provision AWS infrastructure first. 
*1-* create custom VPC
*2-* create custome Subnet
*3-* create route table & internet gateway

### After these infrastructures have been provisioned. 

*4-* Provision EC2 instance
*5-* Deploy nginx docker container
*6-* create security group (firewall)
*7-* open ports to allow ssh 