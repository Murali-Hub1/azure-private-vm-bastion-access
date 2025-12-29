# Secure Azure VM Access Using Azure Bastion (No Public IP)

## Overview
This project demonstrates deploying a Linux virtual machine in Azure without a public IP and accessing it using Azure Bastion.

A web application (Nginx) runs on the VM using a private IP and is accessed using Bastion port tunneling without exposing the VM to the internet.

## Architecture
- Azure Virtual Network
- Multiple subnets including AzureBastionSubnet
- Linux VM (Private IP only)
- Network Security Group
- Azure Bastion (Standard)
- Nginx Web Application

## Security Design
- VM has no public IP
- SSH access only via Azure Bastion
- Inbound traffic controlled using NSG
- Application accessed via Bastion tunnel

## Skills Demonstrated
- Azure Networking
- Secure VM design
- Azure Bastion
- Linux administration
- Cost-aware cloud cleanup
