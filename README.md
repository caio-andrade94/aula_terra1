**Cloud Infra Automation**

***Folder ex1***

Simple terraform to main.tf to provision ec2 instances with docker Run the following commands

terraform plan terraform apply



***Folder ex2*** 

Terraform module to provision ec2 instances with docker

1 - Access the folder ex2

2 - Define the params on main.tf

3 - Run the following commands

terraform init terraform plan terraform apply



***Folder ex3***

Terraform module to provision ec2 instances and jenkins

1 - Access the folder ex3

2 - Define the params on main.tf

3 - Run the following commands

terraform init terraform plan terraform apply



**Define your app params:**

Access the module main.tf and edit the params



**vpc_id**

Your VPC id created to host the EC2 instances



**subnet_cidr**

A public subnet attached to the your VPC, defined above


**ssh_key**

Public ssh key to access the ec2 instances through ssh

**app_name**

Your application name, this name will be used to name all aws resources



**app_tags**

- env: deployment environment
- project: project name
- customer: customer name



**app_instance**

EC2 flavor to be assigned to you application instance



**db_instance**

EC2 flavor to be assigned to you database instance
