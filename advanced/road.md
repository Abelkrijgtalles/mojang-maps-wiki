---
title: Roads
layout: home
parent: Advanced
---

# Roads
> The `nodes.yml` file is in `plugins/MojangMaps/`
{: .note}

## Deleting a road
> Deleting `nodes.yml` without a backup could delete your whole road system, and you would have to create it again from scratch!
{: .warning }

At this moment (version 1.5) there isn't a way/command to delete a road. The only way to do it as of this moment, is to delete `nodes.yml`, reload the server/plugin with `/reload confirm` and retype all the `/createroad` commands except for the road(s) that you want to delete. You can find the commands in two ways:
- Searching through all the log files in `logs` (doesn't require other plugins)
- Having an external logger like [DiscordSRV] that logs it in a Discord channel or one log and searching through that.

[DiscordSRV]: https://github.com/DiscordSRV/DiscordSRV