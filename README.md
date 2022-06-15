# Terraform-Configs-Azure
This repo will be a storage container for all of my Terraform config files. Feel free to take them and customize them for your own environment. Each code file will be named after the Azure resource it creates. 

Current list of config files:

Multi-node Linux VM network - includes options to set the amount of VMs in the variable.tf file, generates VMs, NICs, Disks, etc. based on those variables: https://github.com/jasonereid/Terraform-Configs-Azure/blob/main/Linux-multi-node-network. You can use this template to generate massive amounts of barebones Ubuntu VMs.

Ubuntu Linux VM, SSH keys, Vnet, 2 subnets, and an NSG: https://github.com/jasonereid/Terraform-Configs-Azure/blob/main/Linux-with-vnet-nsg-and-2-subnets
(Don't forget to add your own variables.tf!)

Network Security Group with port 443 open: https://github.com/jasonereid/Terraform-Configs-Azure/blob/main/network-security-group

