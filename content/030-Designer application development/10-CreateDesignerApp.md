---
title: "Create a Designer App for Routing"
chapter: true
weight: 10
---

## Create a Designer App for Routing

- On the Azure EOD Portal login to Designer with your user of role Administrator (refer to 'Login Information' section in Multicloud-cx-102 workshop on how to find users). 
>note: Tenant is left blank.
![Designer](/images/file_1622754045059_azureDesignerTile.png)

- On the Applications page click on [Add Application].
![Apps](/images/eodDsgnrAddApp.png)

- Give the application a name, preferably including your unit id. For instance U##-App1, where ## is your unit id. 
- Keep the type of application as [Default].
- Click on [Create And Open].
![CreateApp](/images/eodDsgnrCreateApp.png)

- In Application Settings click on [Digital].
- Check the [Enable Omni-Channel support for Default applications] box.
- Click on [Please Review All Settings and Press Here to Continue]. 

![AppSettings](/images/eodDsgnrAppDigit(1).png)

- In Application Settings click on [Persona].
- Check the [Enable Persona] checkbox.
- Click on [Please Review All Settings and Press Here to Continue] / [Save]. 

![Personal](/images/eodDsgnrAppPersona.png)

>You need as a bare minimum to add one block named [Route Call] (under [Routing] in the palette)
- Click on the [Route Call] block and drag/drop it inside the [Assisted Service] section.
![RouteCall](/images/eodDsgnrRouteCall.png)

### Assisted Service

- To route an interaction to your virtual agent group, click on the block you just placed into the Application Flow to bring up the block details.

>The default routing type is [Skill based routing with relaxing criteria].
- Click [Specify Skills in this block]. 
- Click on the [Select Some Options] box.

![Environments](/images/file_1604107212047_gecEnvironments.jpg)

- In the drop-down, select at least your unit skill (U##-Skill for instance) 
>Optionally you can add a second specialized skill like BackOffice to target your <BO> agent

![Environments](/images/file_1604107212047_gecEnvironments.jpg
  
  
- [Save Flow] then [Publish] your Application when done.  
  

![Environments](/images/file_1604107212047_gecEnvironments.jpg)
  
### Self Service (Register a Bot)
  
- To register a bot, you need to go to 'Grammar & Bots' > 'Bots Registry' section and enter the bot name and choose the Type, and then click Submit.
  
![Environments](/images/file_1604107212047_gecEnvironments.jpg
  
- Then you will need to enter the settings for the Type you selected. In this example, for Dialog Engine. Then click Save.
  
![Environments](/images/file_1604107212047_gecEnvironments.jpg

  
