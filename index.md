---
title: Home
layout: home
nav_order: 1
description: Mojang Maps is a Google Maps like navigation system for Minecraft.
---

# Mojang Maps

> This wiki is currently in beta.
{: .warning}

_A Google Maps like navigation system for Minecraft._

## Run Mojang Maps

To run Mojang Maps, you´ll need to (have) set up a [SpigotMC] or [PaperMC] Minecraft server. After that download [the latest Mojang Maps release] and place it in your `plugins` folder. To set up a road system and configure Mojang Maps, please see [the getting started page].

If your server has no access to the internet/GitHub.com, please see [Using/Setting up Mojang Maps on a server without access to the internet. - Advanced/Custom].

## About Mojang Maps/FAQ

Mojang Maps is a Google Maps like navigation system for Minecraft.

### Why did I start Mojang Maps?

I started Mojang Maps as a weird idea that had a high change I wouldn't make it. I heard about things like [Dijkstra's Algorithm]. It was just this weird idea that was stuck in my head. At the time I had done here and there some [Spigot]/Bukkit work, but never really worked on a project.

It started with me just finding a way to store locations and implementing [Dijkstra's Algorithm] with [this video] ([commit febb798]). After that I started adding roads and asked [ChatGPT] how to turn a list of directions to one direction to one point ([version 1.0]). Added a language system and showed on which road you were ([version 1.1] and [version 1.3]).

I'm currently working on a GUI, to make Mojang Maps more accessible.

For future projects please see [the roadmap].

### Why the name Mojang Maps?

Google Maps is made by Google. Minecraft is made by Mojang. It is Google Maps for Minecraft, so Mojang Maps.

Reason I haven't changed it: I haven't yet gotten a cease and desist letter from Mojang yet to stop using their name, so I just use this name.

### How can I support Mojang Maps?

You can donate with PayPal, or just help by [translating] or writing code.

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
[Dijkstra's Algorithm]: https://en.wikipedia.org/wiki/Dijkstra%27s_algorithm
[Spigot]: https://www.spigotmc.org/
[this video]: https://youtube.be/BuvKtCh0SKk
[ChatGPT]: https://chat.openai.com
[commit febb798]: https://github.com/Abelkrijgtalles/mojang-maps/commit/febb798009b1b007ef7bbec8a6f5704f1ab19f2
[version 1.0]: https://github.com/Abelkrijgtalles/mojang-maps/tree/1.0
[version 1.1]: https://github.com/Abelkrijgtalles/mojang-maps/tree/v1.1
[version 1.3]: https://github.com/Abelkrijgtalles/mojang-maps/tree/1.3
[the roadmap]: {% link roadmap.md %}
[translating]: https://crowdin.com/project/mojang-maps