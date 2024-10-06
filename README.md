**3 Parts in Microsoft Azure Fundamentals**
# Microsoft Azure Fundamentals: Describe cloud concepts
https://learn.microsoft.com/en-us/training/paths/microsoft-azure-fundamentals-describe-cloud-concepts/

# Microsoft Azure Fundamentals: Describe Azure management and governance
https://learn.microsoft.com/en-us/training/paths/describe-azure-management-governance/

# Microsoft Azure Fundamentals: Describe Azure architecture and services
https://learn.microsoft.com/en-us/training/paths/azure-fundamentals-describe-azure-architecture-services/

**Microsoft Azure Well-Architected Framework**
https://learn.microsoft.com/en-us/training/paths/azure-well-architected-framework/
This learning path helps prepare you for Exam AZ-305: Designing Microsoft Azure Infrastructure Solutions.

**Shared Responsibility Models**
IaaS
PaaS
SaaS

**Cloud models**
The cloud models define the deployment type of cloud resources
Public cloud
Private cloud
Hybrid Cloud

**Consumption based model**
Capital expenditure (CapEx) 
Operational expenditure (OpEx).

**Azure Arc**
Azure Arc is a set of technologies that helps manage your cloud environment. Azure Arc can help manage your cloud environment, whether it's a public cloud solely on Azure, a private cloud in your datacenter, a hybrid configuration, or even a multi-cloud environment running on multiple cloud providers at once.

**Azure VMware Solution**
What if you’re already established with VMware in a private cloud environment but want to migrate to a public or hybrid cloud? Azure VMware Solution lets you run your VMware workloads in Azure with seamless integration and scalability.

**High availability**
High availability focuses on ensuring maximum availability, regardless of disruptions or events that may occur.
99%, 99.9%, 99.99%, 99.9995%

**Scalability**
Scalability refers to the ability to adjust resources to meet. Horizontal Scaling & Vertical Scaling

**Reliability**
Reliability is the ability of a system to recover from failures and continue to function. It's also one of the pillars of the Microsoft Azure Well-Architected Framework.

**Predictability**
Predictability in the cloud lets you move forward with confidence. Predictability can be focused on performance predictability or cost predictability. 

**Performance Predictability** 
Autoscaling, load balancing, and high availability 

**Cost predictability**
Cost predictability is focused on predicting or forecasting the cost of the cloud spend.  Tools like the Total Cost of Ownership (TCO) or Pricing Calculator to get an estimate of potential cloud spend.

Benefits of manageability in the cloud
**Management of the cloud**
Management of the cloud speaks to managing your cloud resources. In the cloud, you can:
  Automatically scale resource deployment based on need.
  Deploy resources based on a preconfigured template, removing the need for manual configuration.
  Monitor the health of resources and automatically replace failing resources.
  Receive automatic alerts based on configured metrics, so you’re aware of performance in real time.

**Management in the cloud**
Management in the cloud speaks to how you’re able to manage your cloud environment and resources. You can manage these:
  Through a web portal.
  Using a command line interface.
  Using APIs.
  Using PowerShell.

**Infrastructure as a Service**
Maintaining the hardware, network connectivity (to the internet), and physical security -> Responsibility of Cloud Provider
Operating system installation, configuration, and maintenance; network configuration; database and storage configuration -> Responsibility of Client 

Scenarios:
Lift-and-shift migration
Testing and development

**Platform as a Service** - Platform as a service (PaaS) is a middle ground between renting space in a datacenter (infrastructure as a service) and paying for a complete and deployed solution (software as a service)
Some common scenarios where PaaS might make sense include:
Development framework
Analytics or business intelligence

**Software as a Service**
In a SaaS environment you’re responsible for the data that you put into the system, the devices that you allow to connect to the system, and the users that have access
Scenarios:
Email and messaging.
Business productivity applications.
Finance and expense tracking.

# Microsoft Azure Fundamentals: Describe Azure management and governance
Describe factors that can affect costs in Azure.
Compare the Pricing calculator and Total Cost of Ownership (TCO) calculator.
Describe the Microsoft Cost Management Tool.
Describe the purpose of tags.

