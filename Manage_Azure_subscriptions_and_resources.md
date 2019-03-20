# Manage Azure subscriptions and resources (15-20%)

## Manage Azure subscriptions
* Assign administrator permissions; 
  * https://docs.microsoft.com/en-us/azure/billing/billing-add-change-azure-subscription-administrator
* configure cost center quotas and tagging; 
  * https://buildazure.com/2017/06/14/azure-subscription-resource-limits-and-quotas/
  * https://docs.microsoft.com/en-us/azure/billing/billing-getting-started
  * http://resource.onlinetech.com/manage-your-azure-spend-by-cost-center/
* configure Azure subscription policies at Azure subscription level
  * https://docs.microsoft.com/en-us/azure/governance/policy/overview

* [Azure enterprise scaffold: Prescriptive subscription governance](https://docs.microsoft.com/en-ca/azure/architecture/cloud-adoption/appendix/azure-scaffold?wt.mc_id=itshowcase-codeapps)
* [Examples of implementing Azure enterprise scaffold](https://docs.microsoft.com/en-ca/azure/architecture/cloud-adoption/appendix/azure-scaffold-examples)
* https://azure.microsoft.com/en-us/blog/organizing-subscriptions-and-resource-groups-within-the-enterprise/
* https://docs.microsoft.com/en-us/powershell/azure/manage-subscriptions-azureps?view=azps-1.5.0&viewFallbackFrom=azurermps-6.10.0
* https://www.computerweekly.com/tip/Windows-Azure-tutorial-Part-1-Set-up-and-manage-subscriptions
* [Blog - Subscription Management](https://azure.microsoft.com/en-us/blog/tag/subscription-management/)
* [Pluralsight - Managing Microsoft Azure Subscriptions](https://www.pluralsight.com/courses/microsoft-azure-subscriptions-managing)

## Analyze resource utilization and consumption
* Configure diagnostic settings on resources; 
* create baseline for resources; 
* create and rest alerts; 
* analyze alerts across subscription; 
* analyze metrics across subscription; 
* create action groups; 
* monitor for unused resources; 
* monitor spend; report on spend; 
* utilize Log Search query functions; 
* view alerts in Log Analytics

## Manage resource groups
May include but not limited to: Use Azure policies for resource groups; configure resource locks; configure resource policies; implement and set tagging on resource groups; move resources across resource groups; remove resource groups

## Managed role based access control (RBAC)
May include but not limited to: Create a custom role, configure access to Azure resources by assigning roles, configure management access to Azure, troubleshoot RBAC, implement RBAC policies, assign RBAC Roles