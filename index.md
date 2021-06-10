---
layout: default
title: Home
nav_order: 1
description: "Beemo is a free antispam Discord Bot that can stop userbot raids against your server."
permalink: /
---

# Beemo
{: .fs-9 }

Beemo is a free antispam Discord Bot that can stop userbot raids against your server.

[Beemo.gg](https://beemo.gg){: .btn .btn-primary .fs-5 .mb-4 .mb-md-0 .mr-2 } [Discord](https://beemo.gg/discord){: .btn .btn-primary .fs-5 .mb-4 .mb-md-0 .mr-2 }

{: .fs-6 .fw-300 }

## Adding Beemo & Setting Up 

Adding Beemo to your server is super simple and takes seconds. 

1. Go to Beemo's OAuth page [here](https://beemo.gg/invite) and go through the steps to invite Beemo. The minimum permissions are
```Ban members, Send messages, Embed Links, Reactions```
2. Move Beemo's integration role above the members in your server, making sure it's highest role is above the highest member role. 

3. (Optional) Set up an ActionLog with `/banpool actionlog #channel`

And you should be done! Beemo should be operating in your discord server and automatically checking and banning any spam activity. There are little other steps that you need to take from this point.


## About the Documentation

### License
See more about the documentation licensing [here](https://github.com/AyuAi/beemo-docs/blob/main/LICENSE).

### Contributing

See more about how to contribute to the documentation [here](https://github.com/AyuAi/beemo-docs/blob/main/CONTRIBUTING.md).

### Documentation Contributors

<ul class="list-style-none">
{% for contributor in site.github.contributors %}
  <li class="d-inline-block mr-1">
     <a href="{{ contributor.html_url }}"><img src="{{ contributor.avatar_url }}" width="32" height="32" alt="{{ contributor.login }}"/></a>
  </li>
{% endfor %}
</ul>