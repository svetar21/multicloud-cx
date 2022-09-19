---
title: "Managing Case Data"
chapter: true
weight: 10
---

## Managing Case Data

>Note: if you override Case Data, the global definition of Case Data (defined under "Contact Center Settings") will be entirely replaced with what you define at the agent group level. This means that if you want to preserve the global definition (and add your own Case Data), you will have to copy the global Case Data entries into your setting at the agent group level.

Click on the Agent Setup tile within the Azure EOD Portal, and login with your Azure EOD Personal user of role Administrator (refer to the 'Login Information' section on how to find users). 
note: Tenant is left blank.



Navigate to [Agent Groups] / U##-AgentGroup:



..then navigate to [Agent Group] / [Case Data]



1) On the right panel, click on [Folder: /GDemo] and select the [U###] folder. This folder is owned by the unit and the unit admin has create/update/delete permissions on this folder to handle objects of the selected type (Case Data in this example)

2) To turn custom Case Data on, click on the [Select Business Attribute] drop-down and on [Add…]

3) Enter the Business Attribute name of your choice. Note that the system requires this name to be unique in the entire tenant. A good idea is to prefix the name with the unit identifier (U### for example) to minimize the risk of name collision.

4) Click on [+ Add] to add a key/value pair of case data to be displayed to the agent. 

The Name needs to be an interaction data key name to be presented to the agent. 
You can set a [Display name] which is the actual name that will be shown to the agent
The entry can be made mandatory (in which case the agent cannot terminate the interaction if this entry has no value)
The entry type can be selected – if set to Read Only, the agent cannot change the value
A default value can be set in case no value is set in the interaction data
5) Repeat the previous step for all entries required in the Case Data.



6) Click on [Save] – otherwise the entire set of changes are not applied and saved.*
