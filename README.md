# ![Discord+](https://github.com/PlusInsta/discord-plus/blob/master/assets/wordmark_black.svg)
A Discord theme inspired by Google's Material Theme.

![Screenshot](https://dl.dropbox.com/s/6r69giyb3hnl1g6/Image2_2.png)

## What is this?

**Discord+** is a theme for [Discord](https://discordapp.com), a popular messaging and voice chat service.

Using a modification called [BandagedBD](https://github.com/rauenzi/BetterDiscordApp), you can change the look of the app, customize its behavior, and even add functionality through plugins! If you already have it installed, you're ready to install my theme. It's as easy as downloading a file and moving it to the right folder.

## User customization
This theme aims to be **fully customizable**.
There are variables at the top of the file that allow you to change things like the background image, the roundness of the UI, and the accent color. You can also change the fonts to any fonts installed on your device.


You could stylize it after a game you like.

![Minecraft-styled Discord+](https://dl.dropbox.com/s/5h9mjteils9fcck/Image2_2_customized_minecraft.png)

Or...if you really wanted to...you could change the background image to cardboard and set the font to Comic Sans.

![please dont do this at home kids](https://dl.dropbox.com/s/fd8swddk8v67c1b/Image2_2_customized.png)

Check the [FAQ](https://github.com/PlusInsta/discord-plus/wiki/FAQ) for a full list of what you can do.

## Complete theme
This theme aims to style everything on Discord.
If there's anything that is not themed, be it an official feature, a plugin, or third party feature, open an issue along with some information about the unthemed feature and I'll see what I can do.

I also use this theme myself, so if there's something's bugging you, it probably bugs me too. Expect a quick update if something big breaks.

## Cross-platform compatibility
The theme works on Windows, macOS, and Linux. There are some minor differences, though.
Windows has a draggable titlebar (with the Discord+ "logo" for good measure), macOS has window buttons at the top left (sans Discord+ logo), and Linux has your desktop environment's borders (which means I can't customize it).

Previously, this theme worked with both browsers and BetterDiscord. However, as Discord kept making their code more difficult to work with, I decided to move entirely to BandagedBD's normalized classes. What this means for you is that you'll have to use Zere's fork of BetterDiscord to use my theme. Not only does this mean Discord+ is unlikely to break overnight, it also means I have more stable code to work with. Until BetterDiscord v2 is finished, your best bet is to use normalized classes. I apologize if any of your plugins don't work with normalized classes, but it's a necessary evil.

# Download
https://rawgit.com/PlusInsta/discord-plus/master/DiscordPlus-master.theme.css
This file always loads the latest version so you don't have to. To download it, open the context menu and click "Save as..." Instructions on how to install below. It's compatible with all future versions, though if I add new variables you'll need to update (or add the new values to the file) to customize them.

# Installation
## **Windows**:
* Download `DiscordPlus-master.theme.css` or `DiscordPlus.theme.css`
* Open your Downloads folder
* Cut the downloaded file (Ctrl + X)
* Type `%AppData%\BetterDiscord\themes` in the address bar
* Paste it here (Ctrl + V)
* Launch Discord
* Enable the theme in Settings

## **macOS**:
* Download `DiscordPlus-master.theme.css` or `DiscordPlus.theme.css`
* Open Finder
* Press ⇧⌘G
* Type `~/Library/Preferences/BetterDiscord/themes`
* Click the Downloads on the Dock
* Drag the file into the folder
* Launch Discord
* Enable the theme in Settings

## **Linux**:
* Download `DiscordPlus-master.theme.css` or `DiscordPlus.theme.css`
* Open the Terminal
* type `mv ~/Downloads/DiscordPlus* ~/.config/BetterDiscord/themes`
* Run `discord`
* Enable the theme in Settings (sorry, no Terminal command for this!)
