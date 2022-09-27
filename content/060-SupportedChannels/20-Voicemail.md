---
title: "Voicemail"
chapter: true
weight: 20
---

## Voicemail

### Group Voicemal
Group mailboxes are already configured for all Azure units.

The Designer template application already has your group mailbox number assigned to mbx variable and Route to Voicemail block is added to Assisted Services.  In case no agents are available to answer the call it will be routed to Voicemail asking to leave a message in the mailbox specified in mbx variable. If you clone Template Application (see section Clone a Template Application) you will have routing to group Voicemail already setup.

To access Voicemail login into Agent Desktop and dial 5555, follow the prompts.

![One](/images/file_1626804804178_VM1.png)

### Personal Voicemail
To configure Personal Voicemail in Agent Setup assign mailbox number to an agent. By default mailbox password is the same as mailbox number, however, you can always change it following the prompts while accessing Voicemail.

In Designer Application change the value of mbx variable to the value of personal mailbox of the agent.

![Two](/images/file_1623781304758_Capture12.png)

To access Voicemail login into Agent Desktop and dial 5555, follow the prompts.
