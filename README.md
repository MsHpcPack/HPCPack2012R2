# Deploy Microsoft HPC Pack 2012 R2 cluster in Azure

You can now deploy a Microsoft HPC Pack cluster with HPC Pack 2012 R2 Update 3 in Azure. Choose one from the following templates and click "Deploy to Azure" button to deploy.

---
## The following templates create an HPC Pack cluster in an existing Active Directory Domain
### Template 1: Cluster for Windows workloads in an existing Active Directory Domain
This template deploys an HPC Pack 2012 R2 cluster for Windows HPC workloads in an existing Active Directory Domain forest. The cluster includes one head node with local databases (SQL Server 2014 Express version), and a configurable number of **Windows** compute nodes. Use this template if you have a virtual network with Express Route configured and you want to join the cluster to your on-premises Active Directory Domain.

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FMsHpcPack%2FHPCPack2012R2%2Fmaster%2Fnewcluster-templates%2Fwincn-existing-ad.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>

### Template 2: Cluster for Linux workloads in an existing Active Directory Domain
This template deploys an HPC Pack 2012 R2 cluster for Linux HPC workloads in an existing Active Directory Domain forest. The cluster includes one head node with local databases (SQL Server 2014 Express version), and a configurable number of **Linux** compute nodes. Use this template if you have a virtual network with Express Route configured and you want to join the cluster to your on-premises Active Directory Domain.

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FMsHpcPack%2FHPCPack2012R2%2Fmaster%2Fnewcluster-templates%2Flinuxcn-existing-ad.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>

### Template 3: Cluster for Windows/Linux workloads with user customized compute node image in an existing Active Directory Domain
This template deploys an HPC Pack 2012 R2 cluster for Windows HPC workloads with user customized compute node image in an existing Active Directory Domain forest. The cluster includes one head node with local databases (SQL Server 2014 Express version), and a configurable number of **Windows** compute nodes from user customized VM image. Use this template if you have a virtual network with Express Route configured and you want to join the cluster to your on-premises Active Directory Domain.

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FMsHpcPack%2FHPCPack2012R2%2Fmaster%2Fnewcluster-templates%2Fcustomcn-existing-ad.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>

---
## The following templates create an HPC Pack cluster in a new Active Directory Domain
### Template 1: Cluster for Windows workloads
This template deploys an HPC Pack 2012 R2 cluster for Windows HPC workloads. The cluster includes one head node with local databases (SQL Server 2014 Express version), and a configurable number of **Windows** compute nodes. 

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FMsHpcPack%2FHPCPack2012R2%2Fmaster%2Fnewcluster-templates%2Fwincn-new-ad.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>

### Template 2: Cluster for Linux workloads
This template deploys an HPC Pack 2012 R2 cluster for Linux HPC workloads. The cluster includes one head node with local databases (SQL Server 2014 Express version), and a configurable number of **Linux** compute nodes. No public IP address is created for the virtual machines. 

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FMsHpcPack%2FHPCPack2012R2%2Fmaster%2Fnewcluster-templates%2Flinuxcn-new-ad.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>

### Template 3: Cluster for Windows/Linux workloads with user customized compute node image
This template deploys an HPC Pack 2012 R2 cluster with user customized compute node image. The cluster includes one head node with local databases (SQL Server 2014 Express version), and a configurable number of **Windows** compute nodes from user customized VM image. 

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FMsHpcPack%2FHPCPack2012R2%2Fmaster%2Fnewcluster-templates%2Fcustomcn-new-ad.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>