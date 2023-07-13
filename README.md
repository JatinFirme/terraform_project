# Steps to create terraform_project
1) Create VPC
2) Create an Internet Gateway
3) Create a Custom Route Table
4) Create a Subnet
5) Associate subnet with Route Table
6) Create a Security Group to allow ports 22,80,443
7) Create a network interface with ip in the subnet that was created in Step 4
8) Assign an elastic IP to the network interface created in Step 7
9) Create an Ubuntu server and install/enable apache2
