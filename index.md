---
layout: default
title: Beemo Docs
nav_order: 1
description: "Beemo is a free antispam Discord Bot that can stop userbot raids against your server."
permalink: /
---

# What is Beemo?
{: .fs-9 }

Beemo is a free antispam Discord Bot that can stop userbot raids against your server.

{: .fs-6 .fw-300 }

## Important Documentation Notes

**If you can't see the commands of XP, Honey or Mod**, then you most likely have the feature disabled. Beemo removes the commands from your server when it finds that the feature is not enabled on your server. To enable the feature, you can use the `/toggle` command.

The documentation for Beemo Max is limited, but there are some pages available. Since Beemo is designed to be configured in-Discord, all of the commands are generally well documented via their respective help menus. If you would like more information on Beemo Max (beyond the docs), [join the Discord](https://beemo.gg/Discord)!

## Adding Beemo & Setting Up 

Adding Beemo to your server is super simple!

1. [Invite Beemo to your server](https://beemo.gg/invite)! Beemo will not function if it is denied the `Ban Members` permission, but do note that all of the permissions being requested are there for logging and antispam improvements.

2. Move Beemo's highest role above regular server members so that it can ban regular members.

3. (Optional) Set up an action log for antispam with `/antispam log set #channel`

And you should be done! Beemo is now automatically checking and banning any userbot raids that it detects. The algorithm is not configurable because it is designed to work dynamically, but in the future, you will be able to disable/enable the antispam via a command.

**NOTE**: Beemo will only post logs to the specified channel when a raid is detected against your server. If you have followed the directions above, Beemo is already passively protecting your server with no other configuration required (or available).  Beemo is a quiet bot so remember that "no news is good news."

<a id="undetected-raids"></a>If a raid occurs that Beemo does not detect, you can submit a report using the `/report-raid` command or to the [#spam-reports](https://discord.com/channels/697474023914733575/856561090623569951) channel on the [Beemo Discord server](https://beemo.gg/discord) (be sure to check the pins for the required format to do so!) to help improve the algorithm. Please keep in mind that Beemo's antispam is provided for free and that the developers don't have time to be on-call for all of the servers.


### How To Contribute

Contributing to the documentation is relatively simple! At the bottom of every documentation page is an "`Edit on GitHub`" button; Simply click this button and make your changes on the page it opens- and submit a pull request when you're done. The pull request will be reviewed, and if your changes are good, they will be added to the docs!

### Documentation Contributors

<ul class="list-style-none">
{% for contributor in site.github.contributors %}
  <li class="d-inline-block mr-1">
     <a href="{{ contributor.html_url }}"><img src="{{ contributor.avatar_url }}" width="32" height="32" alt="{{ contributor.login }}"/></a>
  </li>
{% endfor %}
</ul>
