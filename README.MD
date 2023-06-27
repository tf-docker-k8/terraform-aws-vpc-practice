### VPC Module

This module is going to create following resources.
* VPC
* Internet Gateway
* 2 public subnets
* 1 public route table
* Assocition between public subnets and public route table
* Assocition between private subnets and private route table
### Arguments

**vpc_cidr** (Optional) - Default value is 10.0.0.0/16 <br/>
**vpc_tags** (Optional) - User can provide tags, other wise empty <br/>
**public_subnet_cidr** (Required) - User must provide 2 valid subnet CIDR <br/>
**public_subnet_names** (Required) - User must provide 2 valid subnet names <br/>
**private_subnet_cidr** (Required) - User must provide 2 valid subnet CIDR <br/>
**private_subnet_names** (Required) - User must provide 2 valid subnet names <br/>
**public_route_table_tags** (Optional) - User can provide tags, other wise empty <br/>