Azure shifts development costs from the capital expense (CapEx) of building out and maintaining infrastructure and facilities to an operational expense (OpEx) of renting infrastructure as you need it, whether it’s compute, storage, networking, and so on. OpEx cost can be impacted by many factors.
1. Resource type - Cost varies based on the type of resources, the settings for the resource, and the Azure region will all have an impact on how much a resource costs
2. Consumption - Pay-as-you-go & Azure also offers the ability to commit to using a set amount of cloud resources in advance and receiving discounts on those “reserved” resources
3. Maintenance
4. Geography
5. Subscription type
6. Azure Marketplace

**Microsoft Cost Management tool**
Cost Management provides the ability to quickly check Azure resource costs, create alerts based on resource spend, and create budgets that can be used to automate management of resources.
# Cost alerts
1. Budget Alerts - Alerts the customers based on the Budget threshold
2. Credit Alerts - Azure Prepayment (previously Azure Monetary Commitment). Alerts upon Azure credits are consumed. Need to have EA (Enterprise Agreement) to avail this feature. 
3. Department Spending Quota Alerts - Notifies you when department of an organization spending reaches a fixed threshold of the quota 

# Budget
A budget is where you set a spending limit for Azure.

# Purpose of tags
Resource tags are another way to organize resources. Tags provide extra information, or metadata, about your resources
Other ways to organize resources is based on Subscription/Resource groups

# Tools in Azure for governance and compliance
**Microsoft Purview**
It is a family of data governance, risk, and compliance solutions that helps you get a single, unified view into your data.
Microsoft Purview: Risk and compliance,  unified data governance.
1. Automated data discovery
2. Confidential data classification
3. End-to-end data lineage

**Azure Policy**
Azure Policy is a service in Azure that enables you to create, assign, and manage policies that control or audit your resources. 

**Azure Initiative** - An Azure Policy initiative is a way of grouping related policies together. The initiative definition contains all of the policy definitions to help track your compliance state for a larger goal.

**Purpose of resource locks** - A resource lock prevents resources from being accidentally deleted or changed.
Types of Resource Locks - Delete Lock & Modify Lock

**Microsoft Service Trust Portal**
The Microsoft Service Trust Portal is a portal that provides access to various content, tools, and other resources about Microsoft security, privacy, and compliance practices.
Requires Microsoft cloud services account (Microsoft Entra organization account)

**Tools for deploying Azure resources**
1. **Azure portal:** The Azure portal is a web-based, unified console that provides an alternative to command-line tools
2. **Azure Cloud Shell:** includes both Azure CLI and Azure PowerShell. Difference: Azure PowerShell uses PowerShell commands and the Azure CLI uses Bash commands.
3. **The purpose of Azure Arc:** Azure Arc simplifies governance and management by delivering a consistent multi-cloud and on-premises management platform.
   1. Servers
   2. Kubernetes clusters
   3. Azure data services
   4. SQL Server
   5. Virtual machines (preview)
4. **Azure Resource Manager (ARM) and Azure ARM templates**: Azure Resource Manager (ARM) is the deployment and management service for Azure. 
   ARM templates and Bicep are two examples of using infrastructure as code with the Azure Resource Manager to maintain your environment

**Monitoring tools in Azure**
1. **Azure Advisor:** Azure Advisor evaluates your Azure resources and makes recommendations to help improve reliability, security, and performance, achieve operational excellence, and reduce costs
2. **Azure Service Health:**  Azure Service Health helps you keep track of Azure resource, both your specifically deployed resources and the overall status of Azure.
     1. **Azure Status** is a broad picture of the status of Azure globally.
     2. **Service Health** provides a narrower view of Azure services and regions.
     3. **Resource Health** is a tailored view of your actual Azure resources.
3. **Azure Monitor:** Including Azure Log Analytics, Azure Monitor Alerts, and Application Insights.
    **Azure Monitor** is a platform for collecting data on your resources, analyzing that data, visualizing the information, and even acting on the results.
     1. Azure Log Analytics is the tool in the Azure portal where you’ll write and run log queries on the data gathered by Azure Monitor.
     2. Azure Monitor Alerts
     3. Application Insights
        
