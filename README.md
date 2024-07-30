This GitHub is for updating the Mod Manager from within the program and files should not be manualy downloaded from here as they dont contain all the needed files. If you are trying to download the Mod Manager please got to my other GitHub( https://github.com/Jimk72/Icarus_Software )that has the full zip file download for Icarus Mod Manager!

# Icarus Mod Manager 2.1 

## 7/30/24 Ver 2.1.9

-Fixed several small bugs.

-Redid the whole unpak function to be more reliable with extremely large pak files.

-Several new features for modders in the edit mod screen.

-Changed the outdated mods date system to be compatible with other locals.

-Several backend changes for the new features coming out in 2.2.0 :)

## 6/30/24 Ver 2.1.8

-Improved the Merge efficiency.

-Background changes to clean up code.

-Added option in settings to hide Log updates when merging mods.

-Added progress bar for merging mods so you can see how far along it is.

-Changed wording on merge conflicts to hopefully be more clear on what the conflict is and the options avail.

## 6/29/24 Ver 2.1.7

-Improved the Merge efficiency.

## 6/16/24 Ver 2.1.6

-Fixed bug with multiple new Items with same name not being added to pak file.

## 5/29/24 Ver 2.1.5

-Changed show message of invalid date to add line to log that mod contains invalid date.

## 5/27/24 Ver 2.1.4

-Downloads section now returns you to same spot in list after downloading a mod.

-Added create new mod option to rightclick menu in main extracted list. This will create a new extracted mod folder and json to start a new mod in IMM

-Added new menu when right clicking in IMM editor in the Json section. Allows Copy and paste from there as well as several other new options.

Insert file at location. This will allow you to add the header needed for a file in the editor. Selecting this will show a list of all the games files and allow you to select one. After it is add, just click save and it will expand the json and propperly format it, then click Re-Load in the upper left corner for the file to show in left list.

Merge existing mod into this one. This allows you to merge an existing mod with the currently editing one. Will copy all files and merge the extracted json. 

Open mods folder. This will open the folder of the currently editing mod.

-Added 3 copy buttons and 3 paste button at top of editor. This allows you to select json data and store it for pasting. Hovering over the top of the button will display the json stored. There are also 3 copy buttons on the "View Originals" page that corrispond to these same 3 buttons.

-Added Undo button to the IMM editing page.


## 3/18/24 Ver 2.1.2

-Added Download/install for UnrealPak for new users

## 3/10/24 Ver 2.1.1

Quality of Life Update!

-IMM now reloads the last merged list at start.

-Added a button on right side to Reload last merged list at any time.

-IMM now saves the last merged list in its own folder for access anytime(LastMergedMods.txt).

-IMM now saves the list of merged mods in your mods folder along with IMM_Merged_Mod_P.pak called IMM_Merged_Mod.txt this is for servers so you can copy both files to your servers mods folder and always know what mods are in the IMM_Merged_Mod_P.pak file.

-Added the ability to add merge options to game with no mods selected. 

  Just select the merge options you want to add and click Install All Listed Mods with no mods added to the list. IMM will pop up a question asking if you want to create a mod with the merge options and add to game.

-IMM now saves the merged Options you have selected when you close it, and restores those option the next time you run it.

## 2/23/24 Ver 2.1.0

-Redid UI to allow new merge options.

These new options are added after the mods are all merged. By doing this it effects the custom item mods also. To use these options, just select the options you want to eneable before clicking Install All Listed Mods button.

-Added reduce crafting cost %25 to merge options

This will reduce all crafting bench recipies by %25.

-Added reduce crafting cost %50 to merge options

This will reduce all crafting bench recipies by %50.

-Added Creative mode to merge options

This will reduce all crafting bench costs to 0.

-Added Speed Crafting to merge options

This sets craft time to 1 for all items.


# Icarus Mod Manager 2.0 

## 1/14/24 Ver 2.0.7

-Added Minimize button.

-Added Language.ini to allow uses to change the display text.

-Added experimental post process functions for future functionality.

## 1/5/24 Ver 2.0.6

-QuickFix for Display issues

## 12/30/23 Ver 2.0.5

-Added new Syntax Highlighter for the Editor page.

-Added ability to search in the editor.

-Added new page for viewing original json when in the editor.

## 12/10/23 Ver 2.0.4

-Minor bug fix with UI

-Added sort to mods download page when clicking on column headers.

## 11/7/23 Beta Ver 2.0.0

First Beta release of new 2.0 system/file/folder setup.
I set this as a Beta as its a total rewrite of the backend folder structure/extracted mods system.
NOT COMPATIBLE with previous versions of IMM. Do not place in your old IMM folder as it will not pick up any mods.
Since the folder structure is all new Place in a new folder with a fresh start.
