---
layout: page
published: true
---
# What is the Stracciatella project?
---
The Jagged Alliance 2 Stracciatella project aims to fix existing bugs of the original (called "vanilla") game. It also tries to bring jagged alliance to as many plattforms and operating systems as possible. Another focus of the project is to make the game moddable in an easy and comfortable way.

As of now, it should run on all 32bit little endian platforms, which support SDL. This includes (but is not limited to) BSDs, Linuxes and Windows on x86. A long term goal is to remove the 32bit and little endian restrictions. There are reports of running it successfully one some hand held devices, such as Android smartphones.

# Special features
---
JA2 Stracciatella already includes a few special features that can be used to enhance the original game. None of them are required and can most of them are disabled by default. So make sure to look through them before starting a new game

## _Included mods_

JA2 Stracciatella includes a handful of mods that you can use in conjunction with it. Most of them only change smaller details or help with more tedious parts of the game, especially if it's not your first play-through. The mods can be found in the `mods` folder and need to be copied into the Jagged Alliance 2 game directory. The following mods are included:

-*From russia with love*: There is a little something waiting for you in Omerta.

-*Generous rebels*: It adds some goodies to the rebel's hideout in Omerta.

-*IMP-quiz - honest answers*: It shows the effect each answer in the IMP quiz has on the player character.

-*O-fortuna*: A dramatic intro music for jagged alliance

-*test-json-dialogs*: Replaces all Igor's dialog quotes with "Test quote XXX"


## _Configuration options_

JA2 Stracciatella also comes with special configuration files. These can be found in the `externalized` folder. The most important one is the `game.json`. There you can enable and diable values of the original game (such as starting money), as well as enabling or disabling features introduces by this project. What each option does is explained in the file itself. Just open it with a texteditor and edit the values.

# How to Run
---
1. Install original Jagged Alliance 2 game on your computer.  Data files from the original game will be used by JA2-Stracciatella. If you're installing the linux port, make sure to copy over files from CD2 too.

1. [Download JA2-Stracciatella](/download) or [compile](https://github.com/ja2-stracciatella/ja2-stracciatella/blob/master/COMPILATION.md) it from the source codes.

1. Start the game the first time.  It will create the configuration file in

   - `%USERPROFILE%\Documents\JA2\ja2.ini` on Windows.
   - `~/.ja2/ja2.ini` on Linux or OS X.

1. Edit the configuration file and set parameter data_dir to point on the directory where the original game was installed on step 1.  For example:

   - `D:\games\ja2\` on Windows.
   - `/home/user/games/ja2-installed` on Linux or OS X.


1. If you have a non-english version of the original game, you need to start JA2-Stracciatella with parameter telling which version of the game you are using.  For example

   - ```ja2.exe -resversion FRENCH``` on Windows.
   - ```ja2 -resversion FRENCH``` on Linux or OS X.

   You should see the start screen now.

   ![Ja2 Stracciatella start screen](/img/start-screen.png)

Further command line options are available. To list available options run

- `ja2.exe -help` on Windows.
- `ja2 -help` on Linux or OS X.
