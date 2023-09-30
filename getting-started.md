---
title: Getting started
layout: home
nav_order: 2
---

# Getting Started

## Creating your first road
A road is basically bundled locations (points) with optionally a name. To create your first road, run the command `/createroad` with the name of your road (leave blank for no name), and the coordinates of the locations in your road. It should look something like this:
- With name: `/createroad CoolRoad 0 69 0 10 69 0 10 69 10`
- Without name: `/createroad 0 69 0 10 69 0 10 69 10`

The following road will look like this:
![](../assets/images/CoolRoad.png)
At this moment (version 1.5) there is no way to have spaces in your road name as this messes with the Minecraft argument system. Mojang Maps will also automatically generate locations between locations with a gap larger than 5 blocks.

## Changing the language
To change the language you'll have to have run Mojang Maps for at least one time. After that open `plugins/MojangMaps/config.yml`. In `config.yml` you'll see something like this:
````yaml
# If you change this to custom, you can change the messages in messages.yml. Codes that can be used as language: https://github.com/Abelkrijgtalles/mojang-maps-data/blob/main/README.md#the-following-codes-can-be-used-as-language
language: en
````
To find your languages language code/to see the available languages, click [this link]. [This link] will also be found in `config.yml`.

For example, if we would like to change the language to Dutch, we would have to change `language` to `nl`:
````yaml
# If you change this to custom, you can change the messages in messages.yml. Codes that can be used as language: https://github.com/Abelkrijgtalles/mojang-maps-data/blob/main/README.md#the-following-codes-can-be-used-as-language
language: nl
````
If (some) text is English even tho you've changed the language, please consider [helping with translations].

## Finally, start using Mojang Maps
Now that the setup is finished, you could add more road by using `/createroad`. To go to a location, just use `/goto` or `/navigation` if your Mojang Maps version is 1.5 or higher.

[this link]: https://github.com/Abelkrijgtalles/mojang-maps-data/blob/main/README.md#the-following-codes-can-be-used-as-language
[This link]: https://github.com/Abelkrijgtalles/mojang-maps-data/blob/main/README.md#the-following-codes-can-be-used-as-language
[helping with translations]: https://crowdin.com/project/mojang-maps