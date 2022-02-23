# Azure Lighthouse Managed Offer
Stores the Azure Lighthouse Managed Service Offer template that can be used to provide delegation to customer environments from objects within the Softcat Partner account

The following permissions are included in this lighthouse offer.

# Delegated Permissions

| User/Group                                | Delegated Permission                                 | Access Type | Max Duration | MFA   | Approvers                      |
| ----------------------------------------- | ---------------------------------------------------- | ----------- | ------------ | ---   | ------------------------------ |
| Managed Azure - Engineers                 | Reader                                               | Permanent   | -            | -     | -                              |
| Managed Azure - Engineers                 | Support Request Contributor                          | Permanent   | -            | -     | -                              |
| Managed Azure - Engineers                 | Managed Services Registration Assignment Delete Role | Permanent   | -            | -     | -                              |
| Managed Azure - Engineers                 | Contributor                                          | Eligible    | 4 hours      | Azure | PIM - Managed Azure (Approvers)|
| Managed Azure - Service Delivery Managers | Reader                                               | Permanent   | -            | -     | -                              |
| Managed Azure - Services                  | Reader                                               | Permanent   | -            | -     | -                              |
| Managed Azure - Services                  | Support Request Contributor                          | Permanent   | -            | -     | -                              |

# Deploy to Azure 

Use the below button to deploy this Azure Lighthouse offer to a tenant.

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FSoftcatMS%2Fazure-lighthouse-managedoffer%2Fmain%2Fproduction-lighthouse-offer.json)
