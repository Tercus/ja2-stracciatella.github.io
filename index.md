---
layout: page
---

## What is Jagged Alliance 2 Stracciatella?

The Jagged Alliance 2 Stracciatella project aims to fix existing bugs of the original (called "vanilla") game. It also tries to bring jagged alliance to as many plattforms and operating systems as possible. Another focus of the project is to make the game moddable in an easy and comfortable way.

As of now, it should run on all 32bit little endian platforms, which support SDL. This includes (but is not limited to) BSDs, Linuxes and Windows on x86. A long term goal is to remove the 32bit and little endian restrictions. There are reports of running it successfully one some hand held devices, such as Android smartphones.

Data files from the original game are still required and will be used by JA2-Stracciatella.

Get started: [How to run](/how-to-run) - [Download](/download)

Discussions: [On The Bears Pit](http://thepit.ja-galaxy-forum.com/index.php?t=thread&frm_id=224) - [On ModDB](http://www.moddb.com/mods/ja2-stracciatella)

## Features

JA2 Stracciatella already includes a few special features that can be used to enhance the original game. None of them are required and can most of them are disabled by default. So make sure to look through them before starting a new game

### High Resolution Support

Added support for high video resolutions. For example, game can be started in 1680x1050  mode like this: `ja2.exe -res 1680x1050`.

![Ja2 Stracciatella in 1680x1050 resolution](/img/features/high-res.jpg)

### Integrated Editor

The map editor is now integrated into the game. Start it like this: `ja2.exe -editor`.

![Ja2 Stracciatella Editor](/img/features/integrated-editor.jpg)

### Included mods

JA2 Stracciatella includes a handful of mods that you can use in conjunction with it. Most of them only change smaller details or help with more tedious parts of the game, especially if it's not your first play-through. The mods can be found in the `mods` folder and need to be copied into the Jagged Alliance 2 game directory. The following mods are included:

-*From russia with love*: There is a little something waiting for you in Omerta.

-*Generous rebels*: It adds some goodies to the rebel's hideout in Omerta.

-*IMP-quiz - honest answers*: It shows the effect each answer in the IMP quiz has on the player character.

-*O-fortuna*: A dramatic intro music for jagged alliance

-*test-json-dialogs*: Replaces all Igor's dialog quotes with "Test quote XXX"

### Configuration options

JA2 Stracciatella also comes with special configuration files. These can be found in the `externalized` folder. The most important one is the `game.json`. There you can enable and diable values of the original game (such as starting money), as well as enabling or disabling features introduces by this project. What each option does is explained in the file itself. Just open it with a texteditor and edit the values.

## How to Contribute

The best way to contribute is to make a pull request with a bug fix. Please see list of open issues [here](https://github.com/ja2-stracciatella/ja2-stracciatella/issues).

The second best way is to file a bug report if you encounter a bug or help with retesting issues [where we need more info](https://github.com/ja2-stracciatella/ja2-stracciatella/labels/retest).
