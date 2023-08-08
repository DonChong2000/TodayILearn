# Azure Resource Manager

We can access ARM by Azure Portal, Azure CLI, and Azure PowerShell to access ARM through **REST API**.

Smallest unit: Resources
- e.g. VM, storages accounts...
- Each resources has a resources provider

Resources < Resources Group < Subscription < Azure Resources Manager (ARM). 
![](../../../z.Images/Pasted%20image%2020230807173024.png)

A subscription can only have a relationship with one Tenant at a time,
which make sure only we have access to ARM (By AD identity)


# Using Azure Portal and Portal Cloud Shell
- We use Azure AD to login to Azure
- Since PowerShell is Object Oriented, we can script our environment install process
- e.g. `$RG = Get-AzResourceGroup`, `$RG.name`


# Using ARM Templates

