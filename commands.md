---
title: Commands
layout: home
nav_order: 3
---

# Commands

This is a list of all the commands in Mojang Maps

## /registerlocation

| Command             | Aliases           | Usage               | Permission                     | Description          |
|---------------------|-------------------|---------------------|--------------------------------|----------------------|
| `/registerlocation` | `/createlocation` | `/registerlocation` | `mojangmaps.register.location` | Register a location. |

This registers an individual location at the players location. A location is a point that you can use to travel from a to b. Basically a point of a road.

## /registerroad

| Command             | Aliases       | Permission                 | Usage                                                                                                            | Description      |
|---------------------|---------------|----------------------------|------------------------------------------------------------------------------------------------------------------|------------------|
| `/registerlocation` | `/createroad` | `mojangmaps.register.road` | `/registerroad <(optional) name of road> <coordinates of the locations as X Y Z with a space between arguments>` | Register a road. |

This registers a road. A road is a collection of locations. To set up a road, see [Creating your first road - Getting Started]. For more advanced things, see: [Advanced/Road]

[Creating your first road - Getting Started]: getting-started.html#creating-your-first-road
[Advanced/Road]: advanced/road.html

## /goto

| Command | Aliases | Permission              | Usage               | Description                |
|---------|---------|-------------------------|---------------------|----------------------------|
| `/goto` |         | `mojangmaps.using.goto` | `/goto <X> <Y> <Z>` | Go to a specific location. |

This is basically just saying: "I would like to go to <X> <Y> <Z>. How would I get there?"

## /whereamistanding

| Command             | Aliases                | Permission                      | Usage               | Description                  |
|---------------------|------------------------|---------------------------------|---------------------|------------------------------|
| `/whereamistanding` | `/whichroad`, `/where` | `mojangmaps.using.viewlocation` | `/whereamistanding` | Shows where you're standing. |

This is basically the ActionBar message in a command.

## /reloadconfigsfromdisk

| Command                  | Aliases                           | Permission                      | Usage                    | Description                        |
|--------------------------|-----------------------------------|---------------------------------|--------------------------|------------------------------------|
| `/reloadconfigsfromdisk` | `/reloadconfigs`, `/reloadconfig` | `mojangmaps.util.reloadconfigs` | `/reloadconfigsfromdisk` | Reloads all the configs from disk. |

This reloads the plugin. Technically the configs, but it's the equivalent.

## /navigation

| Command       | Aliases | Permission                    | Usage                     | Description                                                    |
|---------------|---------|-------------------------------|---------------------------|----------------------------------------------------------------|
| `/navigation` |         | `mojangmaps.using.navigation` | `/navigation <X> <Y> <Z>` | Go to a specific location and view the navigation in GUI form. |

[/goto](#goto) in GUI form. This GUI is made possible by [SpiGUI]. See: [/goto](#goto).

[SpiGUI]: https://github.com/SamJakob/SpiGUI