# Core Architectural components of Azure 
**Physical Infrastucture**
1. Azure regions - One of more data centers in a specific region
2. Region pairs - Two regions with 300 miles apart
3. Sovereign regions - Dedicated Azure instance and not connected to the main Azure instance (DoD, US Govern etc)
4. Availability Zones - One of more datacenters in a region with standlone Power supply, cooling and network to provide resilency
5. Azure datacenters - Group of server racks
**Management Infrastucture**
7. Azure resources - A resource is the basic building block of Azure. Anything you create, provision, deploy, etc. is a resource. Virtual Machines (VMs), virtual networks, databases,       cognitive services, etc. are all considered resources within Azure.
8. Resource Groups - Resource groups are simply groupings of resources.
9. Subscriptions - Contains one or more resource groups. Two types of subscription boundaries -> 1. Billing Boundary, 2. Access Control Boundary
10. Management groups - Contains one or more subscriptions. Azure management groups provide a level of scope above subscriptions
11. Hierarchy of resource groups, subscriptions, and management groups
   
# Azure compute and networking services
compute types:
1. Container - Containers are a virtualization environment.
   Azure Container Instances - Azure Container Instances offer the fastest and simplest way to run a container in Azure; without having to manage any virtual machines or adopt any
     additional services. Azure Container Instances are a platform as a service (PaaS) offering. No provision for Certificates, revisions, scale, and environments
   Azure Container Apps - Azure Container Apps are similar in many ways to a container instance. PaaS offering but doesn't have direct access to Kubernetes API.
    Supports Certificates, revisions, scale, and environments
   Azure Kubernetes Service - Azure Kubernetes Service (AKS) is a container orchestration service.
      
3. Virtual machines - With Azure Virtual Machines (VMs), you can create and use VMs in the cloud. VMs provide infrastructure as a service (IaaS).
   Scale VMs in Azure
     **Virtual machine scale sets** - Virtual machine scale sets let you create and manage a group of identical, load-balanced VMs.
     **Virtual machine availability sets** - Availability sets are designed to ensure that VMs stagger updates and have varied power and network connectivity, preventing you from losing all your VMs with a single network or power failure.
       Update domain: The update domain groups VMs that can be rebooted at the same time. This allows you to apply updates while knowing that only one update domain grouping will be                           offline at a time.
       Fault domain:  The fault domain groups your VMs by common power source and network switch. By default, an availability set will split your VMs across up to three fault domains
    **VM Resources**
      1. Size (purpose, number of processor cores, and amount of RAM)
      2. Storage disks (hard disk drives, solid state drives, etc.)
      3. Networking (virtual network, public IP address, and port configuration)

     **Azure virtual desktop**
       Azure Virtual Desktop is a desktop and application virtualization service that runs on the cloud.
  
5. **Functions**

Resources required for virtual machines

Application hosting options, including Azure Web Apps, containers, and virtual machines
  Azure App Service - It is a service often called a "fully-featured" offering for hosting applications (especially Web applications). Need not be a container based application

**Azure Virtual Networks**
Azure virtual networks and virtual subnets enable Azure resources, such as VMs, web apps, and databases, to communicate with each other, with users on the internet, and with your on-premises client computers
Azure virtual networks provide the following key networking capabilities:
1. **Isolation and segmentation** - Azure virtual network allows you to create multiple isolated virtual networks
2. **Internet communications** - You can enable incoming connections from the internet by assigning a public IP address to an Azure resource, or putting the resource behind a public load balancer.
3. **Communicate between Azure resources** - Azure resources to communicate securely with each other in one of two ways. 1. Virtual Network 2. Service endpoints (Azure SQL Database, Azure storage)
4.**Communicate with on-premises resources:** Azure virtual networks enable you to link resources together in your on-premises environment and within your Azure subscription.
     1. Point to site - Point-to-site virtual private network connections are from a computer outside your organization back into your corporate network
     2. Site to Site - Site-to-site virtual private networks link your on-premises VPN device or gateway to the Azure VPN gateway in a virtual network.
     3. Azure Express Route - It provides a dedicated private connectivity to Azure that doesn't travel over the internet.
5. **Route network traffic** - By Default, Azure routes traffic between subnets on any connected virtual networks, on-premises networks, and the internet.
    1. Route tables
    2. Border Gateway protocol
6. **Filter network traffic** - Azure virtual networks enable you to filter traffic between subnets by using the following approaches:
    1 . Network Security Groups: These Azure resources that can contain multiple inbound and outbound security rules
    2.  Network Security Appliances - specialized VM running particular network function, such as running a firewall or performing wide area network (WAN) optimization.
