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
Resource type - Cost varies based on the type of resources, the settings for the resource, and the Azure region will all have an impact on how much a resource costs
Consumption - Pay-as-you-go & Azure also offers the ability to commit to using a set amount of cloud resources in advance and receiving discounts on those “reserved” resources
Maintenance
Geography
Subscription type
Azure Marketplace

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

**Tools for managing and deploying Azure resources**
1. Azure portal
2. Azure Cloud Shell, including Azure CLI and Azure PowerShell
3. The purpose of Azure Arc
4. Azure Resource Manager (ARM) and Azure ARM templates
