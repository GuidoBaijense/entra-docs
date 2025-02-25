---
title: Microsoft Entra application proxy and Qlik Sense
description:  Integrate Microsoft Entra application proxy with Qlik Sense.
services: active-directory
author: kenwith
manager: amycolannino
ms.service: active-directory
ms.subservice: app-proxy
ms.topic: how-to
ms.date: 09/14/2023
ms.author: kenwith
ms.reviewer: ashishj
---
# Microsoft Entra application proxy and Qlik Sense 
Microsoft Entra application proxy and Qlik Sense have partnered together to ensure you're easily able to use Application Proxy to provide remote access for your Qlik Sense deployment.  

## Prerequisites 
The remainder of this scenario assumes you completed the following:
 
- Configured [Qlik Sense](https://community.qlik.com/docs/DOC-19822). 
- [Installed an Application Proxy connector](~/identity/app-proxy/application-proxy-add-on-premises-application.md#install-and-register-a-connector) 
 
## Publish your applications in Azure 
To publish QlikSense, you'll need to publish two applications in Azure.  

### Application #1: 

Follow these steps to publish your app. For a more detailed walkthrough of steps 1-8, see [Publish applications using Microsoft Entra application proxy](~/identity/app-proxy/application-proxy-add-on-premises-application.md). 


1. Sign in to the [Microsoft Entra admin center](https://entra.microsoft.com) as at least a [Application Administrator](~/identity/role-based-access-control/permissions-reference.md#application-administrator).
1. Browse to **Identity** > **Applications** > **Enterprise applications**.
3. Select **New application** at the top of the page. 
4. Select **On-premises application**. 
5. Fill out the required fields with information about your new app. Use the following guidance for the settings: 
   - **Internal URL**: This application should have an internal URL that is the QlikSense URL itself. For example, **https&#58;//demo.qlikemm.com:4244** 
   - **Pre-authentication method**: Microsoft Entra ID (Recommended but not required) 
1. Select **Add** at the bottom of the page. Your application is added, and the quick start menu opens. 
2. In the quick start menu, select **Assign a user for testing**, and add at least one user to the application. Make sure this test account has access to the on-premises application. 
3. Select **Assign** to save the test user assignment. 
4. (Optional) On the app management page, select Single sign-on. Choose **Kerberos Constrained Delegation** from the drop-down menu, and fill out the required fields based on your Qlik configuration. Select **Save**. 

### Application #2: 
Follow the same steps as for Application #1, with the following exceptions: 

**Step #5**: The Internal URL should now be the QlikSense URL with the authentication port used by the application. The default is **4244** for HTTPS, and **4248** for HTTP for QlikSense releases prior to April 2018. The default for QlikSense releases after April 2018 is **443** for HTTPS and **80** for HTTP.  Ex: **https&#58;//demo.qlik.com:4244**</br></br>
**Step #10:** Don’t set up SSO, and leave the **Single sign-on disabled**
 
 
## Testing 
Your application is now ready to test. Access the external URL you used to publish QlikSense in Application #1, and sign in as a user assigned to both applications.  

## Additional references
For more information about publishing Qlik Sense with Application Proxy, see following the Qlik Community Articles: 
- [Microsoft Entra ID with integrated Windows authentication using a Kerberos Constrained Delegation with Qlik Sense](https://community.qlik.com/docs/DOC-20183)
- [Qlik Sense integration with Microsoft Entra application proxy](https://community.qlik.com/t5/Technology-Partners-Ecosystem/Azure-AD-Application-Proxy/ta-p/1528396)

## Next steps

- [Publish applications with Application Proxy](~/identity/app-proxy/application-proxy-add-on-premises-application.md)
- [Working with Application Proxy connectors](~/identity/app-proxy/application-proxy-connector-groups.md)
