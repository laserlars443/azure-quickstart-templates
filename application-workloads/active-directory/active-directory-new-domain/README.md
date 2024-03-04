---
description: This template creates a new Azure VM, it configures the VM to be an AD DC for a new Forest
page_type: sample
products:
- azure
- azure-resource-manager
urlFragment: active-directory-new-domain
languages:
- bicep
- json
---
# Create an Azure VM with a new AD Forest

![Azure Public Test Date](https://azurequickstartsservice.blob.core.windows.net/badges/application-workloads/active-directory/active-directory-new-domain/PublicLastTestDate.svg)
![Azure Public Test Result](https://azurequickstartsservice.blob.core.windows.net/badges/application-workloads/active-directory/active-directory-new-domain/PublicDeployment.svg)

![Azure US Gov Last Test Date](https://azurequickstartsservice.blob.core.windows.net/badges/application-workloads/active-directory/active-directory-new-domain/FairfaxLastTestDate.svg)
![Azure US Gov Last Test Result](https://azurequickstartsservice.blob.core.windows.net/badges/application-workloads/active-directory/active-directory-new-domain/FairfaxDeployment.svg)

![Best Practice Check](https://azurequickstartsservice.blob.core.windows.net/badges/application-workloads/active-directory/active-directory-new-domain/BestPracticeResult.svg)
![Cred Scan Check](https://azurequickstartsservice.blob.core.windows.net/badges/application-workloads/active-directory/active-directory-new-domain/CredScanResult.svg)

![Bicep Version](https://azurequickstartsservice.blob.core.windows.net/badges/application-workloads/active-directory/active-directory-new-domain/BicepVersion.svg)

This template will deploy a new VM (along with a new VNet and Load Balancer) and will configure it as a Domain Controller and create a new forest and domain.

Click the button below to deploy

[![Deploy To Azure]()(https://portal.azure.com/#create/Microsoft.Template/uri/https://github.com/laserlars443/azure-quickstart-templates/blob/a091f0a0a70aac843e65f655ba2a661eda4a74df/application-workloads/active-directory/active-directory-new-domain/azuredeploy.json)

`Tags: Microsoft.Network/publicIPAddresses, Microsoft.Compute/availabilitySets, Microsoft.Resources/deployments, Microsoft.Network/loadBalancers, Microsoft.Network/networkInterfaces, Microsoft.Compute/virtualMachines, extensions, DSC, Microsoft.Network/virtualNetworks`
