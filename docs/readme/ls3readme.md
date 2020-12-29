---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: LS_readme
permalink: /readme/ls3/
---

![](https://i.imgur.com/Vokoo6f.png)

## This readme is a work in progress
Links will be broken, entire sections are incomplete, and phrasing/ordering of the Readme still needs to be revised.


Current version: 3.0.0 Dev Build 1 (Pre-Alpha)

![total-installs](https://img.shields.io/endpoint?label=Total%20Installs&style=for-the-badge&url=https://build.wabbajack.org/metrics/badge/living_skyrim/total_installs_badge.json)  
![build-status](https://img.shields.io/endpoint?label=List%20Status&style=for-the-badge&url=https://build.wabbajack.org/lists/status/living_skyrim/badge.json)

## Table of Contents

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-0pky{border-color:inherit;text-align:left;vertical-align:top}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-0pky"></th>
    <th class="tg-0pky"></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-0pky"><a href="#preface"><span style="color:#905">[Preface](#preface)</span></a><br><a href="#before-you-get-started"><span style="color:#905">[Before You Get Started](#before-you-get-started)</span></a><br><a href="#system-specifications"><span style="color:#905">[System Specifications](#system-specifications)</span></a><br>Important Links<br>Screenshots<br>Videos<br>Pre-Installation<br>Steam &amp; SSE Setup<br>Wabbajack Preparations<br>Installing the List<br>With Nexus Premium<br>Without Nexus Premium<br>Game Folder Files<br>Post-Wabbajack Install<br>Mod Organizer 2<br>Configuration-Specific Setup<br></td>
    <td class="tg-0pky">ENB<br>Updating Living Skyrim<br>Launching Living Skyrim<br>The MCM Settings<br>Getting Started in Living Skyrim<br>Important Mods You Need to Know About<br>Character Customization Mods<br>The Economy and Loot Mods<br>Bug Reporting, Github, and You<br>Common Issues<br>Wabbajack Issues<br>Gameplay Issues<br>Adding to Living Skyrim<br>Performance Optimizations<br>Other Common Questions<br>Credits &amp; Thanks</td>
  </tr>
</tbody>
</table>

## Preface

## Before You Get Started
Before you get started installing or playing Living Skyrim, it's important to note a few things:

* You are not required to have Nexus Premium to install Living Skyrim, however, it is **highly recommended.** Nexus Premium will cut your install time to a fraction of what it would be by automating both the mod download and mod install processes of installing the list.
* As of version 3.0.0, Living Skyrim requires 208GB of hard drive space on top of the ~11GB Skyrim: Special Edition base files. Installing to an SSD/NVMe is not required, but also **highly recommended.** Download and installation times vary based on your computer and internet speeds, but expect the entire process to take a few hours. If you are installing the list without Nexus Premium, expect the process to take a couple of days of 8+ hour sessions downloading mods.
* To maximize performance, both Skyrim: Special Edition and Living Skyrim should be installed on the same hard drive, ideally an SSD/NVMe. This is not required, just recommended if you want the smoothest gameplay experience.
* If you are not familiar with the contents of this modlist, a complete documentation of every mod in the list including links to the mods is available on the [LS3 Modlist Spreadsheet]().
* If you instead only wish for a brief overview of the major changes this modlist makes, you should refer to the [Important Mods You Need to Know About](#important-mods-you-need-to-know-about) section of this document.
* Autosaves for this modlist are disabled. This save option is known to cause issues with modlists running a large number of scripted mods. Instead, quicksaves are automatically turned into manual saves by SSE Engine Fixes. It is recommended to save early and often. Every 15 minutes and before interacting with quest NPCs, quest objects, and before entering new zones should be sufficient.
* Continuing the last point, it is always better to save **before** entering a loading screen instead of after. After a loading screen it is very likely that scripts will be running for at least 30 seconds, so if you must save after a loading screen, at least wait that long before doing so.
* Wabbajack does support updating an existing installation of a modlist. However, as part of this process, it does delete files that don't match with what it is installing. This includes RaceMenu presets, mods you've added/changed, and possibly even save files. It is a good practice to keep backups of your save files so that you can update safely. Saves are stored within the folder you install Living Skyrim to.
* Living Skyrim 3 has been updated such that NPCs and player characters are never nude. Underwear is worn by all NPCs and cannot be unequipped.
* Adding to, changing, or removing from Living Skyrim is not supported. See the [Adding to Living Skyrim](#adding-to-living-skyrim) section of this document for more details.
* As many common issues as I could find have been documented in the [Common Issues](#common-issues) section of this document. Refer to this before asking for support.
* If you want some tips related to getting started playing the list, refer to the [Getting Started in Living Skyrim](#getting-started-in-living-skyrim) section of this document.
* By default, Living Skyrim has the game running in exclusive fullscreen mode to assist with game performance.

### System Specifications
Living Skyrim v3.0.0 has been cut back severely from the performance hog it was in v2.0.0 and on. Textures range from 512x512 to 4K and everything in between. The following system is ForgottenGlory's personal computer and is able to run the list at a constant 60FPS including ENB at 1440p monitor resolution.

- CPU: Intel i5-8600K Overclocked to 4.2GHz 
- RAM: 16GB DDR4 (16299MB actual)
- GPU: nVidia RTX 2080 Super 8GB (8192MB actual)
- Monitor: Dell S2716DGR 2560x1440 @ 144hz
- Storage: Sabrent Rocket 2TB M.2 NVMe 2280

In general, it is recommended that you have a processor with a clock speed of at least 3GHz and a graphics card with at least 6GB of VRAM. 4GB graphics cards may be able to run the list if you do not use ENB, but it is not guaranteed.

If your PC is struggling to run Living Skyrim, see the [Performance Optimizations](#performance-optimizations) section of this document for tips and tricks to receive better performance.

### Important Links
[The Modlist Spreadsheet (INCOMPLETE)]()  
[Living Skyrim FAQ & Troubleshooting](#troubleshooting--faq)  
[Living Skyrim Bug & Suggestions Tracker](https://github.com/ForgottenGlory/Living-Skyrim-3/issues)  
[User Testimonials](https://docs.google.com/document/d/1eXeG852teL9EOnIHTAFTLW4Rq1c_pYGRYPtW_eNJqLg/edit?usp=sharing)  
[Living Skyrim Discord](https://discord.gg/9dFvGnc)  
[Living Skyrim Patreon](https://www.patreon.com/LivingSkyrim)  
[Install Tutorial Video](https://youtu.be/sW7s5IhN7qs)  

#### Screenshots


#### Videos


## Pre-Installation
### Steam & Skyrim Special Edition Setup
Before proceeding with installation, it's important that your Steam and Skyrim Special Edition install are configured correctly.

First, make sure that your Steam library, and therefore the Skyrim Special Edition install folder, is not located within your Program Files or Program Files (x86) folders. Having the Steam library or your copy of Skyrim Special Edition in either of these folders is known to cause issues. Instructions on how to move your Steam library can be found elsewhere on the internet.

Next, you'll need a clean copy of Skyrim Special Edition. To get your copy to this state, follow these steps:

1. In Steam, uninstall Skyrim: Special Edition (Right-click > Manage > Uninstall). 
2. If there are any files leftover in the Skyrim Special Edition game folder (Right-click > Properties… > Local Files > Browse Local Files…), delete them.
3. Install Skyrim: Special Edition.

Afterwards, you need to disable automatic updates for Skyrim to avoid a game update breaking your copy of the game and therefore the modlist.

1. In Steam, set Skyrim: Special Edition to update only when opened. (Right-click > Properties… > Updates > Automatic updates > Only update this game when I launch it)
2. In Steam, disable the Steam Overlay. (Right-click > Properties... > General > Enable the Steam Overlay while in-game checkbox)
   
Finally, once the above steps are completed, launch Skyrim SE through Steam to create any INI or registry entries the game needs. Immediately exit the launcher once it has successfully selected a graphics preset for your hardware. The INIs it just created will be overwritten by the ones included in the modlist, but this is a necessary step for Wabbajack to recognize that you have the game installed.

### Wabbajack Preparations
A video version of the installation instructions from this point forward exists here: [Click Me!](https://youtu.be/sW7s5IhN7qs)  

We'll now setup the folders needed for the installation to proceed smoothly.

1. Create two empty folders: one named Wabbajack and the other named Living Skyrim.
2. Ensure that these two folders are not within any of the following folders: your Skyrim Special Edition install folder, your Program Files folder, or your Program Files (x86) folder. 
3. Additionally, ensure that these two folders are not contained within each other. For example,`[install drive]\Wabbajack\Living Skyrim`is **incorrect**. Ideally, both the Wabbajack folder and Living Skyrim folder will be in the root of the drive you are installing the list to. Example:`[install drive]\Wabbajack`and`[install drive]\Living Skyrim`
4. Ensure that both the Wabbajack and Living Skyrim folders are completely empty. If they are not empty, make them empty.
5. Download the latest version of Wabbajack from the Wabbajack website: [Wabbajack](https://www.wabbajack.org/#/).
6. Place the Wabbajack.exe file you just downloaded into the folder you created earlier called Wabbajack.

## Installing The List
If you are updating your existing installation of Living Skyrim, skip to the [Updating Living Skyrim](#updating-living-skyrim) section of this document.

It's now time to begin the installation of the list. Follow these steps:

1. Run Wabbajack.exe. The program should automatically update itself to the latest version.
2. At the bottom of the window, click Browse Modlists.
3. Locate the Living Skyrim card. You can filter the gallery by game using the dropdown menu at the top of the gallery. Living Skyrim is listed under Skyrim Special Edition.
4. On the Living Skyrim card, click the download/down arrow icon.
5. Once it finishes downloading, click the play/right arrow icon on the Living Skyrim card.
6. Below the image you see of the Living Skyrim logo, there are three text boxes. The second and third need to be filled out.
7. Click the three dots in the second (middle) box. Navigate to your Living Skyrim folder and then select this folder in the window that appears. This middle box tells you where the list will be installed, including the copy of Mod Organizer 2 that you'll need to use to launch the list.
8. The third (bottom) box will automatically populate using the folder you just selected. This third box tells you where all of the mods will be downloaded. If you have hard drive limitations, you may change this to another folder on another hard drive by clicking the three dots in this box and selecting a new folder.
9. Click the play/right arrow button to begin the installation.

### With Nexus Premium
10. Wabbajack will ask you to login to Nexus and authorize your API key so it can download mods for you automatically. If this doesn't happen, it isn't a problem and means you've already set this up.
11. Wabbajack will now download and install all of the mods. This will take a while (3-4 hours at most). Take this opportunity to read the [Important Mods You Need To Know About](#important-mods-you-need-to-know-about) section of this document. This isn't optional, you will have to read this section of the readme at some point, so now is a good time to do it.

### Without Nexus Premium
10. Wabbajack will prompt you to click all the needed buttons to download the modlist. Be prepared for this to take an extraordinarily long time. Current reports indicate installing the list manually takes approximately 24 hours. Also be aware that due to the amount of time required when installing this list manually, the list may update during the time it takes to install and you may need to start over if that happens. Installing with Nexus Premium isn't required, but is strongly recommended if you value your time. If you must install the list manually, put on an audiobook or a TV show and make a day of it.

Once complete, Wabbajack will indicate it is done with a green box that says "Installation complete". You may exit Wabbajack after this appears.

If it does not complete successfully (a red box with "Installation failed"), consult the [Common Issues](#common-issues) section of this document, or visit the [Living Skyrim Discord server](https://discord.gg/9dFvGnc) for assistance. 

### Game Folder Files
Now, you must copy some files to your installation folder of Skyrim Special Edition. This is required for the list to function properly. 

1. Navigate to your Living Skyrim folder and locate the "Game Folder Files" folder.
2. Copy everything inside the "Game Folder Files" folder into your Skyrim Special Edition install folder.
3. Overwrite existing files if you are prompted to do so.

These files include SKSE and Engine Fixes Part 2, both of which are essential for the list to function correctly. Failure to copy these files will result in the list not working.

## Post-Wabbajack Install
### Mod Organizer 2
Among other things, Wabbajack has installed a copy of Mod Organizer 2 for you. This copy of Mod Organizer 2 is specific to Living Skyrim and will not affect any other modlists you have installed.

1. Inside your Living Skyrim folder, locate and launch ModOrganizer.exe. If this is not inside the folder, your installation has failed and you need to consult the [Common Issues](#common-issues) section of this document.
2. Mod Organizer 2 will have a dark theme already selected for you. If it does not, something has gone wrong and you will need to start over at the [Installing the List](#installing-the-list) section of this document.
3. A dialogue may appear and ask if you want to associate Mod Organizer with .nxm links. Click Yes. If this dialogue does not appear, it is not an issue and means you've likely already done this.

#### Configuration-Specific


### ENB
ENB is not required to run Living Skyrim, however, it is intended to be used with it and highly recommended. Weaker computers should opt to skip ENB or use Reshade. Support is not provided for Reshade.

The following ENB presets are known to look great when playing Living Skyrim: Amon ENB Reborn, Silent Horizons, Rudy's, and Re-Engaged. However, you can and should experiment to find the best ENB for you both in terms of looks and performance. Not all ENB presets are created equal, and deciding which one to use is a highly subjective process.

If you wish to use ENB, follow these steps:

1. Download the latest ENB Binary from http://enbdev.com/download_mod_tesskyrimse.htm
2. Open the .zip file, go into the WrapperVersion folder, and copy ONLY d3d11.dll and d3dcompiler_46e.dll into your Skyrim SE installation folder. (Usually located at`[install drive]\Steam\steamapps\common\Skyrim Special Edition`)
3. Download your selected ENB preset. **Important!: Make sure it is compatible with Obsidian Weathers!**
4. Follow any installation instructions included with your Preset. Every ENB has slight variations in their requirements, so make sure to follow the instructions included for that preset. **You should not need to download any additional files other than the preset. Things like ENB Helper and Particle Patch are already included!**
5. Ensure that ForceVsync is set to false in enblocal.ini

## Updating Living Skyrim
If you are updating Living Skyrim, the process is very similar to installing the list. Before you update, you should at a minimum backup your save files. Updating may delete any saves that are present. Additionally, make sure you are using the latest version of Wabbajack (it should automatically update itself when you launch the program).

1. Run Wabbajack.exe. The program should automatically update itself to the latest version.
2. At the bottom of the window, click Browse Modlists.
3. Locate the Living Skyrim card. You can filter the gallery by game using the dropdown menu at the top of the gallery. Living Skyrim is listed under Skyrim Special Edition.
4. On the Living Skyrim card, click the download/down arrow icon.
5. Once it finishes downloading, click the play/right arrow icon on the Living Skyrim card.
6. Below the image you see of the Living Skyrim logo, there are three text boxes. The second and third need to be filled out.
7. Click the three dots in the second (middle) box. Navigate to your Living Skyrim folder and then select this folder in the window that appears. This middle box tells you where the list will be installed, including the copy of Mod Organizer 2 that you'll need to use to launch the list.
8. The third (bottom) box will automatically populate using the folder you just selected. This third box tells you where all of the mods will be downloaded. If you have hard drive limitations, you may change this to another folder on another hard drive by clicking the three dots in this box and selecting a new folder.
9. Click the play/right arrow button to begin the installation.
10. If you are prompted to overwrite, confirm that this is what you want to do by clicking the Confirm button.

## Launching Living Skyrim
To actually launch and then play Living Skyrim, follow these steps:

1. Launch the copy of Mod Organizer 2 found inside your Living Skyrim folder.
2. In the top-right corner of Mod Organizer, you'll see a large dropdown menu. Select SKSE [AKA LIVING SKYRIM] from this dropdown menu.
3. This is how Living Skyrim should always be launched. You can create a shortcut to this selection on your desktop, if you wish, using the Shortcut button directly below the large Run button.
4. Once Skyrim starts, create a new game. **Loading a save from another modlist or from before you installed Living Skyrim will corrupt that save, do not do this.**
5. Create your character and name them whatever you'd like.
6. **As soon as you gain control of your character, do nothing.** The mods are initializing and this can take several minutes. You'll see a list of mods appearing in the top left corner of your screen.
7. Once you see that no more items are appearing in the list in the top left, you can proceed to the next steps.

### The MCM Settings


### Getting Started in Living Skyrim


## Important Mods You Need to Know About

### Character Customization Mods
When creating your character, you'll find there are a lot of options that are available to you. From hairs to tattoos to eyes and more, Living Skyrim has included a comprehensive suite of mods that allow you to tweak your character's appearance to exactly what you want. And, if you're struggling to figure out where to begin with character creation, a number of presets made by the Living Skyrim community have been included for you to pick from. In general, you'll have more options for *everything*.

There is one particular mod you need to be aware of during character creation: [High Poly Head](https://vectorplexus.com/files/file/283-high-poly-head/). To have your character use High Poly Head, you'll need to change the head part using the RaceMenu slider of the same name to option 3. Note that if you do use High Poly Head, you may need to do some manual sculpting using the RaceMenu sculpt feature to remove any clipping issues with eyebrows or beards. 

### The Economy and Loot Mods
There are two sides to the Skyrim economy: Loot, and trade. Loot is your primary source of income, and trade your primary source of expenditure. To address this, Living Skyrim seeks to overhaul both sides of this coin.

On the loot side, you'll find that chests and enemies are fairly abundant loot thanks to [GOLD](https://www.nexusmods.com/skyrimspecialedition/mods/1796), [Dynamic Dungeon Loot](https://www.nexusmods.com/skyrimspecialedition/mods/10308), and [Lock Related Loot](https://www.nexusmods.com/skyrimspecialedition/mods/10308). In general, chests have been overhauled such that no two chests are ever the same and contain a fantastic assortment of things you can find. You may also find powerful items significantly earlier than normal due to Dynamic Dungeon Loot. Normally this would be cause for concern, but you will also find that the amount of just randomly placed objects in the world has been significantly decreased by [Iris](https://www.nexusmods.com/skyrimspecialedition/mods/41920). The removal of most of the items placed in the world shifts the focus of loot from picking up everything in a dungeon to seeking out and opening every chest you can find. Also, for good measure, you'll find a small quality of life improvement in [Lootable Woodpiles](https://www.nexusmods.com/skyrimspecialedition/mods/12238). 

Opposite the loot side, we have the economy side of things. Naturally, because of the increased amount of loot you'll find, the price of many items has been increased drastically. No longer will a set of steel armor cost just a couple hundred gold - instead, you'll find it costs well over 1000 gold, and higher level armors only get even more expensive. The same is true of just about everything you can purchase from a vendor. This is due to the combination of [Trade & Barter](https://www.nexusmods.com/skyrimspecialedition/mods/23081) and [Eve](https://www.nexusmods.com/skyrimspecialedition/mods/26325). Items will sell for less and cost more to buy across the board. This is necessary to make looting feel significant while also keeping some semblance of balance. In general it will be more difficult to obtain obscene amounts of gold, but it is still possible - that's just how Skyrim works without going completely overboard modifying the loot/economy. Also, for the more kleptomania-inclined among you, you'll find some helping hands in [Khajiits Steal Too](https://www.nexusmods.com/skyrimspecialedition/mods/18231).

## Bug Reporting, Github, and You


## Common Issues
### Wabbajack Issues
#### "A mod failed to download."
The short answer: wait for an update to the list. The long answer is you can try to install the missing mods manually if the files are still available on the Nexus, but again, do not ask for anyone to share old files. I work a full-time job in addition to several other personal projects, of which Living Skyrim is just one. If installs are failing, I will try to update as quickly as possible but sometimes it may be a couple of days before I can get to it.

#### "Wabbajack says I'm out of requests."
Nexus Premium is limited to 2500 downloads in a given 24 hour timeframe. Usually this limit resets around 8PM Eastern Time. Wait for your limit to reset and you'll be able to proceed. Usually this only occurs after attempting to download the list multiple times in a row or when attempting to download multiple lists.

#### "Can I pause the installation?"
Yes, just close Wabbajack. When you start the installation process again it will pick up from where it left off.

#### "Can I delete the downloads folder after installing?"
Yes, but remember that if you need to update the list you will have to download all of the mods that have updated again.

#### "The LS2 DynDOLOD Output fails to download."
You'll need to download this manually and put it in your downloads folder. The mirror for this file can be found here: [LS2 DynDOLOD 2.4.0](https://drive.google.com/file/d/1tSWvQiXIHqgngYmoW5eUHQFerUsOP7Wo/view?usp=sharing)

### Gameplay Issues
#### "The Main Quest doesn't proceed after retrieving the Dragonstone."
Read this modpage: [Not So Fast - Main Quest](https://www.nexusmods.com/skyrimspecialedition/mods/2475)

#### "Tolfdir doesn't invite me to Saarthal right away."
Read this modpage: [Not So Fast - Mage Guild](https://www.nexusmods.com/skyrimspecialedition/mods/5686)

#### "Can I access RaceMenu after character creation?"
Only if you are **not** changing your character's gender or race. Changing gender/race will cause issues with powers and passive buffs your character has.

#### "Can I change my attributes after starting?"
No. The choices you make are permanent. You can increase your attributes through various methods, refer to this modpage for more details: [AVA](https://www.nexusmods.com/skyrimspecialedition/mods/23329)

#### "My screen is zoomed in or weirdly off-center."
Check the SSE Display Tweaks INI file to make sure you have the resolution for your screen set correctly. You may also need to check BethINI or the Skyrim INI files to make sure they all match your screen's resolution.

#### "MO2 cannot find SKSE."
You'll need to manually set the path for SKSE using the Edit Executables menu in MO2. Also make sure you have followed the [Game Folder Files](#game-folder-files) step of this readme.

#### "Can I use a controller?"
I strongly advise against it. With as many mods as there are in the list, you'll need a full breadth of keyboard keys to activate and use every feature. If you absolutely must play with a controller, please, for the love of all that is holy, use [Gamepad++](https://www.nexusmods.com/skyrimspecialedition/mods/27007).

#### "My game freezes when saving."
Make sure you’ve disabled all overlays for Skyrim. The most common ones are Discord, Steam, and nVidia. Other overlays from things like MSI Afterburner and f.lux have also been known to cause issues.

#### "Can I play this list on a 75/100/144hz screen?"
Technically yes, but also no. Movement Behavior Overhaul requires that the FPS of the game be capped at 60FPS. Display Tweaks SSE is included to allow higher refresh rates, but exceeding 60FPS is a recipe for disaster.

#### "My equipment animations are broken/weird!"
First, check to make sure you’ve followed the MCM instructions for XPMSE. This should fix any weirdness (sword on hip but being drawn from back, for example.). If you’ve just equipped a new weapon/shield, the animation to draw it may be weird for a few seconds but it will eventually fix itself. XPMSE and AllGUD need a few seconds to register the new weapon configuration and should fix themselves. This is not a bug, just be patient and the mods will figure it out eventually.

#### "Can I use this list on an ultrawide monitor?"
Yes, [Complete Widescreen Fix](https://www.nexusmods.com/skyrimspecialedition/mods/1778) is included by default. Just make sure to enable it

#### "Immersive Spell Learning still allows me to read the spell tome to learn spells instantly."
Yes, this is a known issue and is somewhat intended. Legacy of the Dragonborn's museum counts spell tomes towards its display count, so rather than have players find/buy two copies of a spell tome (one to learn from and the other to store in the museum), I've opted to allow spell tomes to stay in your inventory. If you don't like having the temptation of "cheating" and don't mind having to hunt down a second copy of the book, you can always enable "Destroy Spell Tomes" in the Immersive Spell Learning MCM.

#### "What the heck is going on with the dialogue menu?"
It's being modified by [EZ2C Dialogue Menu](https://www.nexusmods.com/skyrimspecialedition/mods/2246/). Check that mod's page for details of how to configure it if it's not to your liking.

### NeverNude?


### Adding to Living Skyrim
Many Skyrim modders ask the question: "Can I add mods to Living Skyrim?" (Or, "Can I remove mods from Living Skyrim?", or, "Can I change the mods included with Living Skyrim?")

If you are asking this question from a perspective of just installing the mod and expecting it to work, then the answer is a resounding, unequivocal **NO.**

The longer and slightly more technical answer is: "I don't know, can you?"

To expand on this: nobody knows whether you can add a certain mod or not. Adding to, changing, or removing from the list isn't a yes/no question. In 99.9% of cases, the answer is, "Yes, **but..."**

The "but..." part of that answer refers to the process of installing any mod and stems from a deeply rooted belief that mods are either compatible with each other, or they are not. Assuming that any mod is (or is not) compatible with any other mod is absurd. Every mod can be made to work with every other mod, the real questions you *should* be asking are: "How much work would it take to add this mod?" and "Do I have the knowledge, tools, and skills to add this mod?"

And unfortunately, the answer to *those* questions is a resounding, unequivocal, "It depends." And it depends on the answers to these questions, which you, and only you, can answer: Does it require compatibility/consistency patching in xEdit? Does it require modifications in Creation Kit? Does it require that it be loaded in a certain place in the load order? Does it need additional mods (which also require answers to these questions) to function?

Lastly, I (ForgottenGlory) and the Living Skyrim development team do not support this in any way, shape, or form. If you're going to add a mod to Living Skyrim, you need to be prepared to do it on your own. I understand this isn't an ideal answer for people relatively new to modding, but you need to understand that hundreds of hours have been spent putting together Living Skyrim, making it as stable as possible with all the mods working in harmony. Adding a bunch of random mods on top of it and then expecting it to "just work" is naive at best.

"Can I add a mod to Living Skyrim?"

I don't know, can you?

### Performance Optimizations

## Other Common Questions


## Credits & Thanks
- Living Skyrim created by ForgottenGlory
- Living Skyrim 2 Dev Team:
  - Volk
  - MadQueen (Formerly Melisandre)
  - JaceVenture
  - Magnus Hellfire
  - Bearnard
  - Volkaru
  - JaxomOfRuatha
  - TwistedModding
- Contributors & Beta Testers:
  - Patchier
  - DwarfDude
  - Qwerrecd
  - Timboman
  - NexxusDrako
  - Total
  - Dispo
  - Dracosaber
  - Sentrus
  - Nechrion
  - Xanza
  - tjbassoon
- Halgari & The Wabbajack Team
  - Thank you for creating Wabbajack, you’re amazing!
  - [Halgari’s Patreon](https://www.patreon.com/user?u=11907933)
- Special Thanks
  - The TUCO Modding Team - Their modlist is a great way to get a Vanilla+ experience with a tutorial that is extremely helpful for learning the basics of creating a modlist.
  - DarkLadyLexy - Her LotD list is an invaluable resource not only for an awesome modlist, but also for learning many fundamentals of modding and compiling a modlist.
  - EzioTheDeadPoet - For their SME(FT) modlist. The ability to start from scratch on a whim while building this list has been invaluable.
- Mod Authors
  - None of this would be possible without the people who make the quality content we’ve grown to know and love. Please endorse the authors’ works.

### One Last Thing
If you read through the entire readme, congratulations! You get a cookie. If you need any further help, feel free to reach out on the Wabbajack or Living Skyrim Discord Servers. **Do not direct message ForgottenGlory, any of the Living Skyrim dev team, or any Wabbajack staff members for support. I (ForgottenGlory) speak for myself, but I do reserve the right to ignore any requests for support direct messaged to me and block you.**
