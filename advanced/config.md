---
title: Config
layout: home
parent: Advanced
---

# Config
> The `config.yml` file is in `plugins/MojangMaps/`.
{: .note}

> Changing anything in `config.yml` requires Mojang Maps to be run at least one time and a server reload (command: `/reload confirm`) after the change.
{: .note}

How to configure every function in the `config.yml` file and some other setup related things.

## Removing the _currently on_-message

The _currently on_-message looks like this:
![](../../assets/images/CurrentlyOn.png)
To remove the _currently on_-message, go into `config.yml` and set `street-actionbar` to `false`:
````yaml
# If true, then the plugin shows the current street in the ActionBar.
street-actionbar: false
````

## Changing the language

Please see [Changing the language - Getting Started].

[Changing the language - Getting Started]: ../../getting-started.html#changing-the-language

## Using/Setting up Mojang Maps on a server without access to the internet.
> The list of language codes can be found [here].
{: .note}

If your server doesn't have access to the internet/GitHub.com, you'll have to download the translations file manually from `github.com/Abelkrijgtalles/mojang-maps-data/blob/main/[language code]/[language code].json`, and the raw file from here: `raw.githubusercontent.com/Abelkrijgtalles/mojang-maps-data/main/[language code]/[language code].json`. After this, place the file in `plugins/MojangMaps/` with the name `messages.json`.

You don't have to set `language` in `config.yml` to your language code, but it's highly recommended. To use custom messages please see [Using custom messages/text](#using-custom-messagestexts).

## Using custom messages/texts
> The `%s` symbol in `messages.json` is a value. Always leave this in your edited messages or the values won't display.
{: .warning}

> When updating Mojang Maps, make sure to add new messages for new words/sentences. These will be noted in the release notes of version 1.5 and later.
{: .warning}

To use custom messages, set `language` in `config.yml` to `custom`:
````yaml
# If you change this to custom, you can change the messages in messages.yml. Codes that can be used as language: https://github.com/Abelkrijgtalles/mojang-maps-data/blob/main/README.md#the-following-codes-can-be-used-as-language
language: custom
````
Then go into `messages.json` and change (some of) the messages (a reload could be possible to get these changes into effect):
````json
{
  "nolocationroad": "There aren't any locations in this road.",
  "unnamedroad": "This road doesn't have a name",
  "locationalreadyregistered": "This location is already registered.",
  "registerlocation": "A very cool location has been summoned at X: %s, Z: %s.",
  "currentlyon": "Currently on: %s.",
  "blocksprediction": "%s\nThis will take %s blocks",
  "thengoto": "%s then go to\n",
  "noarguments": "You did not run the command with arguments. Please run it again with the %s arguments.",
  "example": "Example: %s",
  "toomanyarguments": "You have run the command with too many arguments. Please run it again with the %s arguments.",
  "invalidcoordinates": "Invalid coordinates. Please run it again with the right coordinates.",
  "finallygoto": "Then finally go to X: %s Z: %s.",
  "registerroadarguments": "(optional) name of road> <coordinates of the locations as X Y Z with a space between arguments",
  "registeredroad": "Registered a new road.",
  "notonaroad": "You are currently not on any street.",
  "noargumentsother": "You did not run the command with arguments. Please run it again with the right arguments.",
  "load": "Loading, this could take some time.",
  "pathnotfound": "Couldn't find a path.",
  "outdated": "Mojang Maps is outdated, please download the newest version at: %s"
}
````
For example, I've changed message 2 and 4 in this version of `messages.json`

If you want the rest of the messages in a different language then English and don't want to translate yourself, set `language` to your language code (list of language codes can be found [here]), reload the server, and follow the steps of [Using custom messages/text](#using-custom-messagestexts).

[here]: https://github.com/Abelkrijgtalles/mojang-maps-data/blob/main/README.md#the-following-codes-can-be-used-as-language