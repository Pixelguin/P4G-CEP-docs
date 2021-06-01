# Extras
## Add Custom Packages to Aemulus

### Compatibility
Most **Aemulus-compatible** mods will work with P4G CEP.

Look for the Aemulus logo in the bottom-right corner:

![](img/extras/aemulus_logo.png)

Aemulus will also automatically convert any package created for the **Mod Compendium** program.

### Tips

- A package with higher priority in Aemulus will override packages with lower priority in the event of a file conflict that can't be merged.
- A mod labelled **Work in Progress** (traffic cone on GameBanana) is incomplete and will have unexpected behavior.

### 1-Click Installation
Many mods on GameBanana support **1-click installation** with Aemulus. Just click the **Aemulus Package Manager** button on the mod page to automatically download and install the mod.

### Manual Installation
Mods that don't support 1-click installation need to be manually installed.

#### Locate Package Folder
- Download the mod you would like to add to P4G CEP.
- Unzip the downloaded mod and locate the **package folder**. The package folder has a file in it named **Package.xml**.

#### Add to Aemulus
- Make sure the dropdown in the top left says **Persona 4 Golden**.
- Drag the package folder over the ➕ **New Package** button and release.
- There should now be a new Aemulus package at the bottom of the grid.

> You can also manually add the package folder to your `P4G Mods\Tools\Aemulus Package Manager\Packages\Persona 4 Golden` folder.

### Organize and Enable
- You can drag packages in Aemulus to organize them and change their build priority.
- Once you've decided on a position, **enable** the package by checking its box.
- Make sure to click 🔨 **Build**  when you're all done!

## Create Steam Shortcut

You can create a shortcut in Steam that calls Reloaded II to launch P4G and inject mods. This is necessary if you want to launch the game through Steam's Big Picture mode.

### Add Reloaded II Shortcut to Steam
- Open Steam. At the top of the Steam window, select **Games** and click **Add a Non-Steam Game to My Library...** to open the *Add a Game* window.
- In the *Add a Game* window, click **Browse...**
- In the file manager window that opens, navigate to your `P4G Mods\.Reloaded II` folder and select **Reloaded-II.exe**.
- Click **Open**, then **Add Selected Programs** in the *Add a Game* window to add Reloaded II to your Steam library.

### Configure Shortcut for P4G
- Right-click **Reloaded II** in your Steam library and select **Properties** to open the *Properties* window.
- In the **Launch Options** section, type `--launch "C:\Program Files (x86)\Steam\steamapps\common\Persona 4 Golden\P4G.exe"`.

> Replace the path to **P4G.exe** with your own file path if you do not have P4G installed in this location. Make sure to keep the quotation marks on both sides!

- Close the *Properties* window. You now have a shortcut to launch P4G with mods that works the same way as clicking *Launch Application* in Reloaded II or clicking *Launch* in Aemulus.

## Install High Quality Japanese Audio
The Japanese voice line files that P4G ships with are very compressed. Mod creator Bakemono has ported high-quality Japanese audio files from the PS Vita version of P4G, and they can be downloaded separately.

You will need an additional 2 GB of free space on your computer (3.5 GB during unpacking).

### Back Up Original File
- Open your `Persona 4 Golden\SND` folder.
- Move (not Copy) the file **ROOT.xwb** to your `P4G Mods\Backups\Game Files` folder.

### Install New File
- Download the **HQ Japanese Audio** add-on.
  - [Download from Google Drive](https://drive.google.com/file/d/1SuOuqcL6qP3XiiuPp0TGtJVT2Roh7wQh/view)
  - [Download from Nexus Mods](https://www.nexusmods.com/persona4golden/mods/11?tab=files)
- Unzip the download and move the **ROOT.xwb** file there to your `Persona 4 Golden\SND` folder.
 
## Remove 60 FPS Cap in Fullscreen
P4G is normally capped at 60 FPS in Fullscreen mode, but the cap can be removed with a simple tweak to the executable.

* Open your `Persona 4 Golden` folder.
* Right-click **P4G.exe** and select **Properties**.
* In the *Properties* window, select the **Compatibility** tab.
* Under *Settings*, check the box labelled **Disable screen optimizations**.
* Click **Apply**, then **OK** to close the *Properties* window.
