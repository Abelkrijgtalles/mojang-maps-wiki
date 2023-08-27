---
title: Config
layout: home
parent: Advanced
---

# Config
> The `config.yml` file is in `plugins/MojangMaps`
{: .note}

How to configure every function in the `config.yml` file.

## Removing the _currently on_-message

The _currently on_-message looks like this:
![](../../assets/images/CurrentlyOn.png)
To remove the _currently on_-message, go into `config.yml` and set `street-actionbar` to `false`:
````yaml
# If true, then the plugin shows the current street in the ActionBar.
street-actionbar: false
````
If the server is on when making this change, please reload the server with `/reload confirm`. This will stop and start all the plugins on your [SpigotMC]/[PaperMC] server.

[SpigotMC]: https://www.spigotmc.org/
[PaperMC]: https://papermc.io/

## Changing the language

Please see [Changing the language - Getting Started].

[Changing the language - Getting Started]: ../../getting-started.html#changing-the-language