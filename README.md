# terraform-azure-vm

Deploy a linux VM with basic SSH access on Azure using Terraform

follow the instructions in the link

https://learn.microsoft.com/en-us/training/modules/provision-linux-virtual-machine-in-azure/4-provision-linux-virtual-machine-using-terraform

### Notes:

* in the file vaiables.tf change the default value of the variable resource_group_name to your own resource group name
* When copy-pasting commands, whenever there are <> , remove them after pasting.
  
  So for example the command:

  terraform plan -out <terraform_plan>.tfplan

  should be:

  terraform plan -out terraform_plan.tfplan
