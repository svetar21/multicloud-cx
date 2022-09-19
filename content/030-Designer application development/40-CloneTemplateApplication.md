---
title: "Clone a Template Application"
chapter: true
weight: 40
---

## Clone a Template Application

As an alternative to creating a Designer Application manually, assigning a Chat Endpoint, and Assigning a Route Point for Voice, it is possible to clone a template application with many channels already integrated.

On the Azure EOD Portal login to Designer with your user of role Administrator (refer to 'Login Information' section on how to find users). 
note: Tenant is left blank.

![Designer](/images/file_1622754045059_azureDesignerTile.png)

The template application for the unit shows in the Applications list. Its name includes the unit name, and the template build number. For example for unit U203, in the following image B9 is the template build number. Over time, we will publish new builds of the template application so keep an eye on the template build number and description to stay up to date.

Click on the table row that contains the template (not on the template name which is a link, but on the row). The description will populate on the right. The description for the application is useful to know what is included with the build.

![One](/images/eodTemplateApplications.png)

> NOTE! : the Template is a standard application that can be edited and associated to a route point or chat endpoint but we strongly recommend that you do not edit or use the application directly. Instead, you must clone the application before modifying or using it.
 

### How to clone your own application from the template
Click on [Clone application]...

![Two](/images/eodTemplateCloneApp.png)

...and give the clone a meaningful name, like "U203-Application_PEC_Demo”, then click [Create and Open]

![Three](/images/eodTemplateCloneName.png)

When the application is open.

![Four](/images/eodTemplateSavePubBuild.png)
- Click [Save]
- Click [Publish]
- Click [Build] and give the build a name.

![Five](/images/eodTemplateCreateBuild.png)

Hit the [Build] button in the bottom right.

![Six](/images/eodTemplateBuildBtn.png)

Go back to the list of Applications by hitting the top-menu “Applications”

Select the newly cloned application by clicking on the highlighted area below:

![Seven](/images/eodTemplateSelectClone.png)

Select the build you created from the drop-down next to [DEV]:

![Eight](/images/eodTemplateDevBuild.png)

Assign one of your route point:

- Click on [Manage] next to the build and in the popup, select an available route point and check the box:

![Nine](/images/eodTemplateManage.png)

![Ten](/images/eodTemplateRoutePoint.png)


- Click [OK]

Assign a chat endpoint to the application:

- Click on [Manage Chat Endpoints]

![Eleven](/images/eodTemplateManageEndpoint.png)


- In the popup, enter the endpoint name, preferably with your unit in the name, like “U203-PEC_Demo”: 

![Twelve](/images/eodTemplateAssignEndpoint.png)


- click [OK]

### How to use the template application
The description will be for chat, but the behavior will be similar for voice.

You can now test your template appllication:

- Have your Azure EOD Personal agent logged into Agent Desktop on the Portal and make them ready.

- Go to this page - Widgets Demo 

- Paste your chat endpoint. Make sure to enter the name of the endpoint and not the name of the application.

- Select the stream in your Designer application (typically [dev])

- Hit [Submit]

![Thirteen](/images/file_1623269540913_azureChatTesting.png)


- This opens a new window with the widget on the right side of the page

- Open the widget to start a chat.

- Fill up the chat registration form and hit [Start Chat]. 
 Accept the chat with your Azure EOD Personal agent logged into Agent Desktop. 

![Fourteen](/images/eodTemplateChatExample.png)

You can ask what your options are:

![Fiftgeen](/images/eodTemplateChatOptions.png)

And so on…

Widget on customer site:

Note that you also have the option to load the widget on a customer site by using the TamperMonkey injection script as described in the [TamperMonkey - Usage & Configuration] section below. In either case, you will have to configure the same chat endpoint you assigned the application to.

Routing and Callback:

When getting to the routing to an agent, the application checks if an agent of your unit is available before routing.
If none is available, a callback option is offered (only when application runs a phone call at this time).
 

### Options that control the application behavior
A data table is used by the template application, where you can change the behavior.

In Designer, go to “Business Controls”/”Data Tables” to access this table, which name includes your unit ID:

![Sixteen](/images/eodTemplateDataTables.png)


To change an option, click on the table name then on the option you want to change. In the below example, the callback timezone wil be changed:

![Seventeen](/images/eodTemplateChangeOption.png)

![Eighteen](/images/eodTemplateTimezone.png)




Click [OK]
Click [Save Table]
Click on [Publish Table]
Click on [Confirm Publish]

The “Authentication” option lets you choose between the following 3 values:

       - None: the caller ID is not requested.
       - Simple: the caller ID is requested. You must enter your mobile number, then a 4 digits PIN (any value will work).
       - Two factor: the caller ID is requested. You must enter your mobile number.
                     Your mobile will receive an SMS with a security code.
                     You will be asked to enter the security code. 
                     Should your mobile NOT receive this SMS, you can enter ‘123456’ as confirmation code.

