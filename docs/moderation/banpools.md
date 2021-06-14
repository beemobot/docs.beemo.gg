---
layout: default
title: Banpools
parent: Moderation
nav_order: 2
---

# Banpools

Banpools allow for Beemo Max servers to group together and ban users across multiple servers with one command.  
{: .fs-6 .fw-300 }

---

## How do they work?

When servers join a banpool, they will recieve all bans from other servers in that banpool. All users by default are apart of the  `antispam` banpool.

## Commands

|        Command       | Description                                                                                                                                                        | Usage                                           |
|:--------------------:|--------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------|
| banpool list         | Lists all of the banpools that this server is in. This command will also show all of the available public banpools to join if there are any this server is not in. | /banpool list                                   |
| banpool info         | Gets info for the banpool ID specified.                                                                                                                            | /banpool info [banpool id]                      |
| banpool invite       | Invites the specified server to the specified banpool, allowing them to join it via command. Banpools can only have one pending invite at a time.                  | /banpool invite [banpool id] [server id]        |
| banpool uninvite     | Revokes the invite for the banpool specified.                                                                                                                      | /banpool uninvite [banpool id]                  |
| banpool join         | Adds this server to the specified banpool if it is allowed to.                                                                                                     | /banpool join [banpool id]                      |
| banpool leave        | Removes this server from the specified banpool if it is in it.                                                                                                     | /banpool leave [banpool id]                     |
| banpool actioinlog   | Sets the log channel for banpools. Put none for the channel parameter to unset.                                                                                    | /banpool actionlog [channel id or mention]      |
| banpool modrole      | Enables a role to contribute to the specified banpool via /poolban and /unpoolban                                                                                  | /banpool modrole [banpool id] [role id or name] |
| banpool modroles     | Lists all mod roles for the banpool specified. Users with these roles can contribute to the banpools they are mod for.                                             | /banpool modroles [banpool id]                  |
| banpool managerrole  | Enables a role to manage banpools for this server. This allows people to use /banpool configuration commands.                                                      | /banpool managerrole [role id or name]          |
| banpool managerroles | Lists all banpool manager roles for this server.                                                                                                                   | /banpool managerroles                           |
| banpool managerroles | Lists all banpool manager roles for this server.                                                                                                                   | /banpool managerroles                           |
| poolban              | Bans a user or list of users from all servers in the banpool specified                                                                                             | /poolban [banpool id] [user id(s)] [reason]     |
| unpoolban            | Unbans a user or list of users from all servers in the banpool specifi                                                                                             | /unpoolban [banpool id] [user id(s)] [reason]   |
