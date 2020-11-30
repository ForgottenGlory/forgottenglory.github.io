---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---

# How to Patch Anything

## Setup

Before you do anything, you need to make sure you open SSEEdit properly. So, launch SSEEdit and make sure you load every single ESP there is. Once everything has loaded (indicated by a "Background loader complete" message in the bottom left corner of SSEEdit), left click anywhere in the left pane of SSEEdit. Then, press Ctrl+A to select everything.

Now, right-click anywhere in the left-pane of SSEEdit and pick "Apply Filter to show Conflicts".

This may take several minutes to run. When finished, you'll see a **lot** of red. Don't panic! Red does not necessarily mean bad.

Now, pick an ESP from the list - any ESP. Start going through the list of records and look for yellow, green, or red. Green you can (usually) ignore. Yellow and Red is where a patch might be needed.

## Step Zero
### Do you really have to patch this?

The first step whenever you think you need to patch something is to first look at what you are patching in relation to the other mods in the load order. If you can save yourself the trouble of creating a patch by moving the mod in the load order, you should always do this instead of creating a patch.

So, how do you know if this is the case? Let's look at an example.



## Step One
### Creating a Patch

The first thing you need to do if you do need to make a patch is to copy a record into a new ESL. Patches for LS3 should **always** be ESL flagged ESPs. We'll talk about that more in a moment.

So, find a record that you need to patch:

Right click on the header and select "Copy as overwrite..."

You will be prompted to select an ESP to copy the record into. As mentioned before, you should create a **new** ESL-flagged ESP for this patch. Name the patch as follows:

```
LS3 [Mod Name] Patch
```

Replacing [Mod Name] with an abbreviation of the name of whatever mod you are making a patch for.



## Step Two
### Patching

## Step Three
### Saving your Patch