8. **Connect virtual networks:** You can link virtual networks together by using virtual network peering. **Peering** allows two virtual networks to connect directly to each other
9   A **virtual private network (VPN)** uses an encrypted tunnel within another network. VPNs are typically deployed to connect two or more trusted private networks to one another over an untrusted network (typically the public internet).
10. **VPN gateway** A VPN gateway is a type of virtual network gateway.
    All data transfer is encrypted inside a private tunnel as it crosses the internet.
    You can deploy only one VPN gateway in each virtual network. 
    When setting up a VPN gateway, you must specify the type of VPN - either **policy-based or route-based**.
    
    **High-availability scenarios**
    Active/standby
    Active/active
    ExpressRoute failover
    Zone-redundant gateways
    Microsoft uses BGP, an industry standard dynamic routing protocol, to exchange routes between your on-premises network, your instances in Azure, and Microsoft public addresses
11. **Express Routes**
    ExpressRoute allows you to create a connection between your on-premises network and the Microsoft cloud in four different ways,
    1. CloudExchange Colocation - If your facility is co-located at a cloud exchange, you can request a virtual cross-connect to the Microsoft cloud
    2. Point-to-point Ethernet Connection - Point-to-point ethernet connection refers to using a point-to-point connection to connect your facility to the Microsoft cloud.
    3. Any-to-any (IPVPN) Connection - With any-to-any connectivity, you can integrate your wide area network (WAN) with Azure by providing connections to your offices and datacenters
    4. ExpressRoute Direct - You can connect directly into the Microsoft's global network at a peering location strategically distributed across the world.
    Even if you have an ExpressRoute connection, DNS queries, certificate revocation list checking, and Azure Content Delivery Network requests are still sent over the public internet.
12. **Azure DNS**
    Azure DNS is a hosting service for DNS domains that provides name resolution by using Microsoft Azure infrastructure.

# Azure storage services
A storage account provides a unique namespace for your Azure Storage data that's accessible from anywhere in the world over HTTP or HTTPS. Data in this account is secure, highly available, durable, and massively scalable.

**Redundancy Options**
  **1. Locally redundant storage (LRS):**
       Locally redundant storage (LRS) replicates your data **three times** within a single data center in the primary region.
       LRS provides at least **11 nines of durability (99.999999999%)** of objects over a given year.
  **2. Zone-redundant storage (ZRS)**:
      For Availability Zone-enabled Regions, zone-redundant storage (ZRS) replicates your Azure Storage data synchronously across three Azure availability zones in the primary region.
      ZRS offers durability for Azure Storage data objects of at least 12 nines (99.9999999999%) over a given year.

**Redundancy in a secondary region** - High availability and durability. Replicates data in another paired region which is miles aways. Region pair cannot be changed. 
  By default data in secondary region does not reach access. Read access will be available only during failover to secondary region. 
  Data is replicated to secondary region asynchronously. 
  The interval between the most recent writes to the primary region and the last write to the secondary region is known as the **recovery point objective (RPO)**. 
  Azure Storage typically has an RPO of less than 15 minutes,
  **3. Geo-redundant storage (GRS):**
       GRS is similar to running LRS in two regions. 3 Copies in 1 data center of primary region and 3 Copies in 1 data center of secondary region
       GRS offers durability for Azure Storage data objects of at least 16 nines (99.99999999999999%) over a given year.
       
  **4. Read-access geo-redundant storage (RA-GRS):** Same as GRS but have default read access to secondary region
  Geo-zone-redundant storage (GZRS)
    Data in a GZRS storage account is copied across three Azure availability zones in the primary region (similar to ZRS) and is also replicated to a secondary geographic region, using LRS, for protection from regional disasters.
    GZRS is designed to provide at least 16 nines (99.99999999999999%) of durability of objects over a given year.
  Read-access geo-zone-redundant storage (RA-GZRS): Same as GZRS but have default read access to secondary region
  Default read access to secondary region
  https://rajanieshkaushikk.com/2023/04/08/azure-blob-storage-vs-file-storage-vs-disk-storage-which-is-right-for-you/
  



