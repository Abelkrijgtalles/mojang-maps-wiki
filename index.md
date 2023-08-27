---
title: Home
layout: home
nav_order: 1
description: Mojang Maps is a Google Maps like navigation system for Minecraft.
---

# Mojang Maps

_A Google Maps like navigation system for Minecraft._

## Run Mojang Maps

To run Mojang Maps, you´ll need to (have) set up a [SpigotMC] or [PaperMC] Minecraft server. After that download [the latest Mojang Maps release] and place it in your `plugins` folder. To set up a road system and configure Mojang Maps, please see [the getting started page].

If your server has no access to the internet/GitHub.com, please see [Using/Setting up Mojang Maps on a server without access to the internet. - Advanced/Custom].

---
Mojang Maps is made by the following people:
<ul class="list-style-none">
{% for contributor in site.github.contributors %}
  <li class="d-inline-block mr-1">
     <a href="{{ contributor.html_url }}"><img src="{{ contributor.avatar_url }}" width="32" height="32" alt="{{ contributor.login }}"></a>
  </li>
{% endfor %}
</ul>

[SpigotMC]: https://www.spigotmc.org/
[PaperMC]: https://papermc.io/
[the latest Mojang Maps release]: https://github.com/Abelkrijgtalles/mojang-maps/releases/latest/
[the getting started page]: {% link getting-started.md %}
[Using/Setting up Mojang Maps on a server without access to the internet. - Advanced/Custom]: advanced/config.html#usingsetting-up-mojang-maps-on-a-server-without-access-to-the-internet