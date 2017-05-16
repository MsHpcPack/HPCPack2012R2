# Deploy Microsoft HPC Pack 2012 R2 cluster in Azure

You can now deploy a Microsoft HPC Pack cluster with HPC Pack 2012 R2 Update 3 in Azure. Choose one from the following templates and click "Deploy to Azure" button to deploy.

### Template 1: Cluster for Windows workloads in an existing Active Directory Domain (No public IP)
This template deploys an HPC Pack 2012 R2 cluster for Windows HPC workloads in an existing Active Directory Domain forest. The cluster includes one head node with local databases (SQL Server 2014 Express version), and a configurable number of **Windows** compute nodes. No public IP address is created for the virtual machines. Use this template if you have a virtual network with Express Route configured and you want to join the cluster to your on-premises Active Directory Domain.

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FMsHpcPack%2FHPCPack2012R2%2Fexistingvnet%2Fnewcluster-templates%2Fwincn-existing-ad-no-public-ip.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>

