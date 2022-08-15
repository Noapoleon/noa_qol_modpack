<h1 align="center"><i><u>Noa's QoL Modpack 🦋</u></i></h1>

**Noa's QoL Modpack** is a **Fabric Minecraft 1.19.2 compatible modpack** that includes multiple client side mods to improve the vanilla experience.
It brings UI enhancements like a minimap, armor and tool durability viewer, inventory viewer without pressing 'e' and more which can all be toggled on and off based on your preference. Of course all mod authors are credited and all official download links are provided as well as a detailed step-by-step installation guide that can be found below.

Here are the different section you'll find in this guide:

+  **[Installation Guide (Windows)](#installation-guide)**
+  **[Sample Images](#sample-images)**
+  **[Download Links](#download-links)**
+  **[Credits](#credits)**

## Installation Guide
Here are the instructions you should follow to successfully run the modpack.

This guide uses will show your 3 things:
+  How to create a fabric profile in the default minecraft launcher
+  Install the modpack mods
+  Install my config files for the included mods (Optional)

1. Install the [Fabric Loader Version for 1.19.2](https://fabricmc.net/use/installer/)

    This step will create a new installation profile for fabric which you will use to launch minecraft in the minecraft launcher.

    + On the webpage the link above took you to click on the big blue "Download installer (Universal/.JAR)" button.
    + It should start downloading file named `fabric-installer-x.xx.x.jar` with `x`s being replaced by the latest build number of the installer.
    + Find the `.jar` file just downladed and double click on it to open.
    + Select these options for the installation of fabric version:
      + The selected tab at the top left should be `Client`
      + The `Minecraft Version:` dropdown should be `1.19.2`
      + The `Loader Version:` dropdown should be `0.14.9` (other versions have yet to be comfirmed as compatible, you may test other versions on your own but expect bugs/crashes.)
      + The `Select Install Location` field should be left as the default included path (unless you know what you're doing).
      + The `Create profile` box should be ticked

    Once all of this is setup like indicated click on the `Install` button and you should be done with this step.

2. Install the modpack mods

    First off to install the mods you will need to locate your `.minecraft` folder which contains all the important files minecraft uses to run.
  
    + Download modpack zip file: <a href="https://github.com/Noapoleon/noa_qol_modpack/blob/master/noa_qol_modpack_v0.0.zip?raw=true" title="modpackDownloadLink">noa_qol_modpack_v0.0.zip</a>
    + Open your Minecraft launcher and navigate to the `Installations` tab at the top.
    + You should have at the very least a `Latest release` installation profile already displayed in the list of installations. Hover over it and to the right you will see a folder icon. Click on it. This will open a file explorer window in your `.minecraft` folder.
    + Try to find a `mods` folder. If there's is none, create it with this exact spelling: `mods`. 
    + If you already have mods inside it is recommended to remove them and save them somewhere as they might interfere with the modpack's mod and cause crashes.
    + Open a new explorer window (shortcut win+e) and navigate to your download location for the modpack (by default the `Downloads` folder).
    + Drag or copy the modpack's zip to the `mods` folder. Right click on the zip folder and using your archive manager software of choice (winrar for me) extract all the `.jar` files directly into the `mods` folder. _**This is important: They have to be directly inside the `mods` folder not in another folder!**_

    If you downloaded the individual `.jar` mod files the process is the same. However make sure you downloaded the mods marked as **depencencies** as some other mods **require** them and won't work properly or even worse, completely halt start up, if they are not present.

3. Launch the game with Noa's QoL Modpack

    At this point everything should be ready for starting the game with the modpack.
  
    + Open the Minecraft Launcher. ( Close it and reopen it if it was already open )
    + At the left of the big green `PLAY` button make sure `fabric-loader-1.19.2` is selected and then click `PLAY`.
    _if the `fabric-loader-1.19.2` option is not available in the dropdown follow this: `Installations` tab (top left) -> `New installation` button -> `Version` dropdown and select `release fabric-0.14.9-1.19.2` or something similar._ _If you still don't see that I recommend you google `Fabric installation not showing minecraft launcher` and research solutions_
    + The game should have started by now and when it's loaded you can enjoy your enhanced vanilla experience :). Now if it didn't, first off sorry for the frustration this brought, and second you can navigate to the top of this repository and leave an issue report [here](https://github.com/Noapoleon/noa_qol_modpack/issues) or use one of my [contacts](#contact).

    **Important Note:** I also have an [Additional Setup](#additional-setup) section where you can find some shaders I use and most importantly a guide that will show you the exact way I configured all those modpacks for a better experience as they are not perfect by default.

## Mod List and Details

ill do it later this afternoon

## Additional Setup

**Shaders:** If your pc is powerful enough to support shaders you might want to look into these two shaders, favorites of mine:
+ [SEUS PTGI Rtx Shaders](https://www.sonicether.com/seus/#:~:text=SEUS%20PTGI%20is%20an%20experimental,also%20includes%20ray%20traced%20reflections.)
+ [Sildur's Vibrant Shaders](https://sildurs-shaders.github.io/) (this one has multiple quality versions for less powerful configs)
    There are plenty of guides online on how to install shaders with sodium if you need help btw.
    
**My mod config:** by default there are keybinds conflict and the UI settings for certain mods are not ideal in my opinion, that's why I've included [my config zipped folder](https://github.com/Noapoleon/noa_qol_modpack/blob/master/config.zip?raw=true). This zip file is meant to be placed in your `config` folder in your `.minecraft` folder (we saw how to find this folder in the installation guide above) and then extracted using the `Extract Here` option. You can then delete the zip file.

## Sample Images
![img](/screenshots/ss1.png)
![img](/screenshots/ss2.png)

## Download Links
Here you can find the modpack zip file as well as all the individual official mods download links for those who won't trust a random stranger on the internet for providing them with jar files ( and I don't blame you ;) ).

+ **Noa's QoL Modpack:** <a href="https://github.com/Noapoleon/noa_qol_modpack/blob/master/noa_qol_modpack_v0.0.zip?raw=true" title="modpackDownloadLink">noa_qol_modpack_v0.0.zip</a>
+ individual mods links coming...

## Credits
ill find the credits soon enough. nobody's gonna download this rn anyway

## Contact
+ **Discord:** `Noapoleon#0843`
+ **Discord id (in case I change username or tag):** `228188623059681282` 
