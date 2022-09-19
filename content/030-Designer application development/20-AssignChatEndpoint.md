---
title: "Assign Chat Endpoint then Test"
chapter: true
weight: 20
---

## Assign Chat Endpoint then Test
Once a Designer application has been created, assign it a chat endpoint. 

- Within Designer, under Applications, in the Application table, click on the row of one of your applications.
- Click on [Manage Chat Endpoints]. 
 
>tip - click on the row of the app, not on the name of the app. 

![ChatEndp](/images/eodDsgnrManageChatEP.png)

- In the [Assign an EServices Endpoint] window, enter the desired chat endpoint name.

     - Preferably, name it after your unit name.
     - The naming convention is U##_ChatEndpoint_#. 
     - For instance U39_ChatEndpoint_1, where ## is your unit id.
     - Click OK  

![AssighEndp](/images/eodAssignEsEndpoint.png)

- You can now test a chat.

     - Have your Azure EOD Personal agent logged into Agent Desktop on the Portal and make them ready.
     - Go to this page - Widgets Demo. 
     - Paste your chat endpoint. Make sure to enter the name of the endpoint and not the name of the application.
     - Select the stream in your Designer application (typically [dev])
     - Hit [Submit].

     - This opens a new window with the widget on the right side of the page.
     - Open the widget to start a chat.
     - Fill up the chat registration form and hit [Start Chat].       



![ChatTesting](/images/file_1623269540913_azureChatTesting.png)
     
 > Note that you can also use the default "Treasure_Bank_Service" endpoint.

-  Accept the chat with your Azure EOD Personal agent logged into Agent Desktop. 
![Endpoint](/images/file_1623292912618_azureEndpointChat7.png)
![TBEndpoint](/images/file_1623272703571_azureEndpointChat.png)

