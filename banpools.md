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

## How do Banpools work?

When servers join a banpool, they will recieve all bans from other servers in that banpool. All users by default are apart of the  `antispam` banpool, which serves to protect all participants against userbot raids.

## Commands

| Command 	| Example 	| Usage 	|
|---	|---	|---	|
| banpool list 	| - 	| Lists all of the banpools that this server is in. This command will also show all of the available public banpools to join if there are any this server is not in. 	|
| banpool info [banpool id] 	| `/banpool info 123456` 	| Gets info for the banpool ID specified. 	|
| banpool invite [banpool id] [server id] 	| `/banpool invite 12464625536373 697474023914733575` 	| Invites the specified server to the specified banpool, allowing them to join it via command. Banpools can only have one pending invite at a time. 	|
| banpool uninvite [banpool id] 	| `/banpool uninvite 12464625536373` 	| Revokes the invite for the banpool specified. 	|
| banpool join [banpool id] 	| `/banpool join 12464625536373` 	| Adds this server to the specified banpool if it is allowed to. 	|
| banpool leave [banpool id] 	| `/banpool leave 12464625536373` 	| Removes this server from the specified banpool if it is in it. 	|
| banpool actionlog [channel id or mention] 	| `/banpool actionlog #log` 	| Sets the log channel for banpools. Put none for the channel parameter to unset. 	|
| banpool modrole [banpool id] [role id or name] 	| `/banpool modrole 12464625536373 Mod` 	| Enables a role to contribute to the specified banpool via /poolban and /unpoolban 	|
| banpool modroles [banpool id] 	| `/banpool modroles 12464625536373` 	| Lists all mod roles for the banpool specified. Users with these roles can contribute to the banpools they are mod for. 	|
| banpool managerrole [role id or name] 	| `/banpool managerole Manager` 	| Enables a role to manage banpools for this server. This allows people to use /banpool configuration commands. 	|
| banpool managerroles 	| - 	| Lists all banpool manager roles for this server. 	|
| poolban [banpool id] [user id(s)] [reason] 	| `/banpool 12464625536373 192048286331437056 347727875266576395 raiding` 	| Bans a user or list of users from all servers in the banpool specified 	|
| unpoolban [banpool id] [user id(s)] [reason] 	| `/unbanpool 12464625536373 192048286331437056 347727875266576395 false positives` 	| Unbans a user or list of users from all servers in the banpool specifi 	|
