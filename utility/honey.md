---
layout: default
title: Honey
parent: Utility
nav_order: 1
---

# Honey

Honey is a consumable credits system that allows users to purchase roles.
{: .fs-6 .fw-300 }

---

## About Honey
Honey allows for servers to reward activity with credits they can later trade in for role rewards. These credits, namely "Honey," are earned at the same rate as XP; This means that users can spend their Honey without affecting their XP level. Many applications could be done with this system - for example, servers could allow for active users to claim exclusive color roles. 

## Commands

| Command 	| Example 	| Usage 	|
|---	|---	|---	|
| honey [enable/disable] 	| `/honey disable` 	| Enables or disables the honey system. 	|
| honey shop role [role mention/id] [cost in honey] (optional description) 	| `/honey shop role 12345678 23 Purchase this honeycomb!` 	| Sets or removes the specified role as a honey shop role for purchase via the /honey shop command. Important: Please note that the role must be either an ID or a mention. 	|
| honey reset [user mention/role name/id] 	| `/honey reset @Ayu`  `/honey reset all`  `/honey reset @Admin` 	| Resets the specified user's honey on the server. Replace user with all to reset the server's Honey. Specify a role to reset all users with a role. 	|
| honey set [user mention/id] [new amount] 	| `/honey set @Ayu 69` 	| Sets the specified user's honey to the new honey amount. 	|
