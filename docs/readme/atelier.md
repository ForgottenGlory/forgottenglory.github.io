---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: atelier_readme
permalink: /readme/atelier/
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

![Atelier Logo](https://i.imgur.com/8NqqiFi.png)

Current version: 1.0.0.1 (Beta 1) 12/6/2020

## Table of Contents
- [Table of Contents](#table-of-contents)
- [Preface](#preface)
  - [Warnings/Disclaimers](#warningsdisclaimers)
  - [System Specifications](#system-specifications)
  - [Important Links](#important-links)
    - [(SFW) Screenshots](#sfw-screenshots)
- [Pre-Installation](#pre-installation)
  - [Skyrim Setup](#skyrim-setup)
  - [Steam Setup](#steam-setup)
  - [Launching Skyrim](#launching-skyrim)
  - [Wabbajack Preparations](#wabbajack-preparations)
- [Wabbajack Installation](#wabbajack-installation)
  - [With Nexus Premium](#with-nexus-premium)
  - [Without Nexus Premium](#without-nexus-premium)
- [Post-Wabbajack Install](#post-wabbajack-install)
  - [Game Folder Files](#game-folder-files)
  - [Mod Organizer 2](#mod-organizer-2)
    - [Configuration-Specific](#configuration-specific)
  - [ENB](#enb)
- [Updating Atelier](#updating-atelier)
- [BodySlides](#bodyslides)
  - [A Note About Presets](#a-note-about-presets)
- [Launching Atelier](#launching-atelier)
  - [The MCM Settings](#the-mcm-settings)
- [The Screenshots](#the-screenshots)
- [Adding to Atelier](#adding-to-atelier)
- [Important Mods You Need to Know About](#important-mods-you-need-to-know-about)
  - [The Screenshot Tools](#the-screenshot-tools)
  - [The Pose Mods](#the-pose-mods)
  - [The Character Customization Mods](#the-character-customization-mods)
  - [The Outfits](#the-outfits)
- [Final Thoughts & Best Practices](#final-thoughts--best-practices)
- [Troubleshooting & FAQ](#troubleshooting--faq)
- [Credits & Thanks](#credits--thanks)
  - [One Last Thing](#one-last-thing)

## Preface
Atelier (noun, /ˌadlˈyā/): a workshop or studio, especially one used by an artist or designer. And in this context, a Skyrim SE modlist focused on one thing and one thing only: taking screenshots. Atelier is setup to make taking screenshots as easy as possible out of the box. Just install, load up the game, pick some outfits, and you're ready to go. This modlist isn't intended to be "played" in the traditional sense. Certainly, the game is functional - all of the vanilla quests work and can be done - but that's not what we're here for. Instead, we're here for powerful camera controls, the ability to set a scene exactly as you wish, and a vast array of outfits to pick from.

All of this with support for adding even more outfits and plenty of photo studio locations in-game to get exactly the type of backdrop you want. And if you want to take some shots of landscapes, skies, and so on, you can do that too. Built using the Living Skyrim 3 graphics package, Atelier will provide an outstanding game look even beyond all the character customization and outfits.

Last, but certainly not least, Atelier includes a very lightweight SexLab setup - meaning that if you want to explore the more lewd side of screenshots, you can absolutely do so. A selection of NSFW animations and skimpy outfits have been included so you can setup the perfect shot. Atelier also supports male characters out of the box if you prefer that.

### Warnings/Disclaimers
Wabbajack no longer requires that you have Nexus Premium to install the modlist, however, having Nexus Premium will cut your install time to a fraction of what it would be instead of downloading each mod individually (and save you a couple thousand clicks or so).  

The modlist requires ~174GB (46.7GB Downloads/128GB Mods) of hard drive space on top of the ~11GB Skyrim: Special Edition base files. Installing onto an SSD/NVMe is not required, but **strongly recommended**. Download and installation times vary based on your computer and internet speeds but expect the entire process to take a few of hours.

<table class="tg">
<thead>
  <tr>
    <th class="warning"><b>WARNING:</b> This modlist contains explicit sexual content and nude character models. Proceed at your own discretion.</th>
  </tr>
</thead>
</table>

### System Specifications
Atelier is somewhat graphically intensive, but with how lightweight the rest of the list is, it performs very well. As a result, the following hardware can run the list at a consistent 60+ FPS with ENB. Use it to gauge how your system might run the list.

- CPU: Intel i5-8600K Overclocked to 4.2GHz 
- RAM: 16GB DDR4 (16299MB actual)
- GPU: nVidia RTX 2080 Super 8GB (8192MB actual)
- Monitor: Dell S2716DGR 2560x1440 @ 144hz

Skyrim is very heavy on processors. Generally, anything above 3GHz should be fine but I can’t guarantee it. 6GB or 8GB of VRAM should be plenty, with 4GB of VRAM probably capable of 60FPS without ENB.

### Important Links 
[Atelier FAQ & Troubleshooting](#troubleshooting--faq)  
[Atelier Bug & Suggestions Tracker](https://github.com/ForgottenGlory/Atelier/issues)  
[Atelier Discord](https://discord.gg/9dFvGnc)  
[Atelier Patreon](https://www.patreon.com/LivingSkyrim)

#### (SFW) Screenshots
[One](https://cdn.discordapp.com/attachments/785328628455309322/786345280765165588/The_Elder_Scrolls_V_Skyrim_Special_Edition_Screenshot_2020.12.09_-_00.39.52.44.jpg) [Two](https://cdn.discordapp.com/attachments/785328628455309322/785531777132527646/ScreenShot16.png) [Three](https://cdn.discordapp.com/attachments/785328628455309322/785531768325144587/ScreenShot15.png) [Four](https://cdn.discordapp.com/attachments/785328628455309322/785531756823969852/ScreenShot9.png) [Five](https://cdn.discordapp.com/attachments/785328628455309322/785531742969659462/ScreenShot10.png) [Six](https://cdn.discordapp.com/attachments/785328628455309322/785531716060184576/ScreenShot4.png) [Seven](https://cdn.discordapp.com/attachments/785328628455309322/790712681657008168/ScreenShot26.png) [Eight](https://cdn.discordapp.com/attachments/785328628455309322/791231378389860352/enb2020_12_23_03_56_28.png) [Nine](https://cdn.discordapp.com/attachments/785328628455309322/791231374363066398/enb2020_12_23_03_35_52.png) [Ten](https://cdn.discordapp.com/attachments/785328628455309322/785531771126677525/ScreenShot5.png) [Eleven](https://cdn.discordapp.com/attachments/785328628455309322/785531758711799818/ScreenShot12.png) [Twelve](https://cdn.discordapp.com/attachments/785328628455309322/785531751841529886/ScreenShot6.png) 

## Pre-Installation
### Skyrim Setup
As with any modlist, it is strongly recommended that you start with a clean, unmodified installation of Skyrim: Special Edition. To get your Skyrim SE to this state, follow these steps:

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

### Steam Setup
1. In Steam, set Skyrim: Special Edition to update only when opened. (Right-click > Properties… > Updates > Automatic updates > Only update this game when I launch it)
2. In Steam, disable the Steam Overlay. (Right-click > Properties... > General > Enable the Steam Overlay while in-game checkbox)
   
### Launching Skyrim
Launch Skyrim SE to create any INI or registry entries the game needs. Immediately exit after the launcher has successfully selected a graphics preset for your hardware. The INIs will be overwritten by the ones included in the Wabbajack installer.

### Wabbajack Preparations
1. Download the latest version of [Wabbajack](https://github.com/wabbajack-tools/wabbajack/releases). Do not run anything until instructed to do so. Make sure you are using the latest version of Wabbajack or else Wabbajack will report a corrupted modlist.
2. Create a new folder in the root of the drive where you want Wabbajack to be installed. Name this folder `Wabbajack`.
3. Create a second folder called `[Install Drive]\Atelier`. This folder is where the modlist will be installed.
4. Double check that you have *not* placed any of these folders in your Skyrim: Special Edition installation directory.
5.  Ensure that `[Install Drive]\Atelier` is **completely empty.**
6.  Ensure that Wabbajack.exe is in `[Install Drive]\Wabbajack`.

<table class="tg">
<thead>
  <tr>
    <th class="warning"><b>WARNING:</b> Failure to set up these folders properly will result in the install failing. For example, [install drive]\Wabbajack\Atelier is <b>incorrect</b>.</th>
  </tr>
</thead>
</table>

## Wabbajack Installation
If you are updating your existing installation of Atelier, skip to [Updating Atelier](#updating-dungeons--deviousness).

1. Download the latest version of the Atelier modlist installer (the .wabbajack file) from here: [Click Here](https://drive.google.com/drive/folders/1GYU6gFLmkTzntxv8kqem-7oDlmzE9VLA?usp=sharing)
2. Run Wabbajack.exe. 
3. At the bottom of the window click Install From Disk, then navigate to where you saved the file you downloaded and select that file.
4. Set the Installation Location to `[Install Drive]\Atelier`. The download location does not need to be set manually unless you have drive space limitations. Downloading to a separate folder is fine (for example, on a HDD), but as before it is recommended that the actual install be placed on a SSD. **Important!:** Do not install the modlist to your Skyrim SE installation folder OR the folder that Wabbajack.exe is in.
5. Click the play/right arrow button to begin installation.

### With Nexus Premium
5. Wabbajack will walk you through logging into the Nexus and authorizing an API key so it can download mods if you have not done so previously.
6. Let Wabbajack do its thing. This will take a little while (usually 3-4 hours at most), so go get a snack and read the [Important Mods You Need to Know About](#important-mods-you-need-to-know-about) section of this document.

### Without Nexus Premium
1. Wabbajack will prompt you to click all the needed buttons to download the modlist. Be prepared for this to take a really long time, possibly more than one day. Also be aware that due to the amount of time required when installing this list manually, the list may update during the time it takes to install and you may need to start over if that happens. Put on some music or a TV show and make a day of it. If you need a break during this process, grab a snack and read the [Important Mods You Need to Know About](#important-mods-you-need-to-know-about) section of this document.

Once complete, Wabbajack will say “Installation complete! You may exit the program.” If it does not, visit the [FG's Modlists Discord server](https://discord.gg/9dFvGnc) for assistance. **Don’t forget to upload your log file!**  

If Wabbajack fails to download a particular mod, it means that the mod has likely been updated. This also means that an update to Atelier is imminent. Be patient and wait for the new release. **Do not ask other people to share older files as this is a violation of the Nexus ToS.**  

## Post-Wabbajack Install
### Game Folder Files
Now you have to copy some files to their correct locations. Navigate to `[Install Drive]\Atelier\Game Folder Files`. Copy all of the files inside the Game Folder Files folder into `[Steam Install Location]\steamapps\common\Skyrim Special Edition\` and Overwrite if prompted. This folder contains SKSE and Engine Fixes part 2, which are required to use Atelier and must be placed into your Skyrim's installation folder for the list to function.

<table class="tg">
<thead>
  <tr>
    <th class="warning"><b>WARNING:</b> These files include SKSE and Engine Fixes Part 2, both of which are essential for the list to function correctly. Failure to copy these files will result in the list not working.</th>
  </tr>
</thead>
</table>

### Mod Organizer 2
1. Navigate to `[Install Drive]\Atelier` and open ModOrganizer.exe. Your Mod Organizer window will have a dark theme already selected. If it doesn’t, something has gone wrong and you’ll likely need to do the Wabbajack installation again.
2. A dialogue will appear and ask if you want to associate Mod Organizer with nxm links. Click **Yes.**

#### Configuration-Specific
There are two mods included with Atelier that you can optionally enable under the "Configuration Specific" section in the left pane of MO2. The first is Improved Camera, which I've included if you can handle it (I personally get motion sickness while using it.). The second is Dear Diary Dark Mode 21:9, which you **need** to enable if you have a 21:9 monitor.

### ENB
ENB is not required to run Atelier, but it is intended to be used with it. You may skip these instructions if you don’t want to use ENB. 

In general, any ENB that is compatible with Obsidian Weathers will work with Atelier. My preferred ENBs are Rudy's, Amon Reborn, Silent Horizons, and Re-Engaged if you want some recommendations.

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

## Updating Atelier
If you are updating Atelier, the process is very simple. Before you update, you should at a minimum backup your saves. Updating may delete any saves that are present. Make sure you are using the latest version of Wabbajack or else Wabbajack will report a corrupted modlist.

1. Download the latest version of the Atelier modlist installer (the .wabbajack file) from here: [Click Here](https://drive.google.com/drive/folders/1GYU6gFLmkTzntxv8kqem-7oDlmzE9VLA?usp=sharing)
2. Run Wabbajack.exe. 
3. At the bottom of the window click Install From Disk, then navigate to where you saved the file you downloaded and select that file.
4. Set the Installation Location to wherever you already have Atelier installed. 
5. **Important!:** Set your downloads folder path to the same downloads folder location you used when you first installed Atelier. Failure to do this will make Wabbajack download every mod again, which you want to avoid if possible.
6. Click Run.
7. When prompted if you would like to overwrite the existing installation, click "Confirm."

## BodySlides
When you first load up Atelier, there will be zero BodySlides created. You have to generate your own Bodyslides, as including them would make the Wabbajack installer file several gigabytes large.

Before you get started, if you have your own personal BodySlide preset that you like, drop the XML file into `[Install Drive]\Atelier\mods\Custom Presets\Caliente Tools\BodySlide\SliderPresets` alongside "Summer.xml".

One more thing: if you get an error about BodySlide not being able to find the output path, click on the Settings button in BodySlide, click on the "Advanced" button, and set the Output Path to `[Install Drive]\Atelier\mods\BodyslideOutfitStudio - Overwrite`.

1. Launch BodySlide from MO2.
2. Click on the magnifying glass icon near the top of the BodySlide Window and select "Choose Groups..."
3. Put a checkmark into **ONLY** "Atelier Outfits 1".
4. From the Preset dropdown, select your preferred preset. You can use the Preview button to preview what it will look like.
5. Make sure that the "Build Morphs" checkbox is checked at the bottom of the BodySlide window.
6. Click "Batch Build..." and then Build on the window that appears.
7. Repeat steps 3 through 6 for "Atelier Outfits 2" and "Atelier Bodies". For Atelier Bodies you may want to select a different Bodyslide preset if you want armor/clothing to look different than the nude bodies. (Dream Angel Outfit for the armors and Dream Angel Nude for the body, for example.)

### A Note About Presets
If you have your own favorite character face/head preset, drop the JSLOT file into `[Install Drive]\Atelier\mods\Custom Presets\SKSE\Plugins\CharGen\Presets` alongside Anna.jslot and Summer.jslot. It will be available in RaceMenu the next time you go to make a character. Make sure to back this up before updating the list as updating will erase any added files like this. Adding presets (whether they be BodySlide or RaceMenu) does not void support for Atelier.

If you have a preset (Bodyslide or RaceMenu, doesn't matter) that *you made* and you'd like it to be included in Atelier, send it to ForgottenGlory.

## Launching Atelier
The hard part is now over. Carry on, the end is in sight!

1. In Mod Organizer 2, select SKSE from the drop-down menu next to the Run button and click Run. This is how Atelier should always be launched. You can create a shortcut on your desktop if you wish using the Shortcut button under the Run button.
2. Once Skyrim starts, create a new game. 
3. Create your character (make sure your character is female or else the list won't work right) and name them whatever you’d like.
4. **As soon as you gain control of your character, do nothing.** The mods are loading and this can take several minutes. You’ll see a list of mods initializing in the top left of the screen.
5. Once you see that no more items are appearing in the list in the top left, you can proceed to the next steps.

<table class="tg">
<thead>
  <tr>
    <th class="warning"><b>WARNING:</b> Loading a save from another modlist or from before you installed Atelier will corrupt that save, do not do this.</th>
  </tr>
</thead>
</table>

### The MCM Settings
1. Consult the [Atelier MCM Configuration](https://forgottenglory.github.io/mcms/atelier/) document and follow all listed steps. This step is required if you want the list to work properly.
2. Don’t forget to save your game after configuring the MCMs, I promise you don’t want to have to do this step more than once.

## The Screenshots
Screenshots are, by default, saved to your Skyrim SE installation folder. If you are sharing your screenshots, make sure to upload the PNG version of the file and not the BMP version (the BMP version is created automatically by ENB). Many places (such as Discord) don't play nice with BMP files and prefer PNGs. 

If you want some tips on how to take better screenshots, consult this link: [Click Here](https://www.tesgeneral.com/screenshot) If you're feeling particularly fancy, you can even open up your screenshots in Photoshop or GIMP and make adjustments to get the exact feeling/color/style you're going for.

## Adding to Atelier
The only support provided for adding mods to Atelier is for adding additional Skyrim SE outfits using the CBBE or 3BBB bodies. Adding any other mods is not supported in any way, shape or form.

**Before you add anything to Atelier, you should be familiar with the following things: Installing mods using Mod Organizer; running BodySlide; using xEdit. If you don't have all three of these skills, you need to learn how to do them. No support will be provided for learning these skills.**

To add an outfit to Atelier, follow these steps:

1. Find an outfit you like.
2. Check to make sure it is for Skyrim SE and uses the CBBE body and has BodySlide support.
3. Optionally, see if there is a 3BBB version of the outfit available.
4. Install and enable the outfit mod using the copy of Mod Organizer included with Atelier.
5. In general, most outfits do not need to be patched with this list in xEdit, however, you should always check for conflicts using xEdit. If you do not know how to do this, you're out of luck if it doesn't work.
6. Follow the [BodySlides](#bodyslides) section of this readme to generate the meshes needed for the outfit to appear properly in game with the exception of the outfit group you choose. Choose the group your outfit is in and only generate the meshes for that outfit.

## Important Mods You Need to Know About
This section details the most important mods included in Atelier and is intended to give you a basic understanding of what to expect when you start the game.

### The Screenshot Tools
For ease of taking screenshots, the following mods are included: FreeFlyCam, ScreenshotPad SE, Weather Control, Rail Light, and AddItemMenu. With these you should be able to set up any location to be exactly what you want for the screenshots you want to take. One minor note: Rail Light is only intended to be used by female characters, equipping one of its lights on a male character will have interesting results, to say the least.

### The Pose Mods
Several pose packs are included: Halo's Poser, Shocky Pose Pack, GomaPeroPoses, and all three are included in Poser Hotkeys Plus, which allows you to quickly and easily cycle through poses. Check the MCM for Poser Hotkeys to see the keybinds for this mod.

### The Character Customization Mods
When creating your character, you'll find there are a lot of options that are available to you. From hairs to tattoos to eyes and more, Atelier has included a comprehensive suite of mods that allow you to tweak your character's appearance to exactly what you want. And, if you're struggling to figure out where to begin with character creation, a number of presets made by the Atelier community have been included for you to pick from in addition to many from Nexus. In general, you'll have more options for *everything*.

There is one particular mod you need to be aware of during character creation: [High Poly Head](https://vectorplexus.com/files/file/283-high-poly-head/). To have your character use High Poly Head, you'll need to change the head part using the RaceMenu slider of the same name to option 3. Note that if you do use High Poly Head, you may need to do some manual sculpting using the RaceMenu sculpt feature to remove any clipping issues with eyebrows or beards. 

### The Outfits
It would be an incredible task to document every outfit included with Atelier, but you'll find a huge assortment ranging from lore-friendly all the way up to and including outfits from entirely different video games and lores. Browse through the selection - there's a lot!

## Final Thoughts & Best Practices
- Autosaves are disabled. This save option is known to cause issues with heavily scripted games. Quicksaves are automatically turned into Manual Saves by SSE Engine Fixes. It is recommended to save **early** and **often**. Every 15 minutes and before interacting with quest NPCs, quest objects, and entering new zones should be sufficient. **Old saves can be deleted, but forgetting to save loses progress forever!**
- Wabbajack supports updating/upgrading over an existing installation, but it will automatically delete any files that aren’t used for the modlist installation. This means if you have changed the modlist in any way, Wabbajack will delete those changes and **delete your saves.** Keep backups of any changes you do make and your saves (as ill-advised as making changes may be).
- **NEVER** save right after a loading screen. Wait 30 seconds before saving to let scripts finish executing. It's always better to save before a loading screen than after one.
- **NEVER** use autosaves. Autosaves are unpredictable at best, and save-corrupting at worst.

## Troubleshooting & FAQ
Additions will be made to this FAQ as needed.

**I get stuck in certain animations!**  
This is usually caused by script lag. There's really no way around it, it will happen sometimes. Normally, you can open the console using the tilde key (~) on your keyboard or pause the game (Esc) for a few seconds and it will catch up. If you're still stuck after doing that, you may need to reload an earlier save. Unfortunately the combination of mods being used can have this happen on occasion. Short of rewriting the scripts used, there's really no way to fix it. Save frequently just in case this does happen to you.

**What do/don’t you support?**  
All unmodified Wabbajack installs of Atelier are supported. Pirated copies of Skyrim are illegal and not supported. Any modlist that changes Atelier by adding/removing non-outfit mods is not supported. Manually installed reproductions of Atelier are not supported. Any ENB compatible with the weather mods installed with Atelier are supported. With extremely few exceptions, mods from LE/Oldrim are not supported and will never be included in Atelier. Converting old saves to Atelier is not supported, only new saves created after Atelier is installed are supported. The same is true of saves from previous versions of Atelier.

**The installer isn’t working, what can I do?**  
The short answer: wait for an update. The long answer is you can try to install the missing mods manually if the files are still available on the Nexus, but again, do not ask for anyone to share old files. I work a full-time job in addition to several other personal projects, of which Atelier is just one. If installs are failing, I will try to update as quickly as possible but sometimes it may be a couple of days before I can get to it.

**How often does Atelier update?**  
There’s no set schedule for Atelier updates. If a mod updates and the list requires a revision, I’ll try to get to it as quickly as possible, but I make no promises. Sometimes troubleshooting updates and rebuilding the list can take days. Anytime there is an update, it will be clearly communicated on the Wabbajack and Atelier Discord servers. That being said, as long as nothing else changes, you should be safe to continue playing an existing installation unless there is an update to Skyrim itself. Remember: the point of all modlists is to play the game. If you’re spending more time updating your list than playing, you’re doing it wrong.

**I found a bug! How do I report it?**  
Check the [Atelier Issues](https://github.com/ForgottenGlory/Atelier/issues). If it’s not already on there, submit a new issue. Be as specific as possible, including screenshots if possible. If it is related to a specific mod, include the name of the mod and the exact steps to reproduce the issue. The best thing you can send for things like incorrect numbers/values or dark face NPCS (if there are any)  is a screenshot of the thing in question selected with the console including the ID of the object/character. Vague reports such as “my game randomly CTDs” will be ignored if they do not include more details.

**Can I play this list on a 75/100/144hz screen?**  
Yes. Display Tweaks SSE is included which allows for this.

**The modlist updated! Do I have to update and start a new save?**  
If your game is working, you’re not required to update. It’s always recommended though, as updates likely fix bugs, update mods, or add new mods or remove unsatisfactory ones. As for starting a new save, it depends on the version. In general, anything that is a 2.0.x update won’t break your save, and is usually just for when a mod updates and the list needs to be recompiled to make it work again. Anything that is an 2.x.0 update adds or removes mods, which likely will break your save (unless otherwise specified). Any full version number changes, x.0.0, are major overhauls/rebuilds of the list and are guaranteed to break your save.

**Can I stream/Let’s Play this modlist?**  
Have fun getting banned from whatever platform you use.

**My game freezes when saving.**  
Make sure you’ve disabled all overlays for Skyrim. The most common ones are Discord, Steam, and nVidia. Other overlays from things like MSI Afterburner and f.lux have also been known to cause issues.

**Can I request a mod be added to Atelier?**  
No.

## Credits & Thanks
- Atelier created by ForgottenGlory
- Atelier Dev Team:
  - Volk
  - Melisandre
  - JaceVenture
  - Magnus Hellfire
  - Bearnard
  - Volkaru
  - Day7
  - JaxomofRuatha
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
If you read through the entire readme, congratulations! You get a cookie. If you need any further help, feel free to reach out on the Wabbajack or Atelier Discord Servers. **Do not direct message ForgottenGlory or any Wabbajack staff members for support. I (ForgottenGlory) speak for myself, but I do reserve the right to ignore any requests for support direct messaged to me and block you.**