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

| Command                                                                 | Example                                                                    | Usage                                                                                                            |
|-------------------------------------------------------------------------|----------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------|
| honey all [enable]                                                      | `/honey all enable:false`                                                  | Enables or disables the honey system.                                                                            |
| honey shop put [role mention/id] [cost in honey] (optional description) | `/honey shop put role:@Sugar cost:23 description:Purchase this honeycomb!` | Puts the specified role as a honey shop role for purchase via the `/honey shop buy` command, replaces if exists. |
| honey shop remove [role mention/id]                                     | `/honey shop remove role:@Sugar`                                           | Removes the specified role from the Honey shop.                                                                  |
| honey reset user [user mention]                                         | `/honey reset user:@Beemo#4570`                                           | Resets the specified user's honey on the server.                                                                 |
| honey reset role [role mention]                                         | `/honey reset role:@Sugar`                                                 | Resets all the user with the role's honey on the server.                                                         |
| honey reset all                                                         | `/honey reset all`                                                         | Resets the entire server's honey.                                                                                |
| honey set [user mention/id] [new amount]                                | `/honey set user:@Beemo#4570 amount:10`                                    | Sets the specified user's honey to the new honey amount.                                                         |
