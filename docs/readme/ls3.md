---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: LS_readme
permalink: /readme/ls3/
---

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .protip{background-color:#353535;border-style:dashed;border-color:#93bd20;color:#f0e7d5;text-align:center;vertical-align:top}
.tg .important{background-color:#353535;border-style:dashed;border-color:#ffcb31;color:#ffcb31;text-align:center;vertical-align:top}
.tg .warning{background-color:#353535;border-style:dashed;border-color:#c6271b;color:#c6271b;text-align:center;vertical-align:top}
</style>

![](https://i.imgur.com/Vokoo6f.png)

## This readme is a work in progress
Links will be broken, entire sections are incomplete, and phrasing/ordering of the Readme still needs to be revised.

Current version: 3.0.0 Dev Build 1 (Pre-Alpha)

![total-installs](https://img.shields.io/endpoint?label=Total%20Installs&style=for-the-badge&url=https://build.wabbajack.org/metrics/badge/living_skyrim/total_installs_badge.json)  
![build-status](https://img.shields.io/endpoint?label=List%20Status&style=for-the-badge&url=https://build.wabbajack.org/lists/status/living_skyrim/badge.json)

## Table of Contents
<table>
<thead>
  <tr>
    <th>
      <ul style="list-style-type:none;">
        <li><a href="https://forgottenglory.github.io/readme/ls3/#preface">Preface</a></li>
        <li><a href="https://forgottenglory.github.io/readme/ls3/#before-you-get-started">Before You Get Started</a></li>
          <ul style="list-style-type:none;">
            <li><a href="https://forgottenglory.github.io/readme/ls3/#system-specifications">System Specifications</a></li>
            <li><a href="https://forgottenglory.github.io/readme/ls3/#important-links">Important Links</a></li>
            <li><a href="https://forgottenglory.github.io/readme/ls3/#screenshots">Screenshots</a></li>
            <li><a href="https://forgottenglory.github.io/readme/ls3/#videos">Videos</a></li>
          </ul>
        <li><a href="https://forgottenglory.github.io/readme/ls3/#pre-installation">Pre-Installation</a></li>
          <ul style="list-style-type:none;">
            <li><a href="https://forgottenglory.github.io/readme/ls3/#steam--skyrim-special-edition-setup">Steam &amp; SSE Setup</a></li>
            <li><a href="https://forgottenglory.github.io/readme/ls3/#wabbajack-preparations">Wabbajack Preparations</a></li>
          </ul>
        <li><a href="https://forgottenglory.github.io/readme/ls3/#installing-the-list">Installing the List</a></li>
          <ul style="list-style-type:none;">
            <li><a href="https://forgottenglory.github.io/readme/ls3/#game-folder-files">Game Folder Files</a></li>
            <li><a href="https://forgottenglory.github.io/readme/ls3/#post-wabbajack-install">Post-Wabbajack Install</a></li>
            <li><a href="https://forgottenglory.github.io/readme/ls3/#mod-organizer-2">Mod Organizer 2</a></li>
            <li><a href="https://forgottenglory.github.io/readme/ls3/#configuration-specific">Configuration-Specific Setup</a></li>
            <li><a href="https://forgottenglory.github.io/readme/ls3/#enb">ENB</a></li>
          </ul>
          <li><a href="https://forgottenglory.github.io/readme/ls3/#updating-living-skyrim">Updating Living Skyrim</a></li>
          <li><a href="https://forgottenglory.github.io/readme/ls3/#launching-living-skyrim">Launching Living Skyrim</a></li>
          <li><a href="https://forgottenglory.github.io/readme/ls3/#the-mcm-settings">The MCM Settings</a></li>
          <li><a href="https://forgottenglory.github.io/readme/ls3/#getting-started-in-living-skyrim">Getting Started in Living Skyrim</a></li>
      </ul>
    </th>
    <th>
      <ul style="list-style-type:none;">
        <li><a href="https://forgottenglory.github.io/readme/ls3/#important-mods-you-need-to-know-about">Important Mods You Need to Know About</a></li>
          <ul style="list-style-type:none;">
            <li><a href="https://forgottenglory.github.io/readme/ls3/#the-population-mods">The Population Mods</a></li>
            <li><a href="https://forgottenglory.github.io/readme/ls3/#the-quest-mods">The Quest Mods</a></li>
            <li><a href="https://forgottenglory.github.io/readme/ls3/#the-magic-mods">The Magic Mods</a></li>
            <li><a href="https://forgottenglory.github.io/readme/ls3/#the-combat-mods">The Combat Mods</a></li>
            <li><a href="https://forgottenglory.github.io/readme/ls3/#the-perks--leveling-mods">The Perks & Leveling Mods</a></li>
            <li><a href="https://forgottenglory.github.io/readme/ls3/#the-economy-and-loot-mods">The Economy and Loot Mods</a></li>
            <li><a href="https://forgottenglory.github.io/readme/ls3/#the-hud-mods">The HUD Mods</a></li>
            <li><a href="https://forgottenglory.github.io/readme/ls3/#character-customization-mods">Character Customization Mods</a></li>
            <li><a href="https://forgottenglory.github.io/readme/ls3/#player-homes">Player Homes</a></li>
            <li><a href="https://forgottenglory.github.io/readme/ls3/#nethers-follower-framework">Nether's Follower Framework</a></li>
          </ul>
        <li><a href="https://forgottenglory.github.io/readme/ls3/#bug-reporting-github-and-you">Bug Reporting, Github, and You</a></li><br>
        <li><a href="https://forgottenglory.github.io/readme/ls3/#common-issues">Common Issues</a></li>
          <ul style="list-style-type:none;">
            <li><a href="https://forgottenglory.github.io/readme/ls3/#wabbajack-issues">Wabbajack Issues</a></li>
            <li><a href="https://forgottenglory.github.io/readme/ls3/#gameplay-issues">Gameplay Issues</a></li>
          </ul>
        <li><a href="https://forgottenglory.github.io/readme/ls3/#adding-to-living-skyrim">Adding to Living Skyrim</a></li>
        <li><a href="https://forgottenglory.github.io/readme/ls3/#performance-optimizations">Performance Optimizations</a></li>
        <li><a href="https://forgottenglory.github.io/readme/ls3/#other-common-questions">Other Common Questions</a></li>
        <li><a href="https://forgottenglory.github.io/readme/ls3/#credits--thanks">Credits &amp; Thanks</a></li>
      </ul>
    </th>
  </tr>
</thead>
</table>

## Preface

## Before You Get Started
Before you get started installing or playing Living Skyrim, it's important to note a few things:

<table class="tg">
<thead>
  <tr>
    <th class="important"><b>Important!:</b> Blocks labeled important like this one will tell you when you need to pay extra attention to something.</th>
  </tr>
</thead>
</table>

<table class="tg">
<thead>
  <tr>
    <th class="warning"><b>WARNING:</b> Warning blocks like this will warn you when you absolutely must not forget to do something. Failure to heed to warning blocks is cause for disaster.</th>
  </tr>
</thead>
</table>

* You are not required to have Nexus Premium to install Living Skyrim, however, it is **highly recommended.** Nexus Premium will cut your install time to a fraction of what it would be by automating both the mod download and mod install processes of installing the list.
* As of version 3.0.0, Living Skyrim requires 208GB of hard drive space on top of the ~11GB Skyrim: Special Edition base files. Installing to an SSD/NVMe is not required, but also **highly recommended.** Download and installation times vary based on your computer and internet speeds, but expect the entire process to take a few hours. If you are installing the list without Nexus Premium, expect the process to take a couple of days of 8+ hour sessions downloading mods.
* To maximize performance, both Skyrim: Special Edition and Living Skyrim should be installed on the same hard drive, ideally an SSD/NVMe. This is not required, just recommended if you want the smoothest gameplay experience.
* If you are not familiar with the contents of this modlist, a complete documentation of every mod in the list including links to the mods is available on the [LS3 Modlist Spreadsheet]().
* If you instead only wish for a brief overview of the major changes this modlist makes, you should refer to the [Important Mods You Need to Know About](#important-mods-you-need-to-know-about) section of this document.
* Autosaves for this modlist are disabled. This save option is known to cause issues with modlists running a large number of scripted mods. Instead, quicksaves are automatically turned into manual saves by SSE Engine Fixes. It is recommended to save early and often. Every 15 minutes and before interacting with quest NPCs, quest objects, and before entering new zones should be sufficient.
* Continuing the last point, it is always better to save **before** entering a loading screen instead of after. After a loading screen it is very likely that scripts will be running for at least 30 seconds, so if you must save after a loading screen, at least wait that long before doing so.
* Wabbajack does support updating an existing installation of a modlist. However, as part of this process, it does delete files that don't match with what it is installing. This includes RaceMenu presets, mods you've added/changed, and possibly even save files. It is a good practice to keep backups of your save files so that you can update safely. Saves are stored within the folder you install Living Skyrim to.
* Living Skyrim 3 has been updated such that NPCs and player characters are never nude. Underwear is worn by all NPCs and the player character and cannot be unequipped.
* Adding to, changing, or removing from Living Skyrim is not supported. See the [Adding to Living Skyrim](#adding-to-living-skyrim) section of this document for more details.
* As many common issues as I could find have been documented in the [Common Issues](#common-issues) section of this document. Refer to this before asking for support.
* If you want some tips related to getting started playing the list, refer to the [Getting Started in Living Skyrim](#getting-started-in-living-skyrim) section of this document.
* By default, Living Skyrim has the game running in exclusive fullscreen mode to assist with game performance.

### System Specifications
Living Skyrim v3.0.0 has been cut back severely from the performance hog it was in v2.0.0 and on. Textures range from 512x512 to 4K and everything in between. The following system is ForgottenGlory's personal computer and is able to run the list at a constant 60FPS including ENB at 1440p monitor resolution.

- CPU: AMD Ryzen 9 3900X @ 4.2GHz  
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
[One](https://cdn.discordapp.com/attachments/771075313849466922/802781636781277204/SkyrimSE_2021-01-24_00-01-33_original.png) [Two](https://cdn.discordapp.com/attachments/771075313849466922/799368412492857354/ScreenShot153.png) [Three](https://cdn.discordapp.com/attachments/771075313849466922/793938031644114964/enb2020_12_30_14_59_11.png) [Four](https://cdn.discordapp.com/attachments/771075313849466922/783880191482134548/SkyrimSE_2020-12-02_20-15-19.png) [Five](https://cdn.discordapp.com/attachments/771075313849466922/783113018833240064/enb2020_11_30_13_24_55.png) [Six](https://cdn.discordapp.com/attachments/771075313849466922/778085567660556298/ScreenShot88.png) [Seven](https://cdn.discordapp.com/attachments/771075313849466922/778085516318605382/ScreenShot91.png) [Eight](https://cdn.discordapp.com/attachments/771075313849466922/778085553336877106/ScreenShot96.png) [Nine](https://cdn.discordapp.com/attachments/771075313849466922/778085573864849428/ScreenShot90.png) [Ten](https://cdn.discordapp.com/attachments/771075313849466922/799368537885769728/ScreenShot160.png) [Eleven](https://cdn.discordapp.com/attachments/771075313849466922/802026560433291264/SkyrimSE_2021-01-21_22-54-34_ReShadePreset.png) [Twelve](https://cdn.discordapp.com/attachments/771075313849466922/802026617282494518/SkyrimSE_2021-01-21_22-57-54_ReShadePreset.png) [Thirteen](https://cdn.discordapp.com/attachments/771075313849466922/799368405664792636/ScreenShot156.png) [Fourteen](https://cdn.discordapp.com/attachments/771075313849466922/799368411573387334/ScreenShot157.png) [Fifteen](https://cdn.discordapp.com/attachments/771075313849466922/799368430926692372/ScreenShot163.png) [Sixteen](https://cdn.discordapp.com/attachments/771075313849466922/799368554654072832/ScreenShot162.png) [Seventeen](https://cdn.discordapp.com/attachments/771075313849466922/778085570719121438/ScreenShot89.png) [Eighteen](https://cdn.discordapp.com/attachments/771075313849466922/778085571368976384/ScreenShot87.png) [Nineteen](https://cdn.discordapp.com/attachments/771075313849466922/778085561051119626/ScreenShot82.png) [Twenty](https://cdn.discordapp.com/attachments/771075313849466922/778085548748177448/ScreenShot95.png)

#### Videos


## Pre-Installation
### Steam & Skyrim Special Edition Setup
Before proceeding with installation, it's important that your Steam and Skyrim Special Edition install are configured correctly.

First, make sure that your Steam library, and therefore the Skyrim Special Edition install folder, is not located within your Program Files or Program Files (x86) folders. Having the Steam library or your copy of Skyrim Special Edition in either of these folders is known to cause issues. Instructions on how to move your Steam library can be found elsewhere on the internet.

Next, you'll need a clean copy of Skyrim Special Edition. To get your copy to this state, follow these steps:

1. In Steam, uninstall Skyrim: Special Edition (Right-click > Manage > Uninstall). 
2. If there are any files leftover in the Skyrim Special Edition game folder (Right-click > Properties… > Local Files > Browse Local Files…), delete them.
3. Install Skyrim: Special Edition.

<table class="tg">
<thead>
  <tr>
    <th class="protip"><b>Protip:</b> If you want to be absolutely certain you have uninstalled Skyrim completely, download and use <a href="https://www.nexusmods.com/skyrimspecialedition/mods/30133">Skyrim Shredder</a>.</th>
  </tr>
</thead>
</table>

Afterwards, you need to disable automatic updates for Skyrim to avoid a game update breaking your copy of the game and therefore the modlist.

1. In Steam, set Skyrim: Special Edition to update only when opened. (Right-click > Properties… > Updates > Automatic updates > Only update this game when I launch it)
2. In Steam, disable the Steam Overlay. (Right-click > Properties... > General > Enable the Steam Overlay while in-game checkbox)
   
Finally, once the above steps are completed, launch Skyrim SE through Steam to create any INI or registry entries the game needs. Immediately exit the launcher once it has successfully selected a graphics preset for your hardware. The INIs it just created will be overwritten by the ones included in the modlist, but this is a necessary step for Wabbajack to recognize that you have the game installed.

### Wabbajack Preparations
A video version of the installation instructions from this point forward exists here: [Click Me!](https://youtu.be/sW7s5IhN7qs)  

We'll now setup the folders needed for the installation to proceed smoothly.

1. Create two empty folders: one named Wabbajack and the other named Living Skyrim.
2. Ensure that these two folders are not within any of the following folders: your Skyrim Special Edition install folder, your Program Files folder, or your Program Files (x86) folder. 
3. Additionally, ensure that these two folders are not contained within each other. 
4. Ensure that both the Wabbajack and Living Skyrim folders are completely empty. If they are not empty, make them empty.
5. Download the latest version of Wabbajack from the Wabbajack website: [Wabbajack](https://www.wabbajack.org/#/).
6. Place the Wabbajack.exe file you just downloaded into the folder you created earlier called Wabbajack.

<table class="tg">
<thead>
  <tr>
    <th class="warning"><b>WARNING:</b> Failure to set up these folders properly will result in the install failing. For example, [install drive]\Wabbajack\Living Skyrim is <b>incorrect</b>.</th>
  </tr>
</thead>
</table>

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
11. Wabbajack will now download and install all of the mods. This will take a while (3-4 hours at most). Take this opportunity to read the [Important Mods You Need To Know About](#important-mods-you-need-to-know-about) section of this document. 

### Without Nexus Premium
10. Wabbajack will prompt you to click all the needed buttons to download the modlist. Be prepared for this to take an extraordinarily long time. Current reports indicate installing the list manually takes approximately 24 hours. Also be aware that due to the amount of time required when installing this list manually, the list may update during the time it takes to install and you may need to start over if that happens. Installing with Nexus Premium isn't required, but is strongly recommended if you value your time. If you must install the list manually, put on an audiobook or a TV show and make a day of it.

<table class="tg">
<thead>
  <tr>
    <th class="important"><b>Important!:</b> Reading the Important Mods section of this document is not optional. You won't have any idea what's going on if you don't.</th>
  </tr>
</thead>
</table>

Once complete, Wabbajack will indicate it is done with a green box that says "Installation complete". You may exit Wabbajack after this appears.

If it does not complete successfully (a red box with "Installation failed"), consult the [Common Issues](#common-issues) section of this document, or visit the [Living Skyrim Discord server](https://discord.gg/9dFvGnc) for assistance. 

### Game Folder Files
Now, you must copy some files to your installation folder of Skyrim Special Edition. This is required for the list to function properly. 

1. Navigate to your Living Skyrim folder and locate the "Game Folder Files" folder.
2. Copy everything inside the "Game Folder Files" folder into your Skyrim Special Edition install folder.
3. Overwrite existing files if you are prompted to do so.

<table class="tg">
<thead>
  <tr>
    <th class="warning"><b>WARNING:</b> These files include SKSE and Engine Fixes Part 2, both of which are essential for the list to function correctly. Failure to copy these files will result in the list not working.</th>
  </tr>
</thead>
</table>

## Post-Wabbajack Install
### Mod Organizer 2
Among other things, Wabbajack has installed a copy of Mod Organizer 2 for you. This copy of Mod Organizer 2 is specific to Living Skyrim and will not affect any other modlists you have installed.

1. Inside your Living Skyrim folder, locate and launch ModOrganizer.exe. If this is not inside the folder, your installation has failed and you need to consult the [Common Issues](#common-issues) section of this document.
2. Mod Organizer 2 will have a dark theme already selected for you. If it does not, something has gone wrong and you will need to start over at the [Installing the List](#installing-the-list) section of this document.
3. A dialogue may appear and ask if you want to associate Mod Organizer with .nxm links. Click Yes. If this dialogue does not appear, it is not an issue and means you've likely already done this.

### Configuration-Specific
There are two mods that can be optionally enabled, depending on your preferences and computer configuration. 

The first is [Complete Widescreen Fix](https://www.nexusmods.com/skyrimspecialedition/mods/1778?tab=description). This should only be enabled if you are using a 21:9 monitor at 2560x1080 resolution or higher.

The second is QuickLoot, which adds a Fallout 4 style loot menu to bodies, containers, etc. This mod provides a significant quality of life improvement to looting, however it can cause issues with mods that run scripts upon looting certain objects. Enable it, or don't, it's entirely up to your personal preference.

### ENB
ENB is not required to run Living Skyrim, however, it is intended to be used with it and highly recommended. Weaker computers should opt to skip ENB or use Reshade. Support is not provided for Reshade.

The following ENB presets are known to look great when playing Living Skyrim: Amon ENB Reborn, Silent Horizons, Rudy's, and Re-Engaged. However, you can and should experiment to find the best ENB for you both in terms of looks and performance. Not all ENB presets are created equal, and deciding which one to use is a highly subjective process.

If you wish to use ENB, follow these steps:

* Download the latest ENB Binary from http://enbdev.com/download_mod_tesskyrimse.htm
* Open the .zip file, go into the WrapperVersion folder, and copy ONLY d3d11.dll and d3dcompiler_46e.dll into your Skyrim SE installation folder. (Usually located at`[install drive]\Steam\steamapps\common\Skyrim Special Edition`)

<table class="tg">
<thead>
  <tr>
    <th class="important"><b>Important!:</b> Make sure your chosen ENB preset is compatible with Obsidian Weathers!</th>
  </tr>
</thead>
</table>

* Download your selected ENB preset.
* Follow any installation instructions included with your Preset. Every ENB has slight variations in their requirements, so make sure to follow the instructions included for that preset. 

<table class="tg">
<thead>
  <tr>
    <th class="important"><b>Important!:</b> You should not need to download any additional files other than the preset. Things like ENB Helper and Particle Patch are already included!</th>
  </tr>
</thead>
</table>

* Ensure that ForceVsync is set to false in enblocal.ini

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
2. In the top-right corner of Mod Organizer, you'll see a large dropdown menu. Select Living Skyrim [SKSE] from this dropdown menu.
3. Click the large Run button.
4. This is how Living Skyrim should always be launched. You can create a shortcut to this selection on your desktop, if you wish, using the Shortcut button directly below the large Run button.
5. Once Skyrim starts, create a new game.
6. Create your character and name them whatever you'd like.
7. **As soon as you gain control of your character, do nothing.** The mods are initializing and this can take several minutes. You'll see a list of mods appearing in the top left corner of your screen.
8. Once you see that no more items are appearing in the list in the top left, you can proceed to the next steps.

<table class="tg">
<thead>
  <tr>
    <th class="warning"><b>WARNING:</b> Loading a save from another modlist or from before you installed Living Skyrim will corrupt that save, do not do this.</th>
  </tr>
</thead>
</table>

### The MCM Settings
The MCM settings for Living Skyrim 3 have all been set for you. You are still encouraged to look through them and tweak them to your liking, but changing MCM settings is not required. You can start the game and begin playing once all mods have initialized.

### Getting Started in Living Skyrim

## Important Mods You Need to Know About

### The Population Mods
Living Skyrim includes a number of mods that increase the population of both creatures and characters in the world. The first and most important one is [Populated Skyrim Hell Edition](https://www.nexusmods.com/skyrimspecialedition/mods/23871) This mod features a grand number of new NPCs in every location you visit. It has an option for 50% less NPCs which is turned on by default, you can disable this option in the mod's MCM if your PC can handle it or you want an extra challenge.

Next is [OBIS](https://www.nexusmods.com/skyrimspecialedition/mods/4145), which adds a ton of mid to high-level bandits to the world. In general this covers most of the overworld locations.

[Organic Factions](https://www.nexusmods.com/skyrimspecialedition/mods/10289) adds groups of NPCs that dynamically expand, recruit, and find new leaders. They will spread to conquer new territory and if left unchecked can take over entire holds. Keep an eye on the notifications for this mod, as it will keep you up to date on who is in control of what regions. You can also stumble across battles between factions if their territories overlap.

Also for your consideration: [Immersive Patrols](https://www.nexusmods.com/skyrimspecialedition/mods/718), and [Interesting NPCs](https://www.nexusmods.com/skyrimspecialedition/mods/29194). For creatures, you'll find [SkyTEST](https://www.nexusmods.com/skyrimspecialedition/mods/1104) and [Animallica](https://www.nexusmods.com/skyrimspecialedition/mods/20456).

What does this mean? Well, to put it simply, there are *a lot* of NPCs to find and interact with now. Silent Moons Camp for example now has somewhere in the range of 30 enemies to fight. It is impossible to go more than 5 minutes without coming across an NPC of some kind be it bandits, a patrol, or an animal. Getting a follower or two (or four) is highly encouraged. You will have to revisit some dungeons once you are stronger or have more followers. The [Take Notes](https://www.nexusmods.com/skyrimspecialedition/mods/13570) mod is included to chronicle your adventure and also to help you remember what places you need to revisit.

### The Quest Mods
Very few quests are untouched by Living Skyrim. Whether it's a location revamp like [Bleak Falls Barrow Revisited](https://www.nexusmods.com/skyrimspecialedition/mods/33251), or a quest rewrite like [Finding Helgi and Laelette](https://www.nexusmods.com/skyrimspecialedition/mods/28973), it's unlikely you'll play most quests the same as you would in vanilla. This isn't even to mention all of the new quests added by Living Skyrim. See below for a complete list of quest-related changes and the new quests added by this list.

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:none;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:bottom;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-c3ow{border-color:inherit;text-align:center;vertical-align:top}
.tg .tg-0pky{border-color:inherit;text-align:left;vertical-align:top}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-c3ow"><b>Quest Changes</b></th>
    <th class="tg-c3ow"><b>New Quests</b></th>
    <th class="tg-c3ow"><b>New Lands</b></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-0pky">
      <ul style="list-style-type:none;">
        <li><a href="https://www.nexusmods.com/skyrimspecialedition/mods/25464">Timing is Everything</a></li>
        <li><a href="https://www.nexusmods.com/skyrimspecialedition/mods/2475">Not So Fast - Main Quest</a></li>
        <li><a href="https://www.nexusmods.com/skyrimspecialedition/mods/5686">Not So Fast - Mage Guild</a></li>
        <li><a href="https://www.nexusmods.com/skyrimspecialedition/mods/931">Opulent Thieves Guild</a></li>
        <li><a href="https://www.nexusmods.com/skyrimspecialedition/mods/19490">The Companions - Don't be a Milk Drinker</a></li>
        <li><a href="https://www.nexusmods.com/skyrimspecialedition/mods/28973">Finding Helgi and Laelette</a></li>
        <li><a href="https://www.nexusmods.com/skyrimspecialedition/mods/32512">Finding Susanna Alive</a></li>
        <li><a href="https://www.nexusmods.com/skyrimspecialedition/mods/336">Namira for Good Guys</a></li>
        <li><a href="https://www.nexusmods.com/skyrimspecialedition/mods/23047">House of Horrors Divine Intervention</a></li>
        <li><a href="https://www.nexusmods.com/skyrimspecialedition/mods/159">Even Better Quest Objectives</a></li>
        <li><a href="https://www.nexusmods.com/skyrimspecialedition/mods/33256">Thieves Guild Requirements</a></li>
        <li><a href="https://www.nexusmods.com/skyrimspecialedition/mods/14883">All Thieves Guild Jobs Concurrently</a></li>
        <li><a href="https://www.nexusmods.com/skyrimspecialedition/mods/365">The Paarthurnax Dilemma</a></li>
        <li><a href="https://www.nexusmods.com/skyrimspecialedition/mods/3850">The Choice is Yours</a></li>
        <li><a href="https://www.nexusmods.com/skyrimspecialedition/mods/329">Boethiah for Good Guys</a></li>
        <li><a href="https://www.nexusmods.com/skyrimspecialedition/mods/5272">Better College Application</a></li>
        <li><a href="https://www.nexusmods.com/skyrimspecialedition/mods/33594">Bounties Are Worthwhile</a></li>
        <li><a href="https://www.nexusmods.com/skyrimspecialedition/mods/34681">Save the Icerunner</a></li>
        <li><a href="https://www.nexusmods.com/skyrimspecialedition/mods/11076">Open Civil War</a></li>
      </ul>
    </td>
    <td class="tg-0pky">
      <ul style="list-style-type:none;">
        <li><a href="https://www.nexusmods.com/skyrimspecialedition/mods/11849">Vigilant</a></li>
        <li><a href="https://www.nexusmods.com/skyrimspecialedition/mods/2303">Become a Bard</a></li>
        <li><a href="https://www.nexusmods.com/skyrimspecialedition/mods/5673">Helgen Reborn</a></li>
        <li><a href="https://www.nexusmods.com/skyrimspecialedition/mods/24351">Carved Brink</a></li>
        <li><a href="https://www.nexusmods.com/skyrimspecialedition/mods/20733">The Falkreath Hauntings</a></li>
        <li><a href="https://www.nexusmods.com/skyrimspecialedition/mods/1179">The Forgotten City</a></li>
        <li><a href="https://www.nexusmods.com/skyrimspecialedition/mods/4301">Moon and Star</a></li>
        <li><a href="https://www.nexusmods.com/skyrimspecialedition/mods/4155">Clockwork</a></li>
        <li><a href="https://www.nexusmods.com/skyrimspecialedition/mods/15996">Project AHO</a></li>
        <li><a href="https://www.nexusmods.com/skyrimspecialedition/mods/22206">Konahrik's Accoutrements</a></li>
        <li><a href="https://www.nexusmods.com/skyrimspecialedition/mods/15264">Artifacts - The Tournament of the Ten Bloods</a></li>
        <li><a href="https://www.nexusmods.com/skyrimspecialedition/mods/748">The Wheels of Lull</a></li>
        <li><a href="https://www.nexusmods.com/skyrimspecialedition/mods/14168">The Tools of Kagrenac</a></li>
        <li><a href="https://www.nexusmods.com/skyrimspecialedition/mods/22513">Faction - Pit Fighter</a></li>
        <li><a href="https://www.nexusmods.com/skyrimspecialedition/mods/36707">The Tale of Tsatampra Xiros</a></li>
        <li><a href="https://www.nexusmods.com/skyrimspecialedition/mods/11802">Legacy of the Dragonborn</a></li>
      </ul>
    </td>
    <td class="tg-0pky">
      <ul style="list-style-type:none;">
        <li><a href="https://www.nexusmods.com/skyrimspecialedition/mods/2057">Falskaar</a></li>
        <li><a href="https://www.nexusmods.com/skyrimspecialedition/mods/12186">Hammet's Dungeons</a></li>
        <li><a href="https://www.nexusmods.com/skyrimspecialedition/mods/31472">Vominheim</a></li>
        <li><a href="https://www.nexusmods.com/skyrimspecialedition/mods/19492">Wyrmstooth</a></li>
        <li><a href="https://www.nexusmods.com/skyrimspecialedition/mods/4509">The Gray Cowl of Nocturnal</a></li>
        <li><a href="https://www.nexusmods.com/skyrimspecialedition/mods/4341">Moonpath to Elsweyr</a></li>
      </ul>
    </td>
  </tr>
</tbody>
</table>
It would take a tome to cover every single mod here, but there are a few to be aware of in particular: [Not So Fast - Main Quest](https://www.nexusmods.com/skyrimspecialedition/mods/2475), [Not So Fast - Mage Guild](https://www.nexusmods.com/skyrimspecialedition/mods/5686), [Timing is Everything](https://www.nexusmods.com/skyrimspecialedition/mods/25464), and [Legacy of the Dragonborn](https://www.nexusmods.com/skyrimspecialedition/mods/11802). The first two introduce breaks in the main storyline of Skyrim and the Mage's Guild questline, giving you time to go do other things while waiting for those to progress. You'll need these breaks as there's a significant difficulty spike between Bleak Falls Barrow and your first dragon fight as well as between the First Lessons quest and the expedition to Saarthal. Timing is Everything delays the DLCs (Dragonborn and Dawnguard, specifically) and various other quests until you are strong enough to take them on. 

Legacy of the Dragonborn of course requires no introduction, but if you're somehow unaware, it adds a museum in Solitude that allows you to proudly display the various items you'll find in Skyrim. It has a home for almost every unique item (and many non-unique items) as well as introducing its own questline, a new guild you can be the leader of, and its own player home. While Legacy of the Dragonborn is not a focus of Living Skyrim, every applicable patch has been included as well as [The Curator's Companion](https://www.nexusmods.com/skyrimspecialedition/mods/38529) so you can easily identify items that go in the museum and you can reasonably expect to have a home for any and all items you come across. If collecting and hoarding items is your thing, Legacy of the Dragonborn is for you.

### The Magic Mods
[Smart Cast](https://www.nexusmods.com/skyrimspecialedition/mods/32847) has supplanted Sustained Magic in Living Skyrim 3 for a multitude of reasons, the primary being that it works with every other magic mod out of the box. With Smart Cast you can set up specific rules and conditions under which spells will be cast for you - assuming you have the magicka to cast them. It also lets you combine spells into a single cast, again, assuming you have the magicka to cast them both at the same time. This mod has quite a few features available, reading its mod page is highly recommended.

[Immersive Spell Learning](https://www.nexusmods.com/skyrimspecialedition/mods/33375) completely changes how your character learns new spells. Instead of "eating" the book and learning the spell, you now have to spend time studying notes about the spell to learn it over time. The amount of time it takes to learn new spells is completely configurable through this mod's MCM menu, so feel free to tweak it to your liking. This mod's inclusion is intended to help balance magic as the combination of magic mods included in Living Skyrim make magic *significantly* stronger.

[Mysticism](https://www.nexusmods.com/skyrimspecialedition/mods/27839), [Forgotten Magic](https://www.nexusmods.com/skyrimspecialedition/mods/12711), [Tomebound](https://www.nexusmods.com/skyrimspecialedition/mods/21403), [Triumvirate](https://www.nexusmods.com/skyrimspecialedition/mods/39170), and [Elemental Destruction Magic](https://www.nexusmods.com/skyrimspecialedition/mods/440) make up the mods adding new spells to Living Skyrim. Between all of these and the additional options found below, it is possible to have multiple mage playthroughs and never do the same build twice.

[Thunderchild](https://www.nexusmods.com/skyrimspecialedition/mods/1460), [Summermyst](https://www.nexusmods.com/skyrimspecialedition/mods/6285), and [Wintersun](https://www.nexusmods.com/skyrimspecialedition/mods/22506), and [Mundustar](https://www.nexusmods.com/skyrimspecialedition/mods/41674) are all included to make magic as diverse as possible with a huge breadth of options. Wintersun covers the religious aspect of the game, Summermyst covers enchantments, Thunderchild covers shouts, and Mundustar covers the various standing stones of the world.

### The Combat Mods
The core combat package of Living Skyrim is [Blade & Blunt](https://www.nexusmods.com/skyrimspecialedition/mods/34549), The Ultimate Dodge Mod, and [VioLens](https://www.nexusmods.com/skyrimspecialedition/mods/668). Assuming a fair fight this generally means that combat will be fast-paced and somewhat deadly. You won't get one-shot unless you're fighting an enemy that is significantly higher level than you (10+ levels above your own).

[Archery Gameplay Overhaul](https://www.nexusmods.com/skyrimspecialedition/mods/24296) completely revamps the archery system in Skyrim. You'll find it now has much more realistic gameplay including arm fatigue, the ability to spread poisons across multiple arrows, stamina drain while the bowstring is pulled, and so on. This mod is highly configurable via its MCM menu, so feel free to tweak it to suit your playstyle.

Also for your consideration: [SkyTEST](https://www.nexusmods.com/skyrimspecialedition/mods/1104), [Deadly Dragons](https://www.nexusmods.com/skyrimspecialedition/mods/23723), and [Arena - An Encounter Zone Overhaul](https://www.nexusmods.com/skyrimspecialedition/mods/19608). Enemies in general will be smarter and stronger across the board, and will dynamically update their levels to match or surpass you as appropriate.

### The Perks & Leveling Mods
[Vokrii](https://www.nexusmods.com/skyrimspecialedition/mods/26176) is the perk overhaul of choice for Living Skyrim. It is a lightweight but still complete overhaul of the perk trees allowing for an incredibly diverse amount of character customization and specialization. [Experience](https://www.nexusmods.com/skyrimspecialedition/mods/17751) is included to control the rate at which your skills and levels progress. By default, only clearing dungeons and completing quests will provide XP. The optional skills XP and kills XP modules can be turned on, but Living Skyrim isn't set up to use these by default so you may come across some oddities (enemies that don't grant XP when killed, for example).

### The Economy and Loot Mods
There are two sides to the Skyrim economy: Loot, and trade. Loot is your primary source of income, and trade your primary source of expenditure. To address this, Living Skyrim seeks to overhaul both sides of this coin.

On the loot side, you'll find that chests and enemies are fairly abundant loot thanks to [GOLD](https://www.nexusmods.com/skyrimspecialedition/mods/1796), [Dynamic Dungeon Loot](https://www.nexusmods.com/skyrimspecialedition/mods/10308), and [Lock Related Loot](https://www.nexusmods.com/skyrimspecialedition/mods/10308). In general, chests have been overhauled such that no two chests are ever the same and contain a fantastic assortment of things you can find. You may also find powerful items significantly earlier than normal due to Dynamic Dungeon Loot. Normally this would be cause for concern, but you will also find that the amount of just randomly placed objects in the world has been significantly decreased by [Iris](https://www.nexusmods.com/skyrimspecialedition/mods/41920). The removal of most of the items placed in the world shifts the focus of loot from picking up everything in a dungeon to seeking out and opening every chest you can find. Also, for good measure, you'll find a small quality of life improvement in [Lootable Woodpiles](https://www.nexusmods.com/skyrimspecialedition/mods/12238). 

Opposite the loot side, we have the economy side of things. Naturally, because of the increased amount of loot you'll find, the price of many items has been increased drastically. No longer will a set of steel armor cost just a couple hundred gold - instead, you'll find it costs well over 1000 gold, and higher level armors only get even more expensive. The same is true of just about everything you can purchase from a vendor. This is due to the combination of [Trade & Barter](https://www.nexusmods.com/skyrimspecialedition/mods/23081) and [Eve](https://www.nexusmods.com/skyrimspecialedition/mods/26325). Items will sell for less and cost more to buy across the board. This is necessary to make looting feel significant while also keeping some semblance of balance. In general it will be more difficult to obtain obscene amounts of gold, but it is still possible - that's just how Skyrim works without going completely overboard modifying the loot/economy. Also, for the more kleptomania-inclined among you, you'll find some helping hands in [Khajiits Steal Too](https://www.nexusmods.com/skyrimspecialedition/mods/18231).

### The HUD Mods
Living Skyrim includes a completely different UI and HUD experience than what you're used to, probably even if you've played modded Skyrim before. [Less Intrusive HUD II](https://www.nexusmods.com/skyrimspecialedition/mods/17974) is 100% customizable through an in-game menu, allowing you to change the position, size, opacity, and anything else for any HUD element. [EZ2C Dialogue Menu](https://www.nexusmods.com/skyrimspecialedition/mods/2246) changes the dialogue menu to be easier to read and use and is also 100% configurable. See the mod description pages for EZ2C and Less Intrusive HUD II to see how to configure these to your liking. [Immersive HUD](https://www.nexusmods.com/skyrimspecialedition/mods/12440) keeps pesky HUD elements out of the way when you don't need to see them. Lastly, [Favorite Things](https://www.nexusmods.com/skyrimspecialedition/mods/27177) greatly expands the SkyUI Favorites menu to make it larger, easier to use, and more customizable. 

### Character Customization Mods
When creating your character, you'll find there are a lot of options that are available to you. From hairs to tattoos to eyes and more, Living Skyrim has included a comprehensive suite of mods that allow you to tweak your character's appearance to exactly what you want. And, if you're struggling to figure out where to begin with character creation, a number of presets made by the Living Skyrim community have been included for you to pick from. In general, you'll have more options for *everything*.

There is one particular mod you need to be aware of during character creation: [High Poly Head](https://vectorplexus.com/files/file/283-high-poly-head/). To have your character use High Poly Head, you'll need to change the head part using the RaceMenu slider of the same name to option 3. Note that if you do use High Poly Head, you may need to do some manual sculpting using the RaceMenu sculpt feature to remove any clipping issues with eyebrows or beards. 

### Player Homes
Living Skyrim includes a fairly diverse selection of player homes that are suitable for a number of different character styles. See below for a complete listing.

<table>
<thead>
  <tr>
    <th>
      <ul style="list-style-type:none;">
        <li><a href="https://www.nexusmods.com/skyrimspecialedition/mods/2242">Blackthorn</a></li>
        <li><a href="https://www.nexusmods.com/skyrimspecialedition/mods/2434">The Scarlett</a></li>
        <li><a href="https://www.nexusmods.com/skyrimspecialedition/mods/20982">Riverside Shack</a></li>
        <li><a href="https://www.nexusmods.com/skyrimspecialedition/mods/2460">Redspire Manor</a></li>
        <li><a href="https://www.nexusmods.com/skyrimspecialedition/mods/324">Castle Volkihar Rebuilt</a></li>
        <li><a href="https://www.nexusmods.com/skyrimspecialedition/mods/26277">Gleamblossom Hollow</a></li>
        <li><a href="https://www.nexusmods.com/skyrimspecialedition/mods/9661">Haafinheim</a></li>
        <li><a href="https://www.nexusmods.com/skyrimspecialedition/mods/41895">Winking Skeever Loft</a></li>
        <li><a href="https://www.nexusmods.com/skyrimspecialedition/mods/8046">Windyridge</a></li>
      </ul>
    </th>
    <th>
      <ul style="list-style-type:none;">
        <li><a href="https://www.nexusmods.com/skyrimspecialedition/mods/33408">Morskom Estate</a></li>
        <li><a href="https://www.nexusmods.com/skyrimspecialedition/mods/1193">Routa</a></li>
        <li><a href="https://www.nexusmods.com/skyrimspecialedition/mods/20486">The Raven's Breezehome</a></li>
        <li><a href="https://www.nexusmods.com/skyrimspecialedition/mods/411">Mornfallow Manor</a></li>
        <li><a href="https://www.nexusmods.com/skyrimspecialedition/mods/34542">JK's Riverfall Cottage</a></li>
        <li><a href="https://www.nexusmods.com/skyrimspecialedition/mods/33889">Zulfardin</a></li>
        <li><a href="https://www.nexusmods.com/skyrimspecialedition/mods/8681">Niflholm</a></li>
        <li><a href="https://www.nexusmods.com/skyrimspecialedition/mods/9883">Mona Alta</a></li>
        <li><a href="https://www.nexusmods.com/skyrimspecialedition/mods/6635">Pinewood Manor</a></li>
      </ul>
    </th>
  </tr>
</thead>
</table>

Additionally, several of the quest mods included with Living Skyrim have player homes associated with them. Namely, Legacy of the Dragonborn, Helgen Reborn, and Project AHO. Make sure to investigate all of your options!

### Nether's Follower Framework
[Nether's Follower Framework](https://www.nexusmods.com/skyrimspecialedition/mods/18076) has too many features to list, but what you need to know is this: You can have multiple followers, you can configure just about anything about them, and you'll have a lot more flexibility with controlling your followers. You can also import followers added by mods to be able to use NFF's features on them. 

<table class="tg">
<thead>
  <tr>
    <th class="important"><b>Important!:</b> Do NOT import standalone followers (Inigo, Lucien, etc.) into Nether's Follower Framework. It will 100% break them. The notable exceptions to this are Auri, Sophia, and any of the Interesting NPCs followers.</th>
  </tr>
</thead>
</table>

## Bug Reporting, Github, and You
While we have tried out best to eliminate as many bugs and inconsistencies as possible, it is unfortunately a near certainty that at some point you will come across something that could be considered a bug. Whether it's duplicate objects overlapping, an imbalanced crafting recipe, or something else entirely, it's important that you report bugs you find on the Living Skyrim 3 Github so that it can be fixed for everyone.

To report a bug, follow these steps:

1. Login to [Github](https://github.com) or create an account as necessary.
2. Open this link: [Click Here!](https://github.com/ForgottenGlory/Living-Skyrim-3/issues/new/choose)
3. Click the green button that says "Get Started" in the line next to "Bug Report".
4. Input a title and fill out the form in the large text box. If you need to attach a screenshot, it can be dragged from your computer to the Github post to insert it.
5. When you have filled out the form completely, click the green "Submit new issue" button.

After that, you've filed your bug report and the LS dev team will take a look at it as soon as possible. Don't forget to check back on your report periodically just in case we request more information from you.

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
Yes, [Complete Widescreen Fix](https://www.nexusmods.com/skyrimspecialedition/mods/1778) is included by default. Just make sure to enable it in the left pane of MO2.

#### "Immersive Spell Learning still allows me to read the spell tome to learn spells instantly."
Yes, this is a known issue and is somewhat intended. Legacy of the Dragonborn's museum counts spell tomes towards its display count, so rather than have players find/buy two copies of a spell tome (one to learn from and the other to store in the museum), I've opted to allow spell tomes to stay in your inventory. If you don't like having the temptation of "cheating" and don't mind having to hunt down a second copy of the book, you can always enable "Destroy Spell Tomes" in the Immersive Spell Learning MCM.

#### "What the heck is going on with the dialogue menu?"
It's being modified by [EZ2C Dialogue Menu](https://www.nexusmods.com/skyrimspecialedition/mods/2246/). Check that mod's page for details of how to configure it if it's not to your liking.

### Nudity?
By default, Living Skyrim has every character be never nude. Underwear is worn by all NPCs and the player character and cannot be unequipped. Support is not provided for making the list Nude.

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
- Living Skyrim Dev Team:
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
