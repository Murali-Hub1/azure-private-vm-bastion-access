## Subnets and Network Security Group

Subnets created:
- AzureBastionSubnet (required for Bastion)
- Workload subnet for VM

Network Security Group:
- Allowed SSH from Azure Bastion
- Allowed HTTP traffic inside VNet
- Denied all other inbound traffic

Purpose:
To restrict access and follow least privilege security.
