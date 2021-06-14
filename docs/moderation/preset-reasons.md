---
layout: default
title: Preset Reasons
parent: Moderation
nav_order: 3
---

# Preset Reasons

Save moderators time by storing preset reasons for them to use on bad actors.   
{: .fs-6 .fw-300 }

---

## About
Preset reasons allow for moderators to save time when issuing punishments in a server by using preset flags for rules that are repeatedly violated. 

## Configuration
Configuring preset reasons for your guild is simple. Please keep in mind that you must have the Administrator permission or be a Moderation Manager to configure preset reasons. 

### Managing Presets

To set a new preset reason, do `/mod presetreason [variablename] (reason)`, to remove a preset reason do `/mod presetreason [variablename]` without a reason.

Once added, all moderators in your server will now be able to use the preset reason you have configured by simply typing `-reasonhere` as their reason.

### Viewing/Listing Presets
To list all of the available preset reasons, use the `/presetreasons` command, to see a specific reason, do `/presetreasons -reasonhere`.

### Using Presets

To use a preset reason in a moderation command, simply put `-reasonhere` as your reason at the end of the command, and Beemo will automatically action the user with that reason. 


