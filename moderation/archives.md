---
layout: default
title: Archives
parent: Moderation
nav_order: 1
---

#  Archives

Archives allow for moderators to quickly browse a users message history, including edits and deleted messages.
{: .fs-6 .fw-300 }

---

## Making Archives 
There are currently a few ways that archives are generated with Beemo:

### Manually Generated
To manually generate an archive for a user, you must be a moderator; Running `/archive [user]` will grant you access to an archive that contains the past 3 days of said user's message history. Manually generated archives expire 12 hours after the command execution.

Notably, archives cannot be manually generated for moderators or administrators. This is to prevent any messages from being exposed from any mod or admin private channels.

### Automatically Generated
Whenever a moderation command is ran targetting a user, for example a ban, all of the users messages (including edits and deletions) will be archived and attached to the case. These archives are meant to serve as a snapshot of the past 3 days of message history of a user receiving an infraction, and will not expire for the purpose of moderation log persistence.

When you check info on a case via `/case (case id)` or `/modlogs (user id)`, the case-specific archive links will be displayed.

Note: When a user types `/mylogs`, they will not see the archives for their own cases.
