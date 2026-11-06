# Azure Labs

Hands-on Azure projects I built in my own subscription over 30 days while preparing for **AZ-104: Microsoft Azure Administrator**, which I passed in November 2026.

Each project starts from a realistic business scenario, is built in the Azure portal (with Azure CLI and Cloud Shell where it made sense), and is then tested to prove it works. Every write-up covers what I built, why I made each decision, how I verified it and what I learned.

## Projects

| # | Project | Key services |
|---|---|---|
| 1 | [Compute, identity and governance](01-compute-identity-governance/) | Linux VM, managed disks, NSG, Key Vault (RBAC), Entra ID groups, Azure RBAC, Azure Policy, Cost Management |
| 2 | [Networking and secure storage](02-networking-secure-storage/) | VNet and subnets, NSG, service endpoints, storage account, private endpoint, private DNS, SAS, Storage Explorer, AzCopy, ARM templates and Template Specs |
| 3 | [Monitoring, backup and disaster recovery](03-monitoring-backup-recovery/) | Azure Monitor, VM insights, metric alerts, action groups, Log Analytics and KQL, Recovery Services vault, Azure Backup, Azure Site Recovery |
| 4 | [Entra ID identity and access](04-entra-id-identity-access/) | Users and groups, app registrations, enterprise applications, Microsoft Graph permissions, Conditional Access, MFA, sign-in logs |
| 5 | [App Service deployment and scaling](05-app-service-scaling/) | App Service, App Service plans, deployment slots, autoscale, backups, metrics and alerts |

## Skills demonstrated

- **Identity and governance:** Entra ID users and groups, Azure RBAC with least privilege, Azure Policy initiatives, Conditional Access and MFA, budgets
- **Storage:** storage account security, SAS tokens, private endpoints and private DNS, AzCopy and Storage Explorer
- **Compute:** Linux VMs with SSH key authentication, managed disks, static private IPs, App Service plans, slots and autoscale
- **Networking:** VNet and subnet design, NSG rules, service endpoints vs private endpoints
- **Monitoring and recovery:** Azure Monitor alerts, Log Analytics with KQL, Azure Backup and Site Recovery
- **Infrastructure as code (intro):** exporting deployments as ARM templates and redeploying them as Template Specs

## A note on names and cleanup

Resource names and IP ranges are from my lab. Projects 3 to 5 use representative names where I didn't record the exact ones. All resources were deleted after testing to avoid costs, and no keys, SAS tokens or other secrets are stored in this repository.

## Certification

Microsoft Certified: Azure Administrator Associate (AZ-104)
