---
title: Archive for What's new in Microsoft Entra ID?
description: The What's new release notes in the Overview section of this content set contain six months of activity. After six months, the items are removed from the main article and put into this archive article.
services: active-directory
author: owinfreyATL
manager: amycolannino
ms.service: active-directory
ms.subservice: fundamentals
ms.topic: conceptual
ms.date: 02/01/2024
ms.author: owinfrey
ms.reviewer: dhanyahk
ms.custom: it-pro, seo-update-azuread-jan, has-adal-ref, has-azure-ad-ps-ref
ms.collection: M365-identity-device-management
---

# Archive for What's new in Microsoft Entra ID?

The primary [What's new in Microsoft Entra ID? release notes](whats-new.md) article contains updates for the last six months, while this article contains Information up to 18 months.

The What's new in Microsoft Entra ID? release notes provide information about:

- The latest releases
- Known issues
- Bug fixes
- Deprecated functionality
- Plans for changes

---

## July 2023

### General Availability: Azure Active Directory (Azure AD) is being renamed.

**Type:** Changed feature       
**Service category:**  N/A                          
**Product capability:** End User Experiences                

**No action is required from you, but you may need to update some of your own documentation.**

Azure AD is being renamed to Microsoft Entra ID. The name change rolls out across all Microsoft products and experiences throughout the second half of 2023. 

Capabilities, licensing, and usage of the product isn't changing. To make the transition seamless for you, the pricing, terms, service level agreements, URLs, APIs, PowerShell cmdlets, Microsoft Authentication Library (MSAL) and developer tooling remain the same.   

Learn more and get renaming details: [New name for Azure Active Directory](new-name.md).

---

### General Availability - Include/exclude My Apps in Conditional Access policies

**Type:** Fixed       
**Service category:** Conditional Access                            
**Product capability:** End User Experiences                  

My Apps can now be targeted in Conditional Access policies. This solves a top customer blocker. The functionality is available in all clouds. GA also brings a new app launcher, which improves app launch performance for both SAML and other app types. 

Learn More about setting up Conditional Access policies here: [Azure AD Conditional Access documentation](~/identity/conditional-access/index.yml).

---

### General Availability - Conditional Access for Protected Actions

**Type:** New feature         
**Service category:** Conditional Access                            
**Product capability:** Identity Security & Protection                    

Protected actions are high-risk operations, such as altering access policies or changing trust settings, that can significantly impact an organization's security. To add an extra layer of protection, Conditional Access for Protected Actions lets organizations define specific conditions for users to perform these sensitive tasks. For more information, see: [What are protected actions in Azure AD?](~/identity/role-based-access-control/protected-actions-overview.md).

---

### General Availability - Access Reviews for Inactive Users

**Type:** New feature         
**Service category:** Access Reviews                            
**Product capability:** Identity Governance                      

This new feature, part of the Microsoft Entra ID Governance SKU, allows admins to review and address stale accounts that haven’t been active for a specified period. Admins can set a specific duration to determine inactive accounts that weren't used for either interactive or non-interactive sign-in activities. As part of the review process, stale accounts can automatically be removed. For more information, see: [Microsoft Entra ID Governance Introduces Two New Features in Access Reviews](https://techcommunity.microsoft.com/t5/microsoft-entra-azure-ad-blog/microsoft-entra-id-governance-introduces-two-new-features-in/ba-p/2466930).

---

### General Availability - Automatic assignments to access packages in Microsoft Entra ID Governance

**Type:** Changed feature       
**Service category:** Entitlement Management                          
**Product capability:** Entitlement Management                

Microsoft Entra ID Governance includes the ability for a customer to configure an assignment policy in an entitlement management access package that includes an attribute-based rule, similar to dynamic groups, of the users who should be assigned access. For more information, see: [Configure an automatic assignment policy for an access package in entitlement management](~/id-governance/entitlement-management-access-package-auto-assignment-policy.md).

---

### General Availability - Custom Extensions in Entitlement Management 

**Type:** New feature       
**Service category:** Entitlement Management                          
**Product capability:** Entitlement Management                

Custom extensions in Entitlement Management are now generally available, and allow you to extend the access lifecycle with your organization-specific processes and business logic when access is requested or about to expire. With custom extensions you can create tickets for manual access provisioning in disconnected systems, send custom notifications to additional stakeholders, or automate additional access-related configuration in your business applications such as assigning the correct sales region in Salesforce. You can also leverage custom extensions to embed external governance, risk, and compliance (GRC) checks in the access request.

For more information, see:

- [Microsoft Entra ID Governance Entitlement Management New Generally Available Capabilities](https://techcommunity.microsoft.com/t5/microsoft-entra-azure-ad-blog/microsoft-entra-id-governance-entitlement-management-new/ba-p/2466929)
- [Trigger Logic Apps with custom extensions in entitlement management](~/id-governance/entitlement-management-logic-apps-integration.md)

---

### General Availability - Conditional Access templates

**Type:** Plan for change         
**Service category:** Conditional Access                             
**Product capability:** Identity Security & Protection                  

Conditional Access templates are predefined set of conditions and controls that provide a convenient method to deploy new policies aligned with Microsoft recommendations. Customers are assured that their policies reflect modern best practices for securing corporate assets, promoting secure, optimal access for their hybrid workforce. For more information, see: [Conditional Access templates](~/identity/conditional-access/concept-conditional-access-policy-common.md).

---

### General Availability - Lifecycle Workflows

**Type:** New feature       
**Service category:** Lifecycle Workflows                            
**Product capability:** Identity Governance                  

User identity lifecycle is a critical part of an organization’s security posture, and when managed correctly, can have a positive impact on their users’ productivity for Joiners, Movers, and Leavers. The ongoing digital transformation is accelerating the need for good identity lifecycle management. However, IT and security teams face enormous challenges managing the complex, time-consuming, and error-prone manual processes necessary to execute the required onboarding and offboarding tasks for hundreds of employees at once. This is an ever present and complex issue IT admins continue to face with digital transformation across security, governance, and compliance.

Lifecycle Workflows, one of our newest Microsoft Entra ID Governance capabilities is now generally available to help organizations further optimize their user identity lifecycle. For more information, see: [Lifecycle Workflows is now generally available!](https://techcommunity.microsoft.com/t5/microsoft-entra-azure-ad-blog/lifecycle-workflows-is-now-generally-available/ba-p/2466931)

---

### General Availability - Enabling extended customization capabilities for sign-in and sign-up pages in Company Branding capabilities.

**Type:** New feature       
**Service category:** User Experience and Management                            
**Product capability:** User Authentication                

Update the Microsoft Entra ID and Microsoft 365 sign in experience with new Company Branding capabilities. You can apply your company’s brand guidance to authentication experiences with predefined templates. For more information, see: [Company Branding](~/fundamentals/how-to-customize-branding.md) 

---

### General Availability - Enabling customization capabilities for the Self-Service Password Reset (SSPR) hyperlinks, footer hyperlinks and browser icons in Company Branding.

**Type:** Changed feature       
**Service category:** User Experience and Management                            
**Product capability:** End User Experiences                  

Update the Company Branding functionality on the Microsoft Entra ID/Microsoft 365 sign in experience to allow customizing Self Service Password Reset (SSPR) hyperlinks, footer hyperlinks, and a browser icon. For more information, see: [Company Branding](~/fundamentals/how-to-customize-branding.md) 

---

### General Availability - User-to-Group Affiliation recommendation for group Access Reviews

**Type:** New feature       
**Service category:** Access Reviews                            
**Product capability:** Identity Governance                  

This feature provides Machine Learning based recommendations to the reviewers of Azure AD Access Reviews to make the review experience easier and more accurate. The recommendation leverages machine learning based scoring mechanism and compares users’ relative affiliation with other users in the group, based on the organization’s reporting structure. For more information, see:  [Review recommendations for Access reviews](~/id-governance/review-recommendations-access-reviews.md) and [Introducing Machine Learning based recommendations in Azure AD Access reviews](https://techcommunity.microsoft.com/t5/microsoft-entra-azure-ad-blog/introducing-machine-learning-based-recommendations-in-azure-ad/ba-p/2466923)

---

### Public Preview - Inactive guest insights

**Type:** New feature       
**Service category:** Reporting                            
**Product capability:** Identity Governance                  

Monitor guest accounts at scale with intelligent insights into inactive guest users in your organization. Customize the inactivity threshold depending on your organization’s needs, narrow down the scope of guest users you want to monitor and identify the guest users that may be inactive. For more information, see: [Monitor and clean up stale guest accounts using access reviews](~/identity/users/clean-up-stale-guest-accounts.md).

---

### Public Preview - Just-in-time application access with PIM for Groups

**Type:** New feature       
**Service category:** Privileged Identity Management                            
**Product capability:** Privileged Identity Management                  

You can minimize the number of persistent administrators in applications such as [AWS](~/identity/saas-apps/aws-single-sign-on-provisioning-tutorial.md#just-in-time-jit-application-access-with-pim-for-groups-preview)/[GCP](~/identity/saas-apps/g-suite-provisioning-tutorial.md#just-in-time-jit-application-access-with-pim-for-groups-preview) and get JIT access to groups in AWS and GCP. While PIM for Groups is publicly available, we’ve released a public preview that integrates PIM with provisioning and reduces the activation delay from 40+ minutes to 1 – 2 minutes.

---

### Public Preview - Graph beta API for PIM security alerts on Azure AD roles

**Type:** New feature       
**Service category:** Privileged Identity Management                            
**Product capability:** Privileged Identity Management                 

Announcing API support (beta) for managing PIM security alerts for Azure AD roles. [Azure Privileged Identity Management (PIM)](~/id-governance/privileged-identity-management/index.yml) generates alerts when there's suspicious or unsafe activity in your organization in Azure Active Directory (Azure AD), part of Microsoft Entra. You can now manage these alerts using REST APIs. These alerts can also be [managed through the Azure portal](~/id-governance/privileged-identity-management/pim-resource-roles-configure-alerts.md). For more information, see:  [unifiedRoleManagementAlert resource type](/graph/api/resources/unifiedrolemanagementalert).

---

### General Availability - Reset Password on Azure Mobile App

**Type:** New feature       
**Service category:** Other                            
**Product capability:** End User Experiences                

The Azure mobile app has been enhanced to empower admins with specific permissions to conveniently reset their users' passwords. Self Service Password Reset will not be supported at this time. However, users can still more efficiently control and streamline their own sign-in and auth methods. The mobile app can be downloaded for each platform here:

- Android: https://aka.ms/AzureAndroidWhatsNew
- IOS: https://aka.ms/ReferAzureIOSWhatsNew

---

### Public Preview - API-driven inbound user provisioning 

**Type:** New feature       
**Service category:** Provisioning                              
**Product capability:** Inbound to Azure AD                  

With API-driven inbound provisioning, Microsoft Entra ID provisioning service now supports integration with any system of record. Customers and partners can use any automation tool of their choice to retrieve workforce data from any system of record for provisioning into Entra ID and connected on-premises Active Directory domains. The IT admin has full control on how the data is processed and transformed with attribute mappings. Once the workforce data is available in Entra ID, the IT admin can configure appropriate joiner-mover-leaver business processes using Entra ID Governance Lifecycle Workflows. For more information, see: [API-driven inbound provisioning concepts (Public preview)](~/identity/app-provisioning/inbound-provisioning-api-concepts.md).

---

### Public Preview - Dynamic Groups based on EmployeeHireDate User attribute

**Type:** New feature       
**Service category:** Group Management                                
**Product capability:** Directory                    

This feature enables admins to create dynamic group rules based on the user objects' employeeHireDate attribute. For more information, see: [Properties of type string](~/identity/users/groups-dynamic-membership.md#properties-of-type-string).

---

### General Availability - Enhanced Create User and Invite User Experiences

**Type:** Changed feature       
**Service category:** User Management                                  
**Product capability:** User Management                      

We have increased the number of properties admins are able to define when creating and inviting a user in the Entra admin portal, bringing our UX to parity with our Create User APIs. Additionally, admins can now add users to a group or administrative unit, and assign roles. For more information, see: [Add or delete users using Azure Active Directory](./add-users.md).

---

### General Availability - All Users and User Profile

**Type:** Changed feature       
**Service category:** User Management                                  
**Product capability:** User Management                   

The All Users list now features an infinite scroll, and admins can now modify more properties in the User Profile. For more information, see: [How to create, invite, and delete users](~/fundamentals/how-to-create-delete-users.md).

---

### Public Preview - Windows MAM

**Type:** New feature       
**Service category:** Conditional Access                                
**Product capability:** Identity Security & Protection                    

“*When will you have MAM for Windows?*” is one of our most frequently asked customer questions. We’re happy to report that the answer is: “Now!” We’re excited to offer this new and long-awaited MAM Conditional Access capability in Public Preview for Microsoft Edge for Business on Windows.

Using MAM Conditional Access, Microsoft Edge for Business provides users with secure access to organizational data on personal Windows devices with a customizable user experience. We’ve combined the familiar security features of app protection policies (APP), Windows Defender client threat defense, and Conditional Access, all anchored to Azure AD identity to ensure un-managed devices are healthy and protected before granting data access. This can help businesses to improve their security posture and protect sensitive data from unauthorized access, without requiring full mobile device enrollment.

The new capability extends the benefits of app layer management to the Windows platform via Microsoft Edge for Business. Admins are empowered to configure the user experience and protect organizational data within Microsoft Edge for Business on un-managed Windows devices.

For more information, see: [Require an app protection policy on Windows devices (preview)](~/identity/conditional-access/how-to-app-protection-policy-windows.md).

---

### General Availability - New Federated Apps available in Azure AD Application gallery - July 2023

**Type:** New feature   
**Service category:** Enterprise Apps                
**Product capability:** 3rd Party Integration          

In July 2023 we've added the following 10 new applications in our App gallery with Federation support:    

[Gainsight SAML](~/identity/saas-apps/gainsight-tutorial.md), [Dataddo](https://www.dataddo.com/), [Puzzel](https://www.puzzel.com/), [Worthix App](~/identity/saas-apps/worthix-app-tutorial.md), [iOps360 IdConnect](https://iops360.com/iops360-id-connect-azuread-single-sign-on/), [Airbase](~/identity/saas-apps/airbase-tutorial.md), [Couchbase Capella - SSO](~/identity/saas-apps/couchbase-capella-sso-tutorial.md), [SSO for Jama Connect®](~/identity/saas-apps/sso-for-jama-connect-tutorial.md), [mediment (メディメント)](https://mediment.jp/), [Netskope Cloud Exchange Administration Console](~/identity/saas-apps/netskope-cloud-exchange-administration-console-tutorial.md), [Uber](~/identity/saas-apps/uber-tutorial.md), [Plenda](https://app.plenda.nl/), [Deem Mobile](~/identity/saas-apps/deem-mobile-tutorial.md), [40SEAS](https://www.40seas.com/), [Vivantio](https://www.vivantio.com/), [AppTweak](https://www.apptweak.com/), [Vbrick Rev Cloud](~/identity/saas-apps/vbrick-rev-cloud-tutorial.md), [OptiTurn](~/identity/saas-apps/optiturn-tutorial.md), [Application Experience with Mist](https://www.mist.com/), [クラウド勤怠管理システムKING OF TIME](~/identity/saas-apps/cloud-attendance-management-system-king-of-time-tutorial.md), [Connect1](~/identity/saas-apps/connect1-tutorial.md), [DB Education Portal for Schools](~/identity/saas-apps/db-education-portal-for-schools-tutorial.md), [SURFconext](~/identity/saas-apps/surfconext-tutorial.md), [Chengliye Smart SMS Platform](~/identity/saas-apps/chengliye-smart-sms-platform-tutorial.md), [CivicEye SSO](~/identity/saas-apps/civic-eye-sso-tutorial.md), [Colloquial](~/identity/saas-apps/colloquial-tutorial.md), [BigPanda](~/identity/saas-apps/bigpanda-tutorial.md), [Foreman](https://foreman.mn/)

You can also find the documentation of all the applications from here https://aka.ms/AppsTutorial.

For listing your application in the Azure AD app gallery, read the details here https://aka.ms/AzureADAppRequest

---

### Public Preview - New provisioning connectors in the Azure AD Application Gallery - July 2023

**Type:** New feature   
**Service category:** App Provisioning               
**Product capability:** 3rd Party Integration    


We've added the following new applications in our App gallery with Provisioning support. You can now automate creating, updating, and deleting of user accounts for these newly integrated apps:

- [Albert](~/identity/saas-apps/albert-provisioning-tutorial.md)
- [Rhombus Systems](~/identity/saas-apps/rhombus-systems-provisioning-tutorial.md)
- [Axiad Cloud](~/identity/saas-apps/axiad-cloud-provisioning-tutorial.md)
- [Dagster Cloud](~/identity/saas-apps/dagster-cloud-provisioning-tutorial.md)
- [WATS](~/identity/saas-apps/wats-provisioning-tutorial.md)
- [Funnel Leasing](~/identity/saas-apps/funnel-leasing-provisioning-tutorial.md)


For more information about how to better secure your organization by using automated user account provisioning, see: [Automate user provisioning to SaaS applications with Azure AD](~/identity/app-provisioning/user-provisioning.md).


---

### General Availability - Microsoft Authentication Library for .NET 4.55.0

**Type:** New feature       
**Service category:** Other                                    
**Product capability:** User Authentication                     

Earlier this month we announced the release of [MSAL.NET 4.55.0](https://www.nuget.org/packages/Microsoft.Identity.Client/4.55.0), the latest version of the [Microsoft Authentication Library for the .NET platform](/entra/msal/dotnet/). The new version introduces support for user-assigned [managed identity](/entra/msal/dotnet/advanced/managed-identity) being specified through object IDs, CIAM authorities in the `WithTenantId` API, better error messages when dealing with cache serialization, and improved logging when using the [Windows authentication broker](/entra/msal/dotnet/acquiring-tokens/desktop-mobile/wam).

---

### General Availability - Microsoft Authentication Library for Python 1.23.0

**Type:** New feature       
**Service category:** Other                                    
**Product capability:** User Authentication                  

Earlier this month, the Microsoft Authentication Library team announced the release of [MSAL for Python version 1.23.0](https://pypi.org/project/msal/1.23.0/). The new version of the library adds support for better caching when using client credentials, eliminating the need to request new tokens repeatedly when cached tokens exist.

To learn more about MSAL for Python, see: [Microsoft Authentication Library (MSAL) for Python](/entra/msal/python/).

---

## June 2023

### Public Preview - New provisioning connectors in the Azure AD Application Gallery - June 2023

**Type:** New feature   
**Service category:** App Provisioning               
**Product capability:** 3rd Party Integration    
      
We've added the following new applications in our App gallery with Provisioning support. You can now automate creating, updating, and deleting of user accounts for these newly integrated apps:

- [Headspace](~/identity/saas-apps/headspace-provisioning-tutorial.md)
- [Humbol](~/identity/saas-apps/humbol-provisioning-tutorial.md)
- [LUSID](~/identity/saas-apps/lusid-provisioning-tutorial.md)
- [Markit Procurement Service](~/identity/saas-apps/markit-procurement-service-provisioning-tutorial.md)
- [Moqups](~/identity/saas-apps/moqups-provisioning-tutorial.md)
- [Notion](~/identity/saas-apps/notion-provisioning-tutorial.md)
- [OpenForms](~/identity/saas-apps/openforms-provisioning-tutorial.md)
- [SafeGuard Cyber](~/identity/saas-apps/safeguard-cyber-provisioning-tutorial.md)
- [Uni-tel A/S](~/identity/saas-apps/uni-tel-as-provisioning-tutorial.md)
- [Vault Platform](~/identity/saas-apps/vault-platform-provisioning-tutorial.md)
- [V-Client](~/identity/saas-apps/v-client-provisioning-tutorial.md)
- [Veritas Enterprise Vault.cloud SSO-SCIM](~/identity/saas-apps/veritas-provisioning-tutorial.md)

For more information about how to better secure your organization by using automated user account provisioning, see: [Automate user provisioning to SaaS applications with Azure AD](~/identity/app-provisioning/user-provisioning.md).

---

### General Availability - Include/exclude Entitlement Management in Conditional Access policies

**Type:** New feature       
**Service category:** Entitlement Management                          
**Product capability:** Entitlement Management                

The Entitlement Management service can now be targeted in the Conditional Access policy for inclusion or exclusion of applications. To target the Entitlement Management service, select “Azure AD Identity Governance - Entitlement Management” in the cloud apps picker. The Entitlement Management app includes the entitlement management part of My Access, the Entitlement Management part of the Entra and Azure portals, and the Entitlement Management part of MS Graph. For more information, see:  [Review your Conditional Access policies](~/id-governance/entitlement-management-external-users.md#review-your-conditional-access-policies).

---

### General Availability - Azure Active Directory User and Group capabilities on Azure Mobile are now available

**Type:** New feature       
**Service category:** Azure Mobile App                             
**Product capability:** End User Experiences                  

The Azure Mobile app now includes a section for Azure Active Directory. Within Azure Active Directory on mobile, user can search for and view more details about user and groups. Additionally, permitted users can invite guest users to their active tenant, assign group memberships and ownerships for users, and view user sign-in logs. For more information, see: [Get the Azure mobile app](https://azure.microsoft.com/get-started/azure-portal/mobile-app/).

---

### Plan for change - Modernizing Terms of Use Experiences

**Type:** Plan for change         
**Service category:** Terms of Use                               
**Product capability:** AuthZ/Access Delegation                   

Recently we announced the modernization of terms of use end-user experiences as part of ongoing service improvements. As previously communicated the end user experiences will be updated with a new PDF viewer and are moving from https://account.activedirectory.windowsazure.com to https://myaccount.microsoft.com. 

Starting today the modernized experience for viewing previously accepted terms of use is available via https://myaccount.microsoft.com/termsofuse/myacceptances. We encourage you to check out the modernized experience, which follows the same updated design pattern as the upcoming modernization of accepting or declining terms of use as part of the sign-in flow. We would appreciate your [feedback](https://forms.microsoft.com/r/NV0msbrqtF) before we begin to modernize the sign-in flow.

---

### General Availability - Privileged Identity Management for Groups

**Type:** New feature       
**Service category:** Privileged Identity Management                               
**Product capability:** Privileged Identity Management                 

Privileged Identity Management for Groups is now generally available. With this feature, you have the ability to grant users just-in-time membership in a group, which in turn provides access to Azure Active Directory roles, Azure roles, Azure SQL, Azure Key Vault, Intune, other application roles, and third-party applications. Through one activation, you can conveniently assign a combination of permissions across different applications and RBAC systems.

PIM for Groups offers can also be used for just-in-time ownership. As the owner of the group, you can manage group properties, including membership. For more information, see: [Privileged Identity Management (PIM) for Groups](~/id-governance/privileged-identity-management/concept-pim-for-groups.md).

---

### General Availability - Privileged Identity Management and Conditional Access integration 

**Type:** New feature       
**Service category:** Privileged Identity Management                               
**Product capability:** Privileged Identity Management                    

The Privileged Identity Management (PIM) integration with Conditional Access authentication context is generally available. You can require users to meet various requirements during role activation such as:

- Have specific authentication method through [Authentication Strengths](~/identity/authentication/concept-authentication-strengths.md)
- Activate from a compliant device 
- Validate location based on GPS
- Not have certain level of sign-in risk identified with Identity Protection
- Meet other requirements defined in Conditional Access policies

The integration is available for all providers: PIM for Azure AD roles, PIM for Azure resources, PIM for groups. For more information, see:
- [Configure Azure AD role settings in Privileged Identity Management](~/id-governance/privileged-identity-management/pim-how-to-change-default-settings.md)
- [Configure Azure resource role settings in Privileged Identity Management](~/id-governance/privileged-identity-management/pim-resource-roles-configure-role-settings.md)
- [Configure PIM for Groups settings](~/id-governance/privileged-identity-management/groups-role-settings.md)

---

### General Availability - Updated look and feel for Per-user MFA

**Type:** Plan for change    
**Service category:** MFA                       
**Product capability:** Identity Security & Protection              

As part of ongoing service improvements, we're making updates to the per-user MFA admin configuration experience to align with the look and feel of Azure. This change doesn't include any changes to the core functionality and will only include visual improvements. For more information, see: [Enable per-user Azure AD Multi-Factor Authentication to secure sign-in events](~/identity/authentication/howto-mfa-userstates.md).

---

### General Availability - Converged Authentication Methods in US Gov cloud

**Type:** New feature   
**Service category:** MFA                      
**Product capability:** User Authentication              

The Converged Authentication Methods Policy enables you to manage all authentication methods used for MFA and SSPR in one policy, migrate off the legacy MFA and SSPR policies, and target authentication methods to groups of users instead of enabling them for all users in the tenant. Customers should migrate management of authentication methods off the legacy MFA and SSPR policies before September 30, 2024. For more information, see: [Manage authentication methods for Azure AD](~/identity/authentication/concept-authentication-methods-manage.md).

---

### General Availability - Support for Directory Extensions using Azure AD cloud sync

**Type:** New feature
**Service category:** Provisioning
**Product capability:** Azure AD Connect cloud sync

Hybrid IT Admins can now sync both Active Directory and Azure AD Directory Extensions using Azure AD Connect cloud sync. This new capability adds the ability to dynamically discover the schema for both Active Directory and Azure Active Directory, thereby, allowing customers to map the needed attributes using the attribute mapping experience of cloud sync. For more information, see [Directory extensions and custom attribute mapping in cloud sync](~/identity/hybrid/cloud-sync/custom-attribute-mapping.md).

---

### Public Preview - Restricted Management Administrative Units

**Type:** New feature   
**Service category:** Directory Management                        
**Product capability:** Access Control               

Restricted Management Administrative Units allow you to restrict modification of users, security groups, and device in Azure AD so that only designated administrators can make changes.  Global Administrators and other tenant-level administrators can't modify the users, security groups, or devices that are added to a restricted management admin unit. For more information, see: [Restricted management administrative units in Azure Active Directory (Preview)](~/identity/role-based-access-control/admin-units-restricted-management.md).

---

### General Availability - Report suspicious activity integrated with Identity Protection

**Type:** Changed feature   
**Service category:** Identity Protection                        
**Product capability:** Identity Security & Protection              

Report suspicious activity is an updated implementation of the MFA fraud alert, where users can report a voice or phone app MFA prompt as suspicious. If enabled, users reporting prompts have their user risk set to high, enabling admins to use Identity Protection risk based policies or risk detection APIs to take remediation actions.  Report suspicious activity operates in parallel with the legacy MFA fraud alert at this time. For more information, see: [Configure Azure AD Multi-Factor Authentication settings](~/identity/authentication/howto-mfa-mfasettings.md).

---

## May 2023

### General Availability - Conditional Access authentication strength for members, external users and FIDO2 restrictions

**Type:** New feature   
**Service category:** Conditional Access                      
**Product capability:** Identity Security & Protection              

Authentication strength is a Conditional Access control that allows administrators to specify which combination of authentication methods can be used to access a resource. For example, they can make only phishing-resistant authentication methods available to access a sensitive resource. Likewise, to access a nonsensitive resource, they can allow less secure multifactor authentication (MFA) combinations such as password + SMS.

Authentication strength is now in General Availability for members and external users from any Microsoft cloud and FIDO2 restrictions. For more information, see: [Conditional Access authentication strength](~/identity/authentication/concept-authentication-strengths.md).

---

### General Availability - SAML/Ws-Fed based identity provider authentication for Azure Active Directory B2B users in US Sec and US Nat clouds

**Type:** New feature   
**Service category:** B2B                        
**Product capability:** B2B/B2C             

SAML/Ws-Fed based identity providers for authentication in Azure AD B2B are generally available in US Sec, US Nat and China clouds. For more information, see: [Federation with SAML/WS-Fed identity providers for guest users](~/external-id/direct-federation.md).

---

### Generally Availability - Cross-tenant synchronization

**Type:** New feature   
**Service category:** Provisioning                          
**Product capability:** Identity Lifecycle Management              

Cross-tenant synchronization allows you to set up a scalable and automated solution for users to access applications across tenants in your organization. It builds upon the Azure Active Directory B2B functionality and automates creating, updating, and deleting B2B users within tenants in your organization. For more information, see: [What is cross-tenant synchronization?](~/identity/multi-tenant-organizations/cross-tenant-synchronization-overview.md).

---

### Public Preview(Refresh) - Custom Extensions in Entitlement Management

**Type:** New feature   
**Service category:** Entitlement management                          
**Product capability:** Identity Governance                

Last year we announced the [public preview of custom extensions in Entitlement Management](https://techcommunity.microsoft.com/t5/microsoft-entra-azure-ad-blog/run-custom-workflows-in-azure-ad-entitlement-management/ba-p/2466938) allowing you to automate complex processes when access is requested or about to expire. We have recently expanded the public preview to allow for the access package assignment request to be paused while your external process is running. In addition, the external process can now provide feedback to Entitlement Management to either surface additional information to end users in MyAccess or even stop the access request. This expands the scenarios of custom extension from notifications to additional stakeholders or the generation of tickets to advanced scenarios such as external governance, risk and compliance checks. In the course of this update, we have also improved the audit logs, token security and the payload sent to the Logic App. To learn more about the preview refresh, see:

-  [Trigger Logic Apps with custom extensions in entitlement management (Preview)](~/id-governance/entitlement-management-logic-apps-integration.md)
- [accessPackageAssignmentRequest: resume](/graph/api/accesspackageassignmentrequest-resume)
- [accessPackageAssignmentWorkflowExtension resource type](/graph/api/resources/accesspackageassignmentworkflowextension)
- [accessPackageAssignmentRequestWorkflowExtension resource type](/graph/api/resources/accesspackageassignmentrequestworkflowextension)

---

### General Availability - Managed Identity in Microsoft Authentication Library for .NET

**Type:** New feature   
**Service category:** Authentications (Logins)                            
**Product capability:** User Authentication               

The latest version of MSAL.NET graduates the Managed Identity APIs into the General Availability mode of support, which means that developers can integrate them safely in production workloads.

Managed identities are a part of the Azure infrastructure, simplifying how developers handle credentials and secrets to access cloud resources. With Managed Identities, developers don't need to manually handle credential retrieval and security. Instead, they can rely on an automatically managed set of identities to connect to resources that support Azure Active Directory authentication. You can learn more in [What are managed identities for Azure resources?](~/identity/managed-identities-azure-resources/overview.md)

With MSAL.NET 4.54.0, the Managed Identity APIs are now stable. There are a few changes that we added that make them easier to use and integrate that might require tweaking your code if you’ve used our [experimental implementation](https://den.dev/blog/managed-identity-msal-net/):

- When using Managed Identity APIs, developers need to specify the identity type when creating an [ManagedIdentityApplication](/dotnet/api/microsoft.identity.client.managedidentityapplication).
- When acquiring tokens with Managed Identity APIs and using the default HTTP client, MSAL retries the request for certain exception codes.
- We added a new [MsalManagedIdentityException](/dotnet/api/microsoft.identity.client.msalmanagedidentityexception) class that represents any Managed Identity-related exceptions. It includes general exception information, including the Azure source from which the exception originates.
- MSAL will now proactively refresh tokens acquired with Managed Identity.

To get started with Managed Identity in MSAL.NET, you can use the [Microsoft.Identity.Client](/dotnet/api/microsoft.identity.client) package together with the [ManagedIdentityApplicationBuilder](/dotnet/api/microsoft.identity.client.managedidentityapplicationbuilder) class.

---

### Public Preview - New My Groups Experience

**Type:** Changed feature   
**Service category:** Group Management                          
**Product capability:** End User Experiences              

A new and improved My Groups experience is now available at [myaccount.microsoft.com/groups](https://myaccount.microsoft.com/groups). This experience replaces the existing My Groups experience at mygroups.microsoft.com in May.   For more information, see: [Update your Groups info in the My Apps portal](https://support.microsoft.com/account-billing/update-your-groups-info-in-the-my-apps-portal-bc0ca998-6d3a-42ac-acb8-e900fb1174a4).

---

### General Availability - Admins can restrict their users from creating tenants

**Type:** New feature   
**Service category:** User Access Management                           
**Product capability:** User Management               

The ability for users to create tenants from the Manage Tenant overview has been present in Azure AD since almost the beginning of the Azure portal.  This new capability in the User Settings pane allows admins to restrict their users from being able to create new tenants. There's also a new [Tenant Creator](~/identity/role-based-access-control/permissions-reference.md#tenant-creator) role to allow specific users to create tenants. For more information, see [Default user permissions](~/fundamentals/users-default-permissions.md#restrict-member-users-default-permissions).

---

### General Availability - Devices Self-Help Capability for Pending Devices



**Type:** New feature   
**Service category:** Device Access Management                
**Product capability:** End User Experiences          

In the **All Devices** view under the Registered column, you can now select any pending devices you have, and it opens a context pane to help troubleshoot why a device may be pending. You can also offer feedback on if the summarized information is helpful or not. For more information, see: [Pending devices in Azure Active Directory](/troubleshoot/azure/active-directory/pending-devices).


---

### General Availability - Admins can now restrict users from self-service accessing their BitLocker keys



**Type:** New feature   
**Service category:** Device Access Management                
**Product capability:** User Management            

Admins can now restrict their users from self-service accessing their BitLocker keys through the Devices Settings page. Turning on this capability hides the BitLocker key(s) of all non-admin users. This helps to control BitLocker access management at the admin level. For more information, see: [Restrict member users' default permissions](users-default-permissions.md#restrict-member-users-default-permissions).


---

### Public Preview - New provisioning connectors in the Azure AD Application Gallery - May 2023

**Type:** New feature   
**Service category:** App Provisioning               
**Product capability:** 3rd Party Integration    
      
We've added the following new applications in our App gallery with Provisioning support. You can now automate creating, updating, and deleting of user accounts for these newly integrated apps:

- [Sign In Enterprise Host Provisioning](~/identity/saas-apps/sign-in-enterprise-host-provisioning-tutorial.md)


For more information about how to better secure your organization by using automated user account provisioning, see: [Automate user provisioning to SaaS applications with Azure AD](~/identity/app-provisioning/user-provisioning.md).


---

### General Availability -  Microsoft Entra Permissions Management Azure Active Directory Insights

**Type:** New feature   
**Service category:** Other                               
**Product capability:** Permissions Management                 

The Azure Active Directory Insights tab in Microsoft Entra Permissions Management provides a view of all permanent role assignments assigned to Global Administrators, and a curated list of highly privileged roles. Administrators can then use the report to take further action within the Azure Active Directory console. For more information, see [View privileged role assignments in your organization (Preview)](~/permissions-management/product-privileged-role-insights.md).

---

### Public Preview - In portal guide to configure multi-factor authentication

**Type:** New feature   
**Service category:** MFA                           
**Product capability:** Identity Security & Protection              

The in portal guide to configure multi-factor authentication helps you get started with Azure Active Directory's MFA capabilities. You can find this guide under the Tutorials tab in the Azure AD Overview. 

---

### General Availability - Authenticator Lite (In Outlook)

**Type:** New feature   
**Service category:** Microsoft Authenticator App                           
**Product capability:** User Authentication                

Authenticator Lite (in Outlook) is an authentication solution for users that haven't yet downloaded the Microsoft Authenticator app. Users are prompted in Outlook on their mobile device to register for multi-factor authentication. After they enter their password at sign-in, they'll have the option to send a push notification to their Android or iOS device.

Due to the security enhancement this feature provides users, the Microsoft managed value of this feature will be changed from ‘*disabled*’ to ‘*enabled*’ on June 9. We’ve made some changes to the feature configuration, so if you made an update before GA, May 17, please validate that the feature is in the correct state for your tenant prior to June 9. If you don't wish for this feature to be enabled on June 9, move the state to ‘*disabled*’, or set users to include and exclude groups.  


For more information, see: [How to enable Microsoft Authenticator Lite for Outlook mobile (preview)](~/identity/authentication/how-to-mfa-authenticator-lite.md).

---

### General Availability - PowerShell and Web Services connector support through the Azure AD provisioning agent

**Type:** New feature   
**Service category:** Provisioning                          
**Product capability:** Outbound to On-premises Applications               

The Azure AD on-premises application provisioning feature now supports both the [PowerShell](~/identity/app-provisioning/on-premises-powershell-connector.md) and [web services](~/identity/app-provisioning/on-premises-web-services-connector.md) connectors. you can now provision users into a flat file using the PowerShell connector or an app such as SAP ECC using the web services connector. For more information, see: [Provisioning users into applications using PowerShell](~/identity/app-provisioning/on-premises-powershell-connector.md).

---

### General Availability - Verified threat actor IP sign-in detection

**Type:** New feature   
**Service category:** Identity Protection                          
**Product capability:** Identity Security & Protection               

Identity Protection has added a new detection, using the Microsoft Threat Intelligence database, to detect sign-ins performed from IP addresses of known nation state and cyber-crime actors and allow customers to block these sign-ins by using risk-based Conditional Access policies. For more information, see: [Sign-in risk](~/id-protection/concept-identity-protection-risks.md).

---

### General Availability - Conditional Access Granular control for external user types 

**Type:** New feature   
**Service category:** Conditional Access                            
**Product capability:** Identity Security & Protection               

When configuring a Conditional Access policy, customers now have granular control over the types of external users they want to apply the policy to. External users are categorized based on how they authenticate (internally or externally) and their relationship to your organization (guest or member). For more information, see: [Assigning Conditional Access policies to external user types](~/external-id/authentication-conditional-access.md#assigning-conditional-access-policies-to-external-user-types).

---

### General Availability - New Federated Apps available in Azure AD Application gallery - May 2023


**Type:** New feature   
**Service category:** Enterprise Apps                
**Product capability:** 3rd Party Integration          

In May 2023 we added the following 51 new applications in our App gallery with Federation support




[INEXTRACK](https://inexto.com/inexto-suite/inextrack), [Valotalive Digital Signage Microsoft 365 integration](https://valota.live/apps/microsoft-excel/), [Tailscale](http://tailscale.com/), [MANTL](https://console.mantl.com/), [ServusConnect](~/identity/saas-apps/servusconnect-tutorial.md), [Jigx MS Graph Demonstrator](https://www.jigx.com/), [Delivery Solutions](~/identity/saas-apps/delivery-solutions-tutorial.md), [Radiant IOT Portal](~/identity/saas-apps/radiant-iot-portal-tutorial.md), [Cosgrid Networks](~/identity/saas-apps/cosgrid-networks-tutorial.md), [voya SSO](https://app.voya.ai/), [Redocly](~/identity/saas-apps/redocly-tutorial.md), [Glaass Pro](https://glaass.net/pro/), [TalentLyftOIDC](https://www.talentlyft.com/en), [Cisco Expressway](~/identity/saas-apps/cisco-expressway-tutorial.md), [IBM TRIRIGA on Cloud](~/identity/saas-apps/ibm-tririga-on-cloud-tutorial.md), [Avionte Bold SAML Federated SSO](~/identity/saas-apps/avionte-bold-saml-federated-sso-tutorial.md), [InspectNTrack](http://www.inspecttrack.com/), [CAREERSHIP](~/identity/saas-apps/careership-tutorial.md), [Cisco Unity Connection](~/identity/saas-apps/cisco-unity-connection-tutorial.md), [HSC-Buddy](https://hsc-buddy.com/), [teamecho](https://app.teamecho.at/), [AskFora](https://askfora.com/), [Enterprise Bot](https://www.enterprisebot.ai/),[CMD+CTRL Base Camp](~/identity/saas-apps/cmd-ctrl-base-camp-tutorial.md), [Debitia Collections](https://www.debitia.com/), [EnergyManager](https://energymanager.no/), [Visual Workforce](https://prod.visualworkforce.com/), [Uplifter](https://uplifter.ai/), [AI2](https://tmti.net/services/), [TES Cloud](https://www.tes.ca/),[VEDA Cloud](~/identity/saas-apps/veda-cloud-tutorial.md), [SOC SST](~/identity/saas-apps/soc-sst-tutorial.md), [Alchemer](~/identity/saas-apps/alchemer-tutorial.md), [Cleanmail Swiss](https://www.alinto.com/fr/antispam-professionnel-cleanmail/), [WOX](https://woxday.com/), [WATS](https://wats.com/), [Data Quality Assistant](https://appsource.microsoft.com/en-GB/product/office/WA200004441?exp=kyyw&tab=Overview), [Softdrive](https://www.softdrive.co/), [Fluence Portal](https://portal.fluence.app/), [Humbol](https://www.humbol.app/en/product/), [Document360](~/identity/saas-apps/document360-tutorial.md), [Engage by Local Measure](https://www.localmeasure.com/),[Gate Property Management Software](https://gatesoftware.nl/), [Locus](~/identity/saas-apps/locus-tutorial.md), [Banyan Infrastructure](https://app.banyaninfrastructure.com/), [Proactis Rego Invoice Capture](~/identity/saas-apps/proactis-rego-invoice-capture-tutorial.md), [SecureTransport](~/identity/saas-apps/securetransport-tutorial.md), [Recnice](https://recnice.com/)

 
You can also find the documentation of all the applications from here https://aka.ms/AppsTutorial,

For listing your application in the Azure AD app gallery, please read the details here https://aka.ms/AzureADAppRequest

---

### General Availability - My Security-info now shows Microsoft Authenticator type

**Type:** Changed feature   
**Service category:** MFA                        
**Product capability:** Identity Security & Protection               

We have improved My Sign-ins and My Security-Info to give you more clarity on the types of Microsoft Authenticator or other Authenticator apps a user has registered. Users will now see Microsoft Authenticator registrations with additional information showing the app as being registered as Push-based MFA or Password-less phone sign-in (PSI) and for other Authenticator apps (Software OATH) we now indicate they're registered as a Time-based One-time password method.  For more information, see: [Set up the Microsoft Authenticator app as your verification method](https://support.microsoft.com/account-billing/set-up-the-microsoft-authenticator-app-as-your-verification-method-33452159-6af9-438f-8f82-63ce94cf3d29).

---

## April 2023

### Public Preview - Custom attributes for Azure Active Directory Domain Services

**Type:** New feature   
**Service category:** Azure Active Directory Domain Services                     
**Product capability:** Azure Active Directory Domain Services            

Azure Active Directory Domain Services will now support synchronizing custom attributes from Azure AD for on-premises accounts. For more information, see: [Custom attributes for Azure Active Directory Domain Services](/entra/identity/domain-services/concepts-custom-attributes).

---

### General Availability - Enablement of combined security information registration for MFA and  self-service password reset (SSPR)

**Type:** New feature   
**Service category:** MFA                     
**Product capability:** Identity Security & Protection            

Last year we announced the combined registration user experience for MFA and  self-service password reset (SSPR) was rolling out as the default experience for all organizations. We're happy to announce that the combined security information registration experience is now fully rolled out. This change doesn't affect tenants located in the China region. For more information, see: [Combined security information registration for Azure Active Directory overview](~/identity/authentication/concept-registration-mfa-sspr-combined.md).

---

### General Availability - System preferred MFA method

**Type:** Changed feature   
**Service category:** Authentications (Logins)                       
**Product capability:** Identity Security & Protection            

Currently, organizations and users rely on a range of authentication methods, each offering varying degrees of security. While Multifactor Authentication (MFA) is crucial, some MFA methods are more secure than others. Despite having access to more secure MFA options, users frequently choose less secure methods for various reasons.

To address this challenge, we're introducing a new system-preferred authentication method for MFA. When users sign in, the system will determine and display the most secure MFA method that the user has registered. This prompts users to switch from the default method to the most secure option. While users may still choose a different MFA method, they'll always be prompted to use the most secure method first for every session that requires MFA. For more information, see: [System-preferred multifactor authentication - Authentication methods policy](~/identity/authentication/concept-system-preferred-multifactor-authentication.md).

---

### General Availability - PIM alert: Alert on active-permanent role assignments in Azure or assignments made outside of PIM

**Type:** Fixed     
**Service category:** Privileged Identity Management                     
**Product capability:** Privileged Identity Management            

[Alert on Azure subscription role assignments made outside of Privileged Identity Management (PIM)](~/id-governance/privileged-identity-management/pim-resource-roles-configure-alerts.md) provides an alert in PIM for Azure subscription assignments made outside of PIM. An owner or User Access Administrator can take a quick remediation action to remove those assignments. 

---

### Public Preview - Enhanced Create User and Invite User Experiences

**Type:** Changed feature   
**Service category:** User Management                     
**Product capability:** User Management            

We have increased the number of properties that admins are able to define when creating and inviting a user in the Entra admin portal. This brings our UX to parity with our Create User APIs. Additionally, admins can now add users to a group or administrative unit, and assign roles. For more information, see:  [How to create, invite, and delete users](~/fundamentals/how-to-create-delete-users.md).

---

### Public Preview - Azure AD Conditional Access protected actions

**Type:** Changed feature   
**Service category:** RBAC                    
**Product capability:** Access Control            

The protected actions public preview introduces the ability to apply Conditional Access to select permissions. When a user performs a protected action, they must satisfy Conditional Access policy requirements. For more information, see: [What are protected actions in Azure AD? (preview)](~/identity/role-based-access-control/protected-actions-overview.md).

---

### Public Preview - Token Protection for Sign-in Sessions

**Type:** New feature   
**Service category:** Conditional Access                  
**Product capability:** User Authentication          

Token Protection for sign-in sessions is our first release on a road-map to combat attacks involving token theft and replay. It provides Conditional Access enforcement of token proof-of-possession for supported clients and services that ensure that access to specified resources is only from a device to which the user has signed in. For more information, see: [Conditional Access: Token protection (preview)](~/identity/conditional-access/concept-token-protection.md).

---

### General Availability- New limits on number and size of group secrets starting June 2023

**Type:** Plan for change  
**Service category:** Group Management                   
**Product capability:** Directory            

Starting in June 2023, the secrets stored on a single group can't exceed 48 individual secrets, or have a total size greater than 10 KB across all secrets on a single group. Groups with more than 10 KB of secrets will immediately stop working in June 2023. In June, groups exceeding 48 secrets are unable to increase the number of secrets they have, though they may still update or delete those secrets. We highly recommend reducing to fewer than 48 secrets by January 2024.

Group secrets are typically created when a group is assigned credentials to an app using Password-based single sign-on. To reduce the number of secrets assigned to a group, we recommend creating additional groups, and splitting up group assignments to your Password-based SSO applications across those new groups. For more information, see: [Add password-based single sign-on to an application](~/identity/enterprise-apps/configure-password-single-sign-on-non-gallery-applications.md).

---

### Public Preview - Authenticator Lite in Outlook

**Type:** New feature   
**Service category:** Microsoft Authenticator App                     
**Product capability:** User Authentication           

Authenticator Lite is an additional surface for Azure Active Directory users to complete multifactor authentication using push notifications on their Android or iOS device. With Authenticator Lite, users can satisfy a multifactor authentication requirement from the convenience of a familiar app. Authenticator Lite is currently enabled in the Outlook mobile app. Users may receive a notification in their Outlook mobile app to approve or deny, or use the Outlook app to generate an OATH verification code that can be entered during sign-in. The *'Microsoft managed'* setting for this feature will be set to be enabled on May 26, 2023. This enables the feature for all users in tenants where the feature is set to Microsoft managed. If you wish to change the state of this feature, please do so before May 26, 2023. For more information, see: [How to enable Microsoft Authenticator Lite for Outlook mobile (preview)](~/identity/authentication/how-to-mfa-authenticator-lite.md).

---

### General Availability - Updated look and feel for Per-user MFA

**Type:** Plan for change   
**Service category:** MFA                       
**Product capability:** Identity Security & Protection             

As part of ongoing service improvements, we're making updates to the per-user MFA admin configuration experience to align with the look and feel of Azure. This change doesn't include any changes to the core functionality and will only include visual improvements.  For more information, see: [Enable per-user Azure AD Multi-Factor Authentication to secure sign-in events](~/identity/authentication/howto-mfa-userstates.md).

---

### General Availability - Additional terms of use audit logs will be turned off

**Type:**  Fixed     
**Service category:** Terms of Use                  
**Product capability:** AuthZ/Access Delegation          

Due to a technical issue, we have recently started to emit additional audit logs for terms of use. The additional audit logs will be turned off by May 1 and are tagged with the core directory service and the agreement category. If you have built a dependency on the additional audit logs, you must switch to the regular audit logs tagged with the terms of use service.

---

### General Availability - New Federated Apps available in Azure AD Application gallery - April 2023



**Type:** New feature   
**Service category:** Enterprise Apps                
**Product capability:** 3rd Party Integration          

In April 2023 we've added the following 10 new applications in our App gallery with Federation support:    

[iTel Alert](https://www.itelalert.nl/), [goFLUENT](~/identity/saas-apps/gofluent-tutorial.md), [StructureFlow](https://app.structureflow.co/), [StructureFlow AU](https://au.structureflow.co/), [StructureFlow CA](https://ca.structureflow.co/), [StructureFlow EU](https://eu.structureflow.co/), [StructureFlow USA](https://us.structureflow.co/), [Predict360 SSO](~/identity/saas-apps/predict360-sso-tutorial.md), [Cegid Cloud](https://www.cegid.com/fr/nos-produits/), [HashiCorp Cloud Platform (HCP)](~/identity/saas-apps/hashicorp-cloud-platform-hcp-tutorial.md), [O'Reilly learning platform](~/identity/saas-apps/oreilly-learning-platform-tutorial.md), [LeftClick Web Services – RoomGuide](https://www.leftclick.cloud/digital_signage), [LeftClick Web Services – Sharepoint](https://www.leftclick.cloud/digital_signage), [LeftClick Web Services – Presence](https://www.leftclick.cloud/presence), [LeftClick Web Services - Single Sign-On](https://www.leftclick.cloud/presence), [InterPrice Technologies](http://www.interpricetech.com/), [WiggleDesk SSO](https://wiggledesk.com/), [Application Experience with Mist](https://www.mist.com/), [Connect Plans 360](https://connectplans360.com.au/), [Proactis Rego Source-to-Contract](~/identity/saas-apps/proactis-rego-source-to-contract-tutorial.md), [Danomics](https://www.danomics.com/), [Fountain](~/identity/saas-apps/fountain-tutorial.md), [Theom](~/identity/saas-apps/theom-tutorial.md), [DDC Web](~/identity/saas-apps/ddc-web-tutorial.md), [Dozuki](~/identity/saas-apps/dozuki-tutorial.md).


You can also find the documentation of all the applications from here https://aka.ms/AppsTutorial.

For listing your application in the Azure AD app gallery, read the details here https://aka.ms/AzureADAppRequest

---

### Public Preview - New provisioning connectors in the Azure AD Application Gallery - April 2023

**Type:** New feature   
**Service category:** App Provisioning               
**Product capability:** 3rd Party Integration    
      

We've added the following new applications in our App gallery with Provisioning support. You can now automate creating, updating, and deleting of user accounts for these newly integrated apps:

- [Alvao](~/identity/saas-apps/alvao-provisioning-tutorial.md)
- [Better Stack](~/identity/saas-apps/better-stack-provisioning-tutorial.md)
- [BIS](~/identity/saas-apps/bis-provisioning-tutorial.md)
- [Connecter](~/identity/saas-apps/connecter-provisioning-tutorial.md)
- [Howspace](~/identity/saas-apps/howspace-provisioning-tutorial.md)
- [Kno2fy](~/identity/saas-apps/kno2fy-provisioning-tutorial.md)
- [Netsparker Enterprise](~/identity/saas-apps/netsparker-enterprise-provisioning-tutorial.md)
- [uniFLOW Online](~/identity/saas-apps/uniflow-online-provisioning-tutorial.md)


For more information about how to better secure your organization by using automated user account provisioning, see: [Automate user provisioning to SaaS applications with Azure AD](~/identity/app-provisioning/user-provisioning.md).


---

### Public Preview - New PIM Azure resource picker

**Type:** Changed feature   
**Service category:** Privileged Identity Management                     
**Product capability:** End User Experiences            

With this new experience, PIM now automatically manages any type of resource in a tenant, so discovery and activation is no longer required. With the new resource picker, users can directly choose the scope they want to manage from the Management Group down to the resources themselves, making it faster and easier to locate the resources they need to administer. For more information, see: [Assign Azure resource roles in Privileged Identity Management](~/id-governance/privileged-identity-management/pim-resource-roles-assign-roles.md).

---

### General availability - Self Service Password Reset (SSPR) now supports PIM eligible users and indirect group role assignment

**Type:** Changed feature   
**Service category:** Self Service Password Reset                     
**Product capability:** Identity Security & Protection          

Self Service Password Reset (SSPR) can now check for PIM eligible users, and evaluate group-based memberships, along with direct memberships when checking if a user is in a particular administrator role. This capability provides more accurate SSPR policy enforcement by validating if users are in scope for the default SSPR admin policy or your organizations SSPR user policy.


For more information, see: 

- [Administrator reset policy differences](~/identity/authentication/concept-sspr-policy.md#administrator-reset-policy-differences).
- [Create a role-assignable group in Azure Active Directory](~/identity/role-based-access-control/groups-create-eligible.md)

---

## March 2023


### Public Preview - New provisioning connectors in the Azure AD Application Gallery - March 2023

**Type:** New feature   
**Service category:** App Provisioning               
**Product capability:** 3rd Party Integration    
      

We've added the following new applications in our App gallery with Provisioning support. You can now automate creating, updating, and deleting of user accounts for these newly integrated apps:

- [Acunetix 360](~/identity/saas-apps/acunetix-360-provisioning-tutorial.md)
- [Akamai Enterprise Application Access](~/identity/saas-apps/akamai-enterprise-application-access-provisioning-tutorial.md)
- [Ardoq](~/identity/saas-apps/ardoq-provisioning-tutorial.md)
- [Torii](~/identity/saas-apps/torii-provisioning-tutorial.md)


For more information about how to better secure your organization by using automated user account provisioning, see: [Automate user provisioning to SaaS applications with Azure AD](~/identity/app-provisioning/user-provisioning.md).


---

### General Availability - Workload identity Federation for Managed Identities

**Type:** New feature   
**Service category:** Managed identities for Azure resources                     
**Product capability:** Developer Experience             

Workload Identity Federation enables developers to use managed identities for their software workloads running anywhere and access Azure resources without needing secrets. Key scenarios include:
- Accessing Azure resources from Kubernetes pods running in any cloud or on-premises
- GitHub workflows to deploy to Azure, no secrets necessary
- Accessing Azure resources from other cloud platforms that support OIDC, such as Google Cloud Platform.

For more information, see: 
- [Workload identity federation](~/workload-id/workload-identity-federation.md).
- [Configure a user-assigned managed identity to trust an external identity provider (preview)](~/workload-id/workload-identity-federation-create-trust-user-assigned-managed-identity.md)
- [Use Azure AD workload identity with Azure Kubernetes Service (AKS)](/azure/aks/workload-identity-overview)

---

### Public Preview - New My Groups Experience

**Type:** Changed feature   
**Service category:** Group Management                   
**Product capability:** End User Experiences          

A new and improved My Groups experience is now available at `https://www.myaccount.microsoft.com/groups`. My Groups enables end users to easily manage groups, such as finding groups to join, managing groups they own, and managing existing group memberships. Based on customer feedback, the new My Groups support sorting and filtering on lists of groups and group members, a full list of group members in large groups, and an actionable overview page for membership requests.
This experience replaces the existing My Groups experience at `https://www.mygroups.microsoft.com` in May.  


For more information, see: [Update your Groups info in the My Apps portal](https://support.microsoft.com/account-billing/update-your-groups-info-in-the-my-apps-portal-bc0ca998-6d3a-42ac-acb8-e900fb1174a4).

---

### Public preview - Customize tokens with Custom Claims Providers

**Type:** New feature   
**Service category:** Authentications (Logins)                      
**Product capability:** Extensibility             

A custom claims provider lets you call an API and map custom claims into the token during the authentication flow. The API call is made after the user has completed all their authentication challenges, and a token is about to be issued to the app. For more information, see: [Custom authentication extensions (preview)](~/identity-platform/custom-claims-provider-overview.md).

---

### General Availability - Converged Authentication Methods

**Type:** New feature   
**Service category:** MFA                     
**Product capability:** User Authentication             

The Converged Authentication Methods Policy enables you to manage all authentication methods used for MFA and SSPR in one policy, migrate off the legacy MFA and SSPR policies, and target authentication methods to groups of users instead of enabling them for all users in your tenant. For more information, see: [Manage authentication methods](~/identity/authentication/concept-authentication-methods-manage.md).

---

### General Availability - Provisioning Insights Workbook

**Type:** New feature   
**Service category:** Provisioning                     
**Product capability:** Monitoring & Reporting            

This new workbook makes it easier to investigate and gain insights into your provisioning workflows in a given tenant. This includes HR-driven provisioning, cloud sync, app provisioning, and cross-tenant sync.

Some key questions this workbook can help answer are:

- How many identities have been synced in a given time range?
- How many create, delete, update, or other operations were performed?
- How many operations were successful, skipped, or failed?
- What specific identities failed? And what step did they fail on?
- For any given user, what tenants / applications were they provisioned or deprovisioned to?

For more information, see: [Provisioning insights workbook](~/identity/app-provisioning/provisioning-workbook.md).

---

### General Availability - Number Matching for Microsoft Authenticator notifications

**Type:** Plan for Change  
**Service category:** Microsoft Authenticator App                      
**Product capability:** User Authentication             

Microsoft Authenticator app’s number matching feature has been Generally Available since Nov 2022! If you haven't already used the rollout controls (via Azure portal Admin UX and MSGraph APIs) to smoothly deploy number matching for users of Microsoft Authenticator push notifications, we highly encourage you to do so. We previously announced that we'll remove the admin controls and enforce the number match experience tenant-wide for all users of Microsoft Authenticator push notifications starting February 27, 2023. After listening to customers, we'll extend the availability of the rollout controls for a few more weeks. Organizations can continue to use the existing rollout controls until May 8, 2023, to deploy number matching in their organizations. Microsoft services will start enforcing the number matching experience for all users of Microsoft Authenticator push notifications after May 8, 2023. We'll also remove the rollout controls for number matching after that date.

If customers don’t enable number match for all Microsoft Authenticator push notifications prior to May 8, 2023, Authenticator users may experience inconsistent sign-ins while the services are rolling out this change. To ensure consistent behavior for all users, we highly recommend you enable number match for Microsoft Authenticator push notifications in advance.

For more information, see: [How to use number matching in multifactor authentication (MFA) notifications - Authentication methods policy](~/identity/authentication/how-to-mfa-number-match.md)

---

### Public Preview - IPv6 coming to Azure AD

**Type:** Plan for Change     
**Service category:** Identity Protection                     
**Product capability:** Platform             

Earlier, we announced our plan to bring IPv6 support to Microsoft Azure Active Directory (Azure AD), enabling our customers to reach the Azure AD services over IPv4, IPv6 or dual stack endpoints. This is just a reminder that we have started introducing IPv6 support into Azure AD services in a phased approach in late March 2023.  
 
If you utilize Conditional Access or Identity Protection, and have IPv6 enabled on any of your devices, you likely must take action to avoid impacting your users. For most customers, IPv4 won't completely disappear from their digital landscape, so we aren't planning to require IPv6 or to deprioritize IPv4 in any Azure AD features or services. We continue to share additional guidance on IPv6 enablement in Azure AD at this link: [IPv6 support in Azure Active Directory](/troubleshoot/azure/active-directory/azure-ad-ipv6-support).

---

### General Availability - Microsoft cloud settings for Azure AD B2B

**Type:** New feature  
**Service category:** B2B              
**Product capability:** B2B/B2C       

Microsoft cloud settings let you collaborate with organizations from different Microsoft Azure clouds. With Microsoft cloud settings, you can establish mutual B2B collaboration between the following clouds:

- Microsoft Azure commercial and Microsoft Azure Government
- Microsoft Azure commercial and Microsoft Azure operated by 21Vianet

For more information about Microsoft cloud settings for B2B collaboration, see [Microsoft cloud settings](~/external-id/cross-tenant-access-overview.md#microsoft-cloud-settings).

---

### Modernizing Terms of Use Experiences

**Type:** Plan for Change  
**Service category:** Terms of use                  
**Product capability:** AuthZ/Access Delegation        

Starting July 2023, we're modernizing the following Terms of Use end user experiences with an updated PDF viewer, and moving the experiences from https://account.activedirectory.windowsazure.com to https://myaccount.microsoft.com:
- View previously accepted terms of use.
- Accept or decline terms of use as part of the sign-in flow.

No functionalities are removed. The new PDF viewer adds functionality and the limited visual changes in the end-user experiences will be communicated in a future update. If your organization has allow-listed only certain domains, you must ensure your allowlist includes the domains ‘myaccount.microsoft.com’ and ‘*.myaccount.microsoft.com’ for Terms of Use to continue working as expected.

---


## February 2023

### General Availability - Expanding Privileged Identity Management Role Activation across the Azure portal

**Type:** New feature   
**Service category:** Privileged Identity Management                    
**Product capability:** Privileged Identity Management           

Privileged Identity Management (PIM) role activation has been expanded to the Billing and AD extensions in the Azure portal. Shortcuts have been added to Subscriptions (billing) and Access Control (AD) to allow users to activate PIM roles directly from these settings. From the Subscriptions settings, select **View eligible subscriptions** in the horizontal command menu to check your eligible, active, and expired assignments. From there, you can activate an eligible assignment in the same pane. In Access control (IAM) for a resource, you can now select **View my access** to see your currently active and eligible role assignments and activate directly. By integrating PIM capabilities into different Azure portal blades, this new feature allows users to gain temporary access to view or edit subscriptions and resources more easily.


For more information Microsoft cloud settings, see: [Activate my Azure resource roles in Privileged Identity Management](~/id-governance/privileged-identity-management/pim-resource-roles-activate-your-roles.md).

---

### General Availability - Follow Azure AD best practices with recommendations

**Type:** New feature   
**Service category:** Reporting                  
**Product capability:** Monitoring & Reporting            

Azure AD recommendations help you improve your tenant posture by surfacing opportunities to implement best practices. On a daily basis, Azure AD analyzes the configuration of your tenant. During this analysis, Azure AD compares the data of a recommendation with the actual configuration of your tenant. If a recommendation is flagged as applicable to your tenant, the recommendation appears in the Recommendations section of the Azure AD Overview. 

This release includes our first 3 recommendations:

- Convert from per-user MFA to Conditional Access MFA
- Migration applications from AD FS to Azure AD
- Minimize MFA prompts from known devices


For more information, see: 

- [What are Azure Active Directory recommendations?](~/identity/monitoring-health/overview-recommendations.md)
- [Use the Azure AD recommendations API to implement Azure AD best practices for your tenant](/graph/api/resources/recommendations-api-overview)

---

### Public Preview - Azure AD PIM + Conditional Access integration

**Type:** New feature   
**Service category:** Privileged Identity Management                    
**Product capability:** Privileged Identity Management               

Now you can require users who are eligible for a role to satisfy Conditional Access policy requirements for activation: use specific authentication method enforced through Authentication Strengths, activate from Intune compliant device, comply with Terms of Use, and use 3rd party MFA and satisfy location requirements.

For more information, see: [Configure Azure AD role settings in Privileged Identity Management](~/id-governance/privileged-identity-management/pim-how-to-change-default-settings.md).


---

### General Availability - More information on why a sign-in was flagged as "unfamiliar"

**Type:** Changed feature   
**Service category:** Identity Protection                    
**Product capability:** Identity Security & Protection           

Unfamiliar sign-in properties risk detection now provides risk reasons as to which properties are unfamiliar for customers to better investigate that risk. 

Identity Protection now surfaces the unfamiliar properties in the Azure portal on UX and in API as *Additional Info* with a user-friendly description explaining that *the following properties are unfamiliar for this sign-in of the given user*. 

There's no additional work to enable this feature, the unfamiliar properties are shown by default. For more information, see: [Sign-in risk](~/id-protection/concept-identity-protection-risks.md).


---

### General Availability - New Federated Apps available in Azure AD Application gallery - February 2023



**Type:** New feature   
**Service category:** Enterprise Apps                
**Product capability:** 3rd Party Integration          

In February 2023 we've added the following 10 new applications in our App gallery with Federation support:    

[PROCAS](https://accounting.procas.com/), [Tanium Cloud SSO](~/identity/saas-apps/tanium-sso-tutorial.md), [LeanDNA](~/identity/saas-apps/leandna-tutorial.md), [CalendarAnything LWC](https://silverlinecrm.com/calendaranything/), [courses.work](~/identity/saas-apps/courseswork-tutorial.md), [Udemy Business SAML](~/identity/saas-apps/udemy-business-saml-tutorial.md), [Canva](~/identity/saas-apps/canva-tutorial.md), [Kno2fy](~/identity/saas-apps/kno2fy-tutorial.md), [IT-Conductor](~/identity/saas-apps/it-conductor-tutorial.md), [ナレッジワーク(Knowledge Work)](~/identity/saas-apps/knowledge-work-tutorial.md), [Valotalive Digital Signage Microsoft 365 integration](https://store.valotalive.com/#main), [Priority Matrix HIPAA](https://hipaa.prioritymatrix.com/), [Priority Matrix Government](https://hipaa.prioritymatrix.com/), [Beable](~/identity/saas-apps/beable-tutorial.md), [Grain](https://grain.com/app?dialog=integrations&integration=microsoft+teams), [DojoNavi](~/identity/saas-apps/dojonavi-tutorial.md), [Global Validity Access Manager](https://myaccessmanager.com/), [FieldEquip](https://app.fieldequip.com/), [Peoplevine](https://control.peoplevine.com/), [Respondent](~/identity/saas-apps/respondent-tutorial.md), [WebTMA](~/identity/saas-apps/webtma-tutorial.md), [ClearIP](https://clearip.com/login), [Pennylane](~/identity/saas-apps/pennylane-tutorial.md), [VsimpleSSO](https://app.vsimple.com/login), [Compliance Genie](~/identity/saas-apps/compliance-genie-tutorial.md), [Dataminr Corporate](https://dmcorp.okta.com/), [Talon](~/identity/saas-apps/talon-tutorial.md). 


You can also find the documentation of all the applications from here https://aka.ms/AppsTutorial.

For listing your application in the Azure AD app gallery, read the details here https://aka.ms/AzureADAppRequest

---

### Public Preview - New provisioning connectors in the Azure AD Application Gallery - February 2023

**Type:** New feature   
**Service category:** App Provisioning               
**Product capability:** 3rd Party Integration    
      

We've added the following new applications in our App gallery with Provisioning support. You can now automate creating, updating, and deleting of user accounts for these newly integrated apps:

- [Atmos](~/identity/saas-apps/atmos-provisioning-tutorial.md)


For more information about how to better secure your organization by using automated user account provisioning, see: [Automate user provisioning to SaaS applications with Azure AD](~/identity/app-provisioning/user-provisioning.md).


---


## January 2023

### Public Preview - Cross-tenant synchronization

**Type:** New feature   
**Service category:** Provisioning               
**Product capability:** Collaboration          

Cross-tenant synchronization allows you to set up a scalable and automated solution for users to access applications across tenants in your organization. It builds upon the Azure AD B2B functionality and automates creating, updating, and deleting B2B users. For more information, see: [What is cross-tenant synchronization? (preview)](~/identity/multi-tenant-organizations/cross-tenant-synchronization-overview.md).


---

### General Availability - New Federated Apps available in Azure AD Application gallery - January 2023



**Type:** New feature   
**Service category:** Enterprise Apps                
**Product capability:** 3rd Party Integration          

In January 2023 we've added the following 10 new applications in our App gallery with Federation support:

[MINT TMS](~/identity/saas-apps/mint-tms-tutorial.md),  [Exterro Legal GRC Software Platform](~/identity/saas-apps/exterro-legal-grc-software-platform-tutorial.md), [SIX.ONE Identity Access Manager](https://portal.six.one/), [Lusha](~/identity/saas-apps/lusha-tutorial.md), [Descartes](~/identity/saas-apps/descartes-tutorial.md), [Travel Management System](https://tms.billetkontoret.dk/), [Pinpoint (SAML)](~/identity/saas-apps/pinpoint-tutorial.md), [my.sdworx.com](~/identity/saas-apps/mysdworxcom-tutorial.md), [itopia Labs](https://labs.itopia.com/), [Better Stack](https://betteruptime.com/users/sign-up).

You can also find the documentation of all the applications from here https://aka.ms/AppsTutorial.

For listing your application in the Azure AD app gallery, read the details here https://aka.ms/AzureADAppRequest


---

### Public Preview - New provisioning connectors in the Azure AD Application Gallery - January 2023



**Type:** New feature   
**Service category:** App Provisioning               
**Product capability:** 3rd Party Integration         

We've added the following new applications in our App gallery with Provisioning support. You can now automate creating, updating, and deleting of user accounts for these newly integrated apps:

- [SurveyMonkey Enterprise](~/identity/saas-apps/surveymonkey-enterprise-provisioning-tutorial.md)


For more information about how to better secure your organization by using automated user account provisioning, see: [Automate user provisioning to SaaS applications with Azure AD](~/identity/app-provisioning/user-provisioning.md).


---

### Public Preview - Azure AD Connect cloud sync new user experience


**Type:** Changed feature
**Service category:** Azure AD Connect cloud sync
**Product capability:** Identity Governance

Try out the new guided experience for syncing objects from AD to Azure AD using Azure AD Connect cloud sync in Azure portal. With this new experience, Hybrid Identity Administrators can easily determine which sync engine to use for their scenarios and learn more about the various options they have with our sync solutions. With a rich set of tutorials and videos, customers are able to learn everything about Azure AD Connect cloud sync in one single place. 

This experience helps administrators walk through the different steps involved in setting up a cloud sync configuration and an intuitive experience to help them easily manage it. Admins can also get insights into their sync configuration by using the "Insights" option, which integrates with Azure Monitor and Workbooks. 

For more information, see:

- [Create a new configuration for Azure AD Connect cloud sync](~/identity/hybrid/cloud-sync/how-to-configure.md)
- [Attribute mapping in Azure AD Connect cloud sync](~/identity/hybrid/cloud-sync/how-to-attribute-mapping.md)
- [Azure AD Connect cloud sync insights workbook](~/identity/hybrid/cloud-sync/how-to-cloud-sync-workbook.md)

---

### Public Preview - Support for Directory Extensions using Azure AD Connect cloud sync

**Type:** New feature   
**Service category:** Provisioning               
**Product capability:** Azure AD Connect cloud sync         

Hybrid IT Admins now can sync both Active Directory and Azure AD Directory Extensions using Azure AD cloud sync. This new capability adds the ability to dynamically discover the schema for both Active Directory and Azure AD, allowing customers to map the needed attributes using the attribute mapping experience of Azure AD Connect cloud sync.

For more information on how to enable this feature, see [Directory extensions and custom attribute mapping in Azure AD Connect cloud sync](~/identity/hybrid/cloud-sync/custom-attribute-mapping.md)


---


## December 2022

### Public Preview - Windows 10+ Troubleshooter for Diagnostic Logs



**Type:** New feature   
**Service category:** Audit             
**Product capability:** Monitoring & Reporting       

This feature analyzes uploaded client-side logs, also known as diagnostic logs, from a Windows 10+ device that is having an issue(s) and suggests remediation steps to resolve the issue(s). Admins can work with end user to collect client-side logs, and then upload them to this troubleshooter in the Microsoft Entra admin center. For more information, see: [Troubleshooting Windows devices in Azure AD](~/identity/devices/troubleshoot-device-windows-joined.md).


---

### General Availability - Multiple Password-less Phone Sign-ins for iOS Devices



**Type:** New feature   
**Service category:** Authentications (Logins)            
**Product capability:** User Authentication     

End users can now enable password-less phone sign-in for multiple accounts in the Authenticator App on any supported iOS device. Consultants, students, and others with multiple accounts in Azure AD can add each account to Microsoft Authenticator and use password-less phone sign-in for all of them from the same iOS device. The Azure AD accounts can be in the same tenant or different tenants. Guest accounts aren't supported for multiple account sign-ins from one device.


End users aren't required to enable the optional telemetry setting in the Authenticator App. For more information, see: [Enable passwordless sign-in with Microsoft Authenticator](~/identity/authentication/howto-authentication-passwordless-phone.md).


---

### Public Preview(refresh) - Updates to Conditional Access templates 



**Type:** Changed feature   
**Service category:** Conditional Access             
**Product capability:** Identity Security & Protection        

Conditional Access templates provide a convenient method to deploy new policies aligned with Microsoft recommendations. In total, there are 14 Conditional Access policy templates, filtered by five different scenarios; secure foundation, zero trust, remote work, protect administrators, and emerging threats.  

In this Public Preview refresh, we've enhanced the user experience with an updated design and added four new improvements: 

- Admins can create a Conditional Access policy by importing a JSON file.
- Admins can duplicate existing policy.
- Admins can view more detailed policy information.
- Admins can query templates programmatically via MSGraph API.


For more information, see: [Conditional Access templates (Preview)](~/identity/conditional-access/concept-conditional-access-policy-common.md).

---

### Public Preview - Admins can restrict their users from creating tenants



**Type:** New feature   
**Service category:** User Access Management             
**Product capability:** User Management       

The ability for users to create tenants from the Manage Tenant overview has been present in Azure AD since almost the beginning of the Azure portal. This new capability in the User Settings option allows admins to restrict their users from being able to create new tenants. There's also a new [Tenant Creator](~/identity/role-based-access-control/permissions-reference.md#tenant-creator) role to allow specific users to create tenants. For more information, see [Default user permissions](~/fundamentals/users-default-permissions.md#restrict-member-users-default-permissions).


---

### General availability - Consolidated App launcher (My Apps) settings and new preview settings



**Type:** New feature   
**Service category:** My Apps            
**Product capability:** End User Experiences      

We have consolidated relevant app launcher settings in a new App launchers section in the Azure and Microsoft Entra admin centers. The entry point can be found under Enterprise applications, where Collections used to be. You can find the Collections option by selecting App launchers. In addition, we've added a new App launchers Settings option. This option has some settings you may already be familiar with like the Microsoft 365 settings. The new Settings options also have controls for previews. As an admin, you can choose to try out new app launcher features while they are in preview. Enabling a preview feature means that the feature turns on for your organization. This enabled feature reflects in the My Apps portal, and other app launchers for all of your users. To learn more about the preview settings, see: [End-user experiences for applications](~/identity/enterprise-apps/end-user-experiences.md).


---

### Public preview - Converged Authentication Methods Policy



**Type:** New feature   
**Service category:** MFA          
**Product capability:** User Authentication     

The Converged Authentication Methods Policy enables you to manage all authentication methods used for MFA and SSPR in one policy. You can migrate off the legacy MFA and SSPR policies, and target authentication methods to groups of users instead of enabling them for all users in the tenant. For more information, see: [Manage authentication methods for Azure AD](~/identity/authentication/concept-authentication-methods-manage.md).


---

### General Availability - Administrative unit support for devices



**Type:** New feature   
**Service category:** Directory Management             
**Product capability:** AuthZ/Access Delegation       

You can now use administrative units to delegate management of specified devices in your tenant by adding devices to an administrative unit. You're also able to assign built-in, and custom device management roles, scoped to that administrative unit. For more information, see: [Device management](~/identity/role-based-access-control/administrative-units.md#device-management).


---

### Public Preview - Frontline workers using shared devices can now use Microsoft Edge and Yammer apps on Android



**Type:** New feature   
**Service category:** N/A          
**Product capability:** SSO       

Companies often provide mobile devices to frontline workers that need are shared between shifts. Microsoft’s shared device mode allows frontline workers to easily authenticate by automatically signing users in and out of all the apps that have enabled this feature. In addition to Microsoft Teams and Managed Home Screen being generally available, we're excited to announce that Microsoft Edge and Yammer apps on Android are now in Public Preview.

For more information on deploying frontline solutions, see: [frontline deployment documentation](https://aka.ms/frontlinewhitepaper).


For more information on shared-device mode, see: [Azure Active Directory Shared Device Mode documentation](~/identity-platform/msal-android-shared-devices.md#microsoft-applications-that-support-shared-device-mode).


For steps to set up shared device mode with Intune, see: [Intune setup blog](https://techcommunity.microsoft.com/t5/intune-customer-success/enroll-android-enterprise-dedicated-devices-into-azure-ad-shared/ba-p/1820093). 


---

### Public preview - New provisioning connectors in the Azure AD Application Gallery - December 2022



**Type:** New feature   
**Service category:** App Provisioning             
**Product capability:** 3rd Party Integration     

We've added the following new applications in our App gallery with Provisioning support. You can now automate creating, updating, and deleting of user accounts for these newly integrated apps:

- [GHAE](~/identity/saas-apps/ghae-provisioning-tutorial.md)


For more information about how to better secure your organization by using automated user account provisioning, see: [Automate user provisioning to SaaS applications with Azure AD](~/identity/app-provisioning/user-provisioning.md).


---

### General Availability - On-premises application provisioning



**Type:** Changed feature   
**Service category:** Provisioning            
**Product capability:** Outbound to On-premises Applications        

Azure AD supports provisioning users into applications hosted on-premises or in a virtual machine, without having to open up any firewalls. If your application supports [SCIM](https://techcommunity.microsoft.com/t5/identity-standards-blog/provisioning-with-scim-getting-started/ba-p/880010), or you've built a SCIM gateway to connect to your legacy application, you can use the Azure AD Provisioning agent to [directly connect](~/identity/app-provisioning/on-premises-scim-provisioning.md) with your application and automate provisioning and deprovisioning. If you have legacy applications that don't support SCIM and rely on an [LDAP](~/identity/app-provisioning/on-premises-ldap-connector-configure.md) user store, or a [SQL](~/identity/app-provisioning/tutorial-ecma-sql-connector.md) database, Azure AD can support those as well.


---

### General Availability - New Federated Apps available in Azure AD Application gallery - December 2022



**Type:** New feature   
**Service category:** Enterprise Apps              
**Product capability:** 3rd Party Integration         

In December 2022 we've added the following 44 new applications in our App gallery with Federation support:

[Bionexo IDM](https://login.bionexo.com/), [SMART Meeting Pro](https://www.smarttech.com/en/business/software/meeting-pro), [Venafi Control Plane – Datacenter](~/identity/saas-apps/venafi-control-plane-tutorial.md), [HighQ](~/identity/saas-apps/highq-tutorial.md), [Drawboard PDF](https://pdf.drawboard.com/), [ETU Skillsims](~/identity/saas-apps/etu-skillsims-tutorial.md), [TencentCloud IDaaS](~/identity/saas-apps/tencent-cloud-idaas-tutorial.md), [TeamHeadquarters Email Agent OAuth](https://thq.entry.com/), [Verizon MDM](https://verizonmdm.vzw.com/), [QRadar SOAR](~/identity/saas-apps/qradar-soar-tutorial.md), [Tripwire Enterprise](~/identity/saas-apps/tripwire-enterprise-tutorial.md), [Cisco Unified Communications Manager](~/identity/saas-apps/cisco-unified-communications-manager-tutorial.md), [Howspace](https://login.in.howspace.com/), [Flipsnack SAML](~/identity/saas-apps/flipsnack-saml-tutorial.md), [Albert](http://www.albertinvent.com/), [Altinget.no](https://www.altinget.no/), [Coveo Hosted Services](~/identity/saas-apps/coveo-hosted-services-tutorial.md), [Cybozu(cybozu.com)](~/identity/saas-apps/cybozu-tutorial.md), [BombBomb](https://app.bombbomb.com/app), [VMware Identity Service](~/identity/saas-apps/vmware-identity-service-tutorial.md), [HexaSync](https://app-az.hexasync.com/login), [Trifecta Teams](https://app.trifectateams.net/), [VerosoftDesign](https://verosoft-design.vercel.app/), [Mazepay](https://app.mazepay.com/), [Wistia](~/identity/saas-apps/wistia-tutorial.md), [Begin.AI](https://app.begin.ai/), [WebCE](~/identity/saas-apps/webce-tutorial.md), [Dream Broker Studio](https://dreambroker.com/studio/login/), [PKSHA Chatbot](~/identity/saas-apps/pksha-chatbot-tutorial.md), [PGM-BCP](https://ups-pgm-bcp.4gfactor.com/azure/), [ChartDesk SSO](~/identity/saas-apps/chartdesk-sso-tutorial.md), [Elsevier SP](~/identity/saas-apps/elsevier-sp-tutorial.md), [GreenCommerce IdentityServer](https://identity.jem-id.nl/Account/Login), [Fullview](https://app.fullview.io/sign-in), [Aqua Platform](~/identity/saas-apps/aqua-platform-tutorial.md), [SpedTrack](~/identity/saas-apps/spedtrack-tutorial.md), [Pinpoint](https://pinpoint.ddiworld.com/psg2?sso=true), [Darzin Outlook Add-in](https://outlook.darzin.com/graph-login.html), [Simply Stakeholders Outlook Add-in](https://outlook.simplystakeholders.com/graph-login.html), [tesma](~/identity/saas-apps/tesma-tutorial.md), [Parkable](~/identity/saas-apps/parkable-tutorial.md), [Unite Us](~/identity/saas-apps/unite-us-tutorial.md)

You can also find the documentation of all the applications from here https://aka.ms/AppsTutorial,

For listing your application in the Azure AD app gallery, read the details here https://aka.ms/AzureADAppRequest

---

### Microsoft Authentication Library End of Support Announcement

**Type:** N/A      
**Service category:** Other               
**Product capability:** Developer Experience         

As part of our ongoing initiative to improve the developer experience, service reliability, and security of customer applications, we end support for the Microsoft Authentication Library (Microsoft Authentication Library). The final deadline to migrate your applications to Microsoft Authentication Library (MSAL) has been extended to **June 30, 2023**. 

### Why are we doing this?

As we consolidate and evolve the Microsoft Identity platform, we're also investing in making significant improvements to the developer experience and service features that make it possible to build secure, robust and resilient applications. To make these features available to our customers, we needed to update the architecture of our software development kits. As a result of this change, we’ve decided that the path forward requires us to sunset Microsoft Authentication Library. This allows us to focus on developer experience investments with Microsoft Authentication Library. 

### What happens?

We recognize that changing libraries isn't an easy task, and can't be accomplished quickly. We're committed to helping customers plan their migrations to Microsoft Authentication Library and execute them with minimal disruption.

- In June 2020, we [announced the 2-year end of support timeline for Microsoft Authentication Library](https://devblogs.microsoft.com/microsoft365dev/end-of-support-timelines-for-azure-ad-authentication-library-adal-and-azure-ad-graph/). 
- In December 2022, we’ve decided to extend the Microsoft Authentication Library end of support to June 2023. 
- Through the next six months (January 2023 – June 2023) we continue informing customers about the upcoming end of support along with providing guidance on migration. 
- On June 2023 we'll officially sunset Microsoft Authentication Library, removing library documentation and archiving all GitHub repositories related to the project. 

### How to find out which applications in my tenant are using Microsoft Authentication Library?

Refer to our post on [Microsoft Q&A](/answers/questions/360928/information-how-to-find-apps-using-adal-in-your-te) for details on identifying Microsoft Authentication Library apps with the help of [Azure Workbooks](/azure/azure-monitor/visualize/workbooks-overview).
### If I’m using Microsoft Authentication Library, what can I expect after the deadline? 

- There will be no new releases (security or otherwise) to the library after June 2023. 
- We won't accept any incident reports or support requests for Microsoft Authentication Library. Microsoft Authentication Library to Microsoft Authentication Library migration support would continue.   
- The underpinning services continue working and applications that depend on Microsoft Authentication Library should continue working. Applications, and the resources they access, are at increased security and reliability risk due to not having the latest updates, service configuration, and enhancements made available through the Microsoft Identity platform. 

### What features can I only access with Microsoft Authentication Library?

The number of features and capabilities that we're adding to Microsoft Authentication Library libraries are growing weekly. Some of them include: 
- Support for Microsoft accounts (MSA) 
- Support for Azure AD B2C accounts 
- Handling throttling 
- Proactive token refresh and token revocation based on policy or critical events for Microsoft Graph and other APIs that support [Continuous Access Evaluation (CAE)](~/identity-platform/app-resilience-continuous-access-evaluation.md)
- Auth broker support with device-based Conditional Access policies 
- Azure AD hardware-based certificate authentication (CBA) on mobile  
- System browsers on mobile devices 
And more. For an up-to-date list, refer to our [migration guide](~/identity-platform/msal-migration.md#how-to-migrate-to-msal). 

### How to migrate? 

To make the migration process easier, we published a [comprehensive guide](~/identity-platform/msal-migration.md#how-to-migrate-to-msal) that documents the migration paths across different platforms and programming languages. 

In addition to the Microsoft Authentication Library to Microsoft Authentication Library update, we recommend migrating from Azure AD Graph API to Microsoft Graph. This change enables you to take advantage of the latest additions and enhancements, such as CAE, across the Microsoft service offering through a single, unified endpoint. You can read more in our [Migrate your apps from Azure AD Graph to Microsoft Graph](/graph/migrate-azure-ad-graph-overview) guide. You can post any questions to [Microsoft Q&A](/answers/topics/azure-active-directory.html) or [Stack Overflow](https://stackoverflow.com/questions/tagged/msal).

---

## November 2022

### General Availability - Use Web Sign-in on Windows for password-less recovery with Temporary Access Pass



**Type:** Changed feature   
**Service category:** N/A          
**Product capability:** User Authentication     

The Temporary Access Pass can now be used to recover Azure AD-joined PCs when the EnableWebSignIn policy is enabled on the device. This is useful for when your users don't know, or have, a password. For more information, see: [Authentication/EnableWebSignIn](/windows/client-management/mdm/policy-csp-authentication#authentication-enablewebsignin).


---

### Public Preview - Workload Identity Federation for Managed Identities



**Type:** New feature   
**Service category:** Managed identities for Azure resources         
**Product capability:** Developer Experience       

Developers can now use managed identities for their software workloads running anywhere, and for accessing Azure resources, without needing secrets. Key scenarios include:

- Accessing Azure resources from Kubernetes pods running on-premises or in any cloud.
- GitHub workflows to deploy to Azure, no secrets necessary.
- Accessing Azure resources from other cloud platforms that support OIDC, such as Google Cloud.

For more information, see: 
- [Configure a user-assigned managed identity to trust an external identity provider (preview)](~/workload-id/workload-identity-federation-create-trust-user-assigned-managed-identity.md)
- [Workload identity federation](~/workload-id/workload-identity-federation.md)
- [Use an Azure AD workload identity (preview) on Azure Kubernetes Service (AKS)](/azure/aks/workload-identity-overview)


---

### General Availability - Authenticator on iOS is FIPS 140 compliant



**Type:** New feature   
**Service category:** Microsoft Authenticator App              
**Product capability:** User Authentication     

Authenticator version 6.6.8 and higher on iOS will be FIPS 140 compliant for all Azure AD authentications using push multi-factor authentications (MFA), Password-less Phone Sign-In (PSI), and time-based one-time pass-codes (TOTP). No changes in configuration are required in the Authenticator app or Azure portal to enable this capability. For more information, see: [FIPS 140 compliant for Azure AD authentication](~/identity/authentication/concept-authentication-authenticator-app.md#fips-140-compliant-for-azure-ad-authentication).


---

### General Availability - New Federated Apps available in Azure AD Application gallery - November 2022



**Type:** New feature   
**Service category:** Enterprise Apps                 
**Product capability:** 3rd Party Integration        

In November 2022, we've added the following 22 new applications in our App gallery with Federation support

[Adstream](~/identity/saas-apps/adstream-tutorial.md), [Databook](~/identity/saas-apps/databook-tutorial.md), [Ecospend IAM](https://ecospend.com/), [Digital Pigeon](~/identity/saas-apps/digital-pigeon-tutorial.md), [Drawboard Projects](~/identity/saas-apps/drawboard-projects-tutorial.md), [Vellum](https://www.vellum.ink/request-demo), [Veracity](https://aie-veracity.com/connect/azure), [Microsoft OneNote to Bloomberg Note Sync](https://www.bloomberg.com/professional/support/software-updates/), [DX NetOps Portal](~/identity/saas-apps/dx-netops-portal-tutorial.md), [itslearning Outlook integration](https://itslearning.com/global/), [Tranxfer](~/identity/saas-apps/tranxfer-tutorial.md), [Occupop](https://app.occupop.com/), [Nialli Workspace](https://ws.nialli.com/), [Tideways](https://app.tideways.io/login), [SOWELL](https://manager.sowellapp.com/#/?sso=true), [Prewise Learning](https://prewiselearning.com/), [CAPTOR for Intune](https://www.inkscreen.com/microsoft), [wayCloud Platform](https://app.way-cloud.de/login), [Nura Space Meeting Room](https://play.google.com/store/apps/details?id=com.meetingroom.prod), [Flexopus Exchange Integration](https://help.flexopus.com/de/microsoft-graph-integration), [Ren Systems](https://app.rensystems.com/login), [Nudge Security](https://www.nudgesecurity.io/login)

You can also find the documentation of all the applications from here https://aka.ms/AppsTutorial,

For listing your application in the Azure AD app gallery, read the details here https://aka.ms/AzureADAppRequest


---

### General Availability - New provisioning connectors in the Azure AD Application Gallery - November 2022



**Type:** New feature   
**Service category:** App Provisioning               
**Product capability:** 3rd Party Integration        

We've added the following new applications in our App gallery with Provisioning support. You can now automate creating, updating, and deleting of user accounts for these newly integrated apps:

- [Keepabl](~/identity/saas-apps/keepabl-provisioning-tutorial.md)
- [Uber](~/identity/saas-apps/uber-provisioning-tutorial.md)

For more information about how to better secure your organization by using automated user account provisioning, see: [Automate user provisioning to SaaS applications with Azure AD](~/identity/app-provisioning/user-provisioning.md).


---

### Public Preview - Dynamic Group pause functionality 



**Type:** New feature   
**Service category:** Group Management           
**Product capability:** Directory     

Admins can now pause, and resume, the processing of individual dynamic groups in the Entra Admin Center. For more information, see: [Create or update a dynamic group in Azure Active Directory](~/identity/users/groups-create-rule.md).


---

### Public Preview - Enabling extended customization capabilities for sign-in and sign-up pages in Company Branding capabilities.



**Type:** New feature   
**Service category:** Authentications (Logins)          
**Product capability:** User Authentication     

Update the Azure AD and Microsoft 365 sign-in experience with new company branding capabilities. You can apply your company’s brand guidance to authentication experiences with predefined templates. For more information, see: [Configure your company branding](./how-to-customize-branding.md).


---

### Public Preview - Enabling customization capabilities for the Self-Service Password Reset (SSPR) hyperlinks, footer hyperlinks and browser icons in Company Branding.



**Type:** New feature   
**Service category:** Directory Management             
**Product capability:** Directory       

Update the company branding functionality on the Azure AD/Microsoft 365 sign-in experience to allow customizing Self Service Password Reset (SSPR) hyperlinks, footer hyperlinks and browser icon. For more information, see: [Configure your company branding](./how-to-customize-branding.md).


---

### General Availability - Soft Delete for Administrative Units



**Type:** New feature   
**Service category:** Directory Management           
**Product capability:** Directory      

Administrative Units now support soft deletion. Admins can now list, view properties of, or restore deleted Administrative Units using the Microsoft Graph. This functionality restores all configuration for the Administrative Unit when restored from soft delete, including memberships, admin roles, processing rules, and processing rules state.

This functionality greatly enhances recoverability and resilience when using Administrative Units. Now, when an Administrative Unit is accidentally deleted, you can restore it quickly to the same state it was at time of deletion. This removes uncertainty around configuration and makes restoration quick and easy. For more information, see: [List deletedItems (directory objects)](/graph/api/directory-deleteditems-list).


---

### Public Preview - IPv6 coming to Azure AD



**Type:** Plan for change      
**Service category:** Identity Protection            
**Product capability:** Platform     

With the growing adoption and support of IPv6 across enterprise networks, service providers, and devices, many customers are wondering if their users can continue to access their services and applications from IPv6 clients and networks. Today, we’re excited to announce our plan to bring IPv6 support to Microsoft Azure Active Directory (Azure AD). This allows customers to reach the Azure AD services over both IPv4 and IPv6 network protocols (dual stack).
For most customers, IPv4 won't completely disappear from their digital landscape, so we aren't planning to require IPv6 or to deprioritize IPv4 in any Azure Active Directory features or services.
We'll begin introducing IPv6 support into Azure AD services in a phased approach, beginning March 31, 2023.
We have guidance that is specifically for Azure AD customers who use IPv6 addresses and also use Named Locations in their Conditional Access policies.

Customers who use named locations to identify specific network boundaries in their organization need to:
1. Conduct an audit of existing named locations to anticipate potential risk.
1. Work with your network partner to identify egress IPv6 addresses in use in your environment.
1. Review and update existing named locations to include the identified IPv6 ranges.

Customers who use Conditional Access location based policies to restrict and secure access to their apps from specific networks need to:
1. Conduct an audit of existing Conditional Access policies to identify use of named locations as a condition to anticipate potential risk.
1. Review and update existing Conditional Access location based policies to ensure they continue to meet your organization’s security requirements.

We continue to share additional guidance on IPv6 enablement in Azure AD at this link: https://aka.ms/azureadipv6.


---
