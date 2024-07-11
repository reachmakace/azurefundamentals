**3 Parts in Microsoft Azure Fundamentals**
Microsoft Azure Fundamentals: Describe cloud concepts
Microsoft Azure Fundamentals: Describe Azure management and governance
Microsoft Azure Fundamentals: Describe Azure architecture and services

# Microsoft Azure Fundamentals: Describe cloud concepts
https://learn.microsoft.com/en-us/training/paths/microsoft-azure-fundamentals-describe-cloud-concepts/

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

# Azure shifts development costs from the capital expense (CapEx) of building out and maintaining infrastructure and facilities to an operational expense (OpEx) of renting infrastructure as you need it, whether it’s compute, storage, networking, and so on. OpEx cost can be impacted by many factors.
Resource type - Cost varies based on the type of resources, the settings for the resource, and the Azure region will all have an impact on how much a resource costs
Consumption - Pay-as-you-go & Azure also offers the ability to commit to using a set amount of cloud resources in advance and receiving discounts on those “reserved” resources
Maintenance
Geography
Subscription type
Azure Marketplace
