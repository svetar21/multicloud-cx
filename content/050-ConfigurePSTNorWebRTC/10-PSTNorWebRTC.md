---
title: "Configuration steps"
chapter: true
weight: 10
---

## Adding/Removing PSTN number

### Adding a PSTN number to an agent

- Click on the Agent Setup tile within the Genesys Engage Cloud Portal, and login with your EOD Personal user of role Administrator. 
- Navigate to [Users] and select one of your agents - Agent Setup direct link
- In the General Info section, locate the [Phone Number(s)] section
- The first entry of the table is the WebRTC phone. Do not edit/delete this entry
- Click on the next line's number and enter your PSTN in E164 format (including +country_code)
- Check the 'default' checkbox and make sure the 'use' checkbox is checked
- Hit [Save]
 
![One](/images/file_1622775547962_azureAgentSetupTile.png)


This actually creates a second Place for the agent (u5agt@pec.com2 in the above example).

- Disable WebRTC for this agent

       - Navigate to [Users] and select one of your agents - Agent Setup direct link
       - In the Voice section, locate the [Can Use WebRTC] checkbox - you can filter options by typing 'webrtc' in the filter
       - Uncheck the 'Can Use WebRTC' checkbox
       - Hit [Save]
       - 
![Two](/images/file_1622775547962_azureAgentSetupTile.png)


Optionally you can configure this agent to have the ability to enter his/her desired place to use at login, the default that will be presented in WWE will be the one for which the 'default' checkbox is checked.

- To configure  the 'prompt place' option:

     -In Agent Setup, navigate to [Users] and select one of your agents - Agent Setup direct link
Expand the [Desktop Options] 
Click on [Global Login]
Check the [Prompt Place] box
Hit [Save]




When login in your agent in WWE, the 3rd login screen will prompt for the place

The place will be prefilled with the default place
If you want to change the place, simply type the place name you want to use



Notes on the use of a PSTN phone

Since there is no 3rd party call control on an external phone, you won't be able to answer the call from WWE. You will need to answer the call from the PSTN phone

To avoid looping issues, do not use the same phone for your agent and your customer

You cannot configure the same PSTN number for multiple agents

### Removing a PSTN number from an agent

Click on the Agent Setup tile within the Genesys Engage Cloud Portal, and login with your EOD Personal user of role Administrator. 
Navigate to [Users] and select one of your agents - Agent Setup direct link
In the General Info section, locate the [Phone Number(s)] section
Remove the PSTN number and description (if any)
Uncheck the 'use' checkbox for this line
Check the 'default' checkbox on the first line (WebRTC number)


Click on [Save] - you will be prompted to delete the Place
Check the [Delete user's Places] box, then click on [Update]



Enable WebRTC for this agent
Navigate to [Users] and select one of your agents - Agent Setup direct link
In the Voice section, locate the [Can Use WebRTC] checkbox - you can filter options by typing 'webrtc' in the filter
Check the 'Can Use WebRTC' checkbox
Hit [Save]