**Endpoint format for Azure Storage services**
Blob Storage --> https://<storage-account-name>.blob.core.windows.net
Data Lake Storage Gen2 -->	https://<storage-account-name>.dfs.core.windows.net
Azure Files -->	https://<storage-account-name>.file.core.windows.net
Queue Storage -->	https://<storage-account-name>.queue.core.windows.net
Table Storage -->	https://<storage-account-name>.table.core.windows.net

1. Azure storage services
   
Storage tiers
Redundancy options
Storage account options and storage types
Options for moving files, including AzCopy, Azure Storage Explorer, and Azure File Sync
Migration options, including Azure Migrate and Azure Data Box

**Azure migration tools**
**Azure Migrate: Discovery and assessment**. Discover and assess on-premises servers running on VMware, Hyper-V, and physical servers in preparation for migration to Azure.
**Azure Migrate: Server Migration.** Migrate VMware VMs, Hyper-V VMs, physical servers, other virtualized servers, and public cloud VMs to Azure.
**Data Migration Assistant.** Data Migration Assistant is a stand-alone tool to assess SQL Servers. It helps pinpoint potential problems blocking migration. It identifies unsupported features, new features that can benefit you after migration, and the right path for database migration.
**Azure Database Migration Service.** Migrate on-premises databases to Azure VMs running SQL Server, Azure SQL Database, or SQL Managed Instances.
Azure App Service migration assistant. Azure App Service migration assistant is a standalone tool to assess on-premises websites for migration to Azure App Service. Use Migration Assistant to migrate .NET and PHP web apps to Azure.
Azure Data Box. Use Azure Data Box products to move large amounts of offline data to Azure.

**Azure Tenant Vs Azure Subcription**
Basic understanding:
a tenant is associated with a single identity (person, company, or organization) and can own one or several subscriptions
a subscription is linked to a payment setup and each subscription will result in a separate bill
in every subscription, you can add virtual resources (VM, storage, network, ...)
Additionally:
Every tenant is linked to a single Azure AD instance, which is shared with all tenant's subscriptions
Resources from one subscription are isolated from resources in other subscriptions
An owner of a tenant can decide to have multiple subscriptions:

when Subscriptions limits are reached
to use different payment methods
to isolate resources between different departments, projects, regional offices, and so on.
Example 1:
Contoso decides to have a tenant with 2 subscriptions:

one subscription for the Prod department with Credit Card A
one subscription for the Dev department with Credit Card B
(but could also be the same Credit Card as the one of another subscription)
In this example, the two departments share the same Azure AD database. However, resources are isolated between departments, and budgets can be separated too.

Example 2:
A holding company decides to have 2 tenants:

one tenant for subsidiary Contoso with one subscription for Dev and Prod
one tenant for subsidiary Fabrikam with one subscription for Dev and another subscription for Prod
In this example, both companies have a different Azure AD database.

Example 3:
You have a tenant for your personal training.
In this tenant, you can have:

one free Azure subscription (linked to a credit card but not charged, and can be converted to a Pay-As-You-Go subscription after the free trial)
one or several Pay-As-You-Go subscriptions (linked to different credit cards)
one or several Azure Pass Sponsorship subscriptions, not linked to any credit card because these subscriptions are obtained during Microsoft trainings
one Visual Studio subscription (linked to a credit card) and with different quotas (of free resources) than the free subscription
Despite all those subscriptions have isolated resources (per subscription), and some are free while you have to pay for others, all subscriptions share the same Azure AD database.

Here is a quick recap:

An organization can have multiple subscriptions.

A subscription can have multiple licenses.

Licenses can be assigned to individual user accounts.

User accounts are stored in a Microsoft Entra tenant.

Here is an example of the relationship of organizations, subscriptions, licenses, and user accounts:

An organization identified by its public domain name.

A Microsoft 365 E3 subscription with user licenses.

A Microsoft 365 E5 subscription with user licenses.

A Dynamics 365 subscription with user licenses.

Multiple Azure subscriptions.

The organization's user accounts in a common Microsoft Entra tenant.

Multiple Microsoft cloud offering subscriptions can use the same Microsoft Entra tenant that acts as a common identity provider. A central Microsoft Entra tenant that contains the synchronized accounts of your on-premises AD DS provides cloud-based Identity as a Service (IDaaS) for your organization.
