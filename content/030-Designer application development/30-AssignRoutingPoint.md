---
title: "Assign Routing Point for Voice"
chapter: true
weight: 30
---

## Assign Routing Point for Voice

Once a Designer application has been created, you can assign it a Route Point. 

- Click on the line of one of your applications.
- Click on [Manage]:
![Apps](/images/eodDsgnrAddApp.png)
- Click on the internal route point you want to assign to the app:
![Apps](/images/eodDsgnrAddApp.png)
> Notice that the Unit ID for this example is 12. Your numbers will change accordigly for your specific Unit ID. 

- Your internal route point has been assigned:
![Apps](/images/eodDsgnrAddApp.png)

You can use 2 shared DIDs (local numbers in North America and in UK) that will automatically map to Internal DIDs that you can assign to your application.

EOD Personal Users
 	External DID
North America	External DID
UK	External DID
Australia	Internal DID	Example for
Unit ID 123
Group 0	+1 (650) 337-3810	+44 (204) 525-4840	+61 272-024-270	778<####>00	778012300
Group 1	+1 (650) 337-3811	+44 (204) 525-4841	+61 272-024-271	778<####>01	778012301
Group 2	+1 (650) 337-3812	+44 (204) 525-4842	+61 272-024-272	778<####>02	778012302
Group 3	+1 (650) 337-3813	+44 (204) 525-4843	+61 272-024-273	778<####>03	778012303

You can then call the external route points of the group you assigned to your application. In the above example, call +1 (650) 337-3811 because you assigned the application to group 1. This call should be routed to one of your logged in and ready agents.
