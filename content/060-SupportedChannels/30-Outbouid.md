---
title: "Outbound/CX Contact"
chapter: true
weight: 30
---

## Outbound/CX Contact

CX Contact is available on the Azure EOD Personal platform.

Each personal unit can fully administer their own pesonal set of CX Contact objects (e.g. Calling Lists, Campaign Groups, etc.) or refer to a predefined set of CX Contact objects already created and configured.

The system provides this segmentation by enabling the latest "partitioning" capabilities within the CX Contact product.

We recommend each user create their own calling lists, campaign templates and campaign groups to avoid any conflicts with other users sharing the "global" objects created primarily for reference.

> Note: all "required" Compliance Rules or Suppression Lists are always considered Shared and will be applied to all partitions so please do not set the Required attribute to true for any Compliance Tools in our demonstration environment.

To access CX Contact click on the CX Contact tile on the portal main page.

![One](/images/file_1626298517134_portal.png)

This action will opne the main CX Contact login page.

![Two](/images/file_1626298746091_cxcmain.png)

Enter your admin user name and password to login to CX Contact.

Once logged in the CX Contact UI will be shown.

![Three](/images/file_1626712735921_cxcui.png)

The above image shows the "global" campaign templates and groups created for you to refer to when creating your own private CX Contact objects. The global set is shared by all users and therefore not the ideal source for individual demonstrations. However, the global objects will function and can be used for live demonstrations if required.

The global objects will provide examples of all the various dialing modes available in CX Contact. To use one of the global campaign groups you need to have your **u[Unit Id]out@pec.com** agent logged into WWE, make this agent Ready and perform the appropriate action for each campaign group within your Agent Desktop. The global calling lists assigned to the global campaign groups have a small set of target voice numbers created on our VoipMS service provider. The numbers when dialed will answer the call and play a brief message to the caller. We use these same numbers for voice and sms endpoints. Emails are delivered to another internet service we have chosen that provides free email endpoints. To view emails sent to the global-Email-List endpoints go to [external link](https://yopmail.com/en/) and login with the specific email address listed in the global email calling list. 

We recommend each user create their own personal and private set of CX Contact objects to use in live demonstrations. Using the global objects can result in other users performing actions on the global objects that conflict with your active demonstrations.

Each POC and EOD has numerous pre-created objects available for use when creating private CX Contact configuration objects. For example, the Dxxx_Outbound_RP and Uxxx_Outbound_RP should be used when creating custom Designer applications and so forth. Please review the configuration for your unit when administering CX Contact.
