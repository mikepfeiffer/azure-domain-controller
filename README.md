# ARM Template that builds an Active Directory Domain Controller

## Modified by Tim on April 18, 2022

This template deploys an Active Directory Domain Controller on an Azure VM. You can RDP to the Domain Controller through an Azure Load Balancer that is deployed along with the VM. Additional NAT rules can be created on the Load Balancer to support RDP for additional member servers you wish to deploy into the same VNET. The AD DS configuration is applied by a PowerShell DSC configuration located inside this repo.

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fmikepfeiffer%2Fazure-domain-controller%2Fmaster%2Fazuredeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>
