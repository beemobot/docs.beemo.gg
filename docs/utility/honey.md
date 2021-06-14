---
layout: default
title: Honey
parent: Utility
nav_order: 1
---

# Honey

Honey is a consumable credits system that allows for users to purchase roles.  
{: .fs-6 .fw-300 }

---

## About Honey
Honey allows for servers to reward members who participate in the server with credits they can later trade in for role-rewards. There are many applications that could be be done with this system - for example, servers could allow for active users to claim colour roles. 

## Commands

| Command         | Description                                                                                                                                                                | Usage                                                                     |
|-----------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------|
| honey           | Enables or disables the honey system.                                                                                                                                      | /honey (enable/disable)                                                   |
| honey shop role | Sets or removes the specified role as a honey shop role for purchase via the /honey shop command. Important: Please note that the role must be either an ID or a mention.  | /honey shop role (role mention/id) (cost in honey) (optional description) |
| honey reset     | Resets the specified user's honey on the server. Replace user with all to reset the server's Honey. Specify a role to reset all users with a role.                         | /honey reset (user mention/role name/id)                                  |
| honey set       | Sets the specified user's honey to the new honey amount.                                                                                                                   | /honey set (user mention/id) (new amount)                                 |