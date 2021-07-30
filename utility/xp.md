---
layout: default
title: XP
parent: Utility
nav_order: 1
---

# XP
Beemo's XP system allows for members to gain experience as they participate in the server via text & voice channels.

---

## About

Users are able to gain XP through both text and voice channels, with customisable curves and role rewards for levels. Servers can add roles to be rewarded at different level milestones and benefit from an intregrated XP leaderboard.

If enabled alongside XP, users will also gain Honey at the same rate, which is consumable in a Honey role shop. See https://docs.beemo.gg/utility/honey for more information on the Honey shop.

## Commands

| Command 	| Example 	| Usage 	|
|---	|---	|---	|
| xp (enable/disable) 	| `/xp enable` 	| Enables or disables the XP system. 	|
| xp rolereward (level) (role name/id) 	| `/xp rolereward 10 @Level 10` 	| Adds or removes the specified role as an XP role reward for the level specified. You do not need to specify the role if you are removing the role reward. 	|
| xp rolerewards 	| - 	| Lists the current XP role rewards for the server. 	|
| xp reset (user mention/role name/id) 	| `/xp reset @Ayu` `/xp reset all` 	| Resets the specified user's XP on the server. Replace user with all to reset the server's XP. Specify a role to reset all users with a role. 	|
| xp set (user mention/id) (new amount) 	| `/xp set @Ayu 100` 	| Sets the specified user's XP to the new XP amount. 	|
| xp refreshroles 	| - 	| Refreshes all of the user's XP role rewards. Use this command after you add or remove xp role rewards from the system. 	|
| xp textcooldown (seconds) 	| `/xp textcooldown 10` 	| Sets how often 1 XP / honey can be earned through text channels, in seconds. 	|
| xp voicecooldown (seconds) 	| `/xp voicecooldown 10` 	| Sets how often 1 XP / honey can be earned through voice channels, in seconds. 	|
| xp blacklistrole (role name/id) 	| `/xp blacklist @Banned` 	| Adds or removes the specified role as an XP & Honey-blacklisted role. 	|
| xp blacklistedroles 	| - 	| List the current XP and honey-blacklisted roles. Users with these roles cannot gain XP or honey. 	|
| xp blacklistchannel (channel name/id) 	| `/xp blacklistchannel #general` 	| Adds or removes the specified text or voice channel as an XP and honey-blacklisted channel. 	|
| xp blacklistedchannels 	| - 	| Lists the current XP and honey-blacklisted text and voice channels. 	|
| xp adminrole (role name/id) 	| `/xp adminrole @Admin` 	| Adds or removes the specified role as an XP and honey admin role. 	|
| xp adminroles 	| - 	| Lists the current XP and honey admin roles. Users with these roles can use XP and honey admin commands. 	|
| xp keepxproles (yes/no) 	| `/xp keeproles yes` 	| Sets if users should keep their previous XP roles when they reach the next role reward. 	|
| xp resetonleave (yes/no) 	| `/xp resetonleave no` 	| Sets if user XP / honey should be reset upon leaving the server. 	|
| xp resetonban (yes/no) 	| `/xp resetonban yes` 	| Sets if user XP / honey should be reset upon being banned from the server. 	|
| xp notifications (yes/no) 	| `/xp notifications no` 	| Sets if a level up notification should be sent when a user levels up. 	|
| xp notificationschannel (channel name/id) 	| `/xp notificationschannel #notify` 	| Sets the channel to send level up notifications to. Put none for the channel name to remove a set channel. If no channel is specified, the notice will be sent to the user's DMs. 	|
| xp commandchannel (channel name/id) 	| `/xp commandchannel #bot-commands` 	| Adds or removes the specified text channel as an allowed channel for XP and honey commands. 	|
| xp commandchannels 	| - 	| Lists the current XP and honey command channels. 	|
| xp rankcommandcooldown (seconds) 	| `/xp rankcommandcooldown 5` 	| Sets the cooldown in seconds for the /rank command. 	|
| xp difficulty (decimal value) 	| `/xp difficulty 2.0` 	| IMPORTANT: This setting will change the XP curve! Sets the difficulty of the XP system. This modifies the multiplier so that the amount of XP needed to reach the next level is either larger or smaller. The current difficulty is set to 1.0. 	|
|  	|  	| IMPORTANT: This setting will change the XP curve! Changes the XP level-to-xp ratio to the specified decimal value. 	|
