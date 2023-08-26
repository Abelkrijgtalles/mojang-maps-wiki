---
title: Getting started
layout: home
nav_order: 2
---

## Creating your first road
A road is basically bundled locations (points) with optionally a name. To create your first road, run the command `/createroad` with the name of your road (leave blank for no name), and the coordinates of the locations in your road. It should look something like this:
- With name: `/createroad CoolRoad 0 69 0 10 69 0 10 69 10`
- Without name: `/createroad 0 69 0 10 69 0 10 69 10`

At this moment (version 1.4) there is no way to have spaces in your road name as this messes with the Minecraft argument system. Mojang Maps will also automatically generate locations between locations with a gap larger than 5 blocks.