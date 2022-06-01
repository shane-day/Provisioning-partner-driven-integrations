# Partner-driven provisioning integrations

The Azure Active Directory Provisioning service allows you to provision users and groups into both SaaS and on-premises applications. There are three primary integration paths:

**3rd Party integrations / gallery applications:**
Popular 3rd party applications, such as Dropbox, Snowflake, and Workplace by Facebook, are made available for customers through the Azure AD application gallery. New applications can easily be onboaded to the gallery using the [application network portal](https://docs.microsoft.com/azure/active-directory/azuread-dev/howto-app-gallery-listing). 

**SCIM compliant line-of-business applications:**
If your line-of-business application supports the [SCIM](https://aka.ms/scimoverview) standard, it can easily be integrated with the [Azure AD SCIM client](https://docs.microsoft.com/azure/active-directory/app-provisioning/use-scim-to-provision-users-and-groups).

**Partner-driven provisioning integrations:**
In cases where an application does not support SCIM, partners have built gateways between the Azure AD SCIM client and target applications.  **This document serves as a place for partners to attest to integrations that are compatible with Azure Active Directory, and for customers to discover these partner-driven integrations.** Note that these gateways are built, maintained, and owned by the third-party vendor. 

# How-to add partner-driven integrates to this document

1. Review the Azure AD SCIM [documentation](https://docs.microsoft.com/azure/active-directory/app-provisioning/use-scim-to-provision-users-and-groups) to understand the Azure AD SCIM implementation.
2. Test compatibility between the Azure AD SCIM client and your SCIM gateway using [on-demand provisioning](https://docs.microsoft.com/azure/active-directory/app-provisioning/provision-on-demand) and the [postman test suite](https://github.com/AzureAD/SCIMReferenceCode/wiki/Test-Your-SCIM-Endpoint).
3. Test the integration with at least 3 cusotmers to ensure that it is working as expected.
4. Click edit at the top of this page to create a pull request add your integration with this list.
5. An admin of the repository will merge your changes so that others can view them.

## Guidelines
* Add any new partners in alphabetical order.
* Limit your entries to 500 words.
* Ensure that you provide contact information for customers to learn more.

# Available partner-driven integrations
## Aquera
### Description
The Aquera Identity Integration Platform as a Service closes the connectivity gaps for real-time identity governance and lifecycle management workflows. The platform offers SCIM gateway services for account provisioning and aggregation, orchestration services for user and password synchronization, and workflow services for the governance of disconnected applications.
### Contact information
* Company website: https://www.aquera.com/applications.html
* Contact information: https://www.aquera.com/contact-us.html

### Applications supported
3 apps listed below for reference. Catalog contains [200+](https://www.aquera.com/applications.html).
* ADP
* Balsamiq
* Calendly

## IDM Works
### Description
We Are Experts In Identity & Access Management and Data Center Management.

### Contact information
* Company website: [IdentityForge solutions for Microsoft FIM](http://identityforge.com/index.php/solutions/iamsolutions/solutions-for-fim-2010)
* Contact information: 

### Applications supported
* SAP ECC Advanced Adapter
* IBM Tivoli
* FHIR Healthcare Advanced Adapter

## UnifySolutions
### Description

### Contact information

### Applications supported
* Company website: https://unifysolutions.net/solutions/azure-ad-application-provisioning/
* Contact information: 


# Disclaimer
{Input Legal text once available}
