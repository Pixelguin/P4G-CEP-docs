# Troubleshooting

### My issue isn't listed here.
The fastest way to get support is on [**Discord**](https://discord.gg/aZkkqnw).

---


## Reloaded II

### I can't find Reloaded-II.exe.
Your antivirus software probably deleted it.

* Add an exception in your antivirus for your `P4G Mods\.Reloaded II` folder.
* Redownload Reloaded-II.exe (either redownload P4G CEP or ask on Discord).

----

### Reloaded II is asking me to download and install .NET/Visual C++ Redist.

* Either follow the directions Reloaded II gives you or run **Install_Prerequisites.exe** in your `P4G Mods\Setup` folder.

----

### Reloaded II can't launch P4G.

* If you're getting a "Failed to load Reloaded II" or "Unable to initialize SteamAPI" error, make sure Steam is running. 
* Make sure your P4G.exe path is correct. It's a common mistake to forget to include `P4G.exe` at the end of the file path.
* Make sure you didn't put the `P4G Mods` folder in your OneDrive folder or any other location that synchronizes files with the cloud.

----

### Reloaded II isn't reading the right Apps/Mods folders.

Reloaded II keeps a file in AppData (ReloadedII.json) that tracks a single folder each for Apps, Mods, and Plugins. This is necessary for its functionality, but it means **you can only have one Reloaded II folder on your computer**.

* To reset Reloaded II's folder paths, delete every Reloaded II folder on your computer except the one you want to keep, then launch the remaining **Reloaded-II.exe**.

----

## Aemulus

### I can't find AemulusPackageManager.exe.
Your antivirus software probably deleted it.

* Add an exception in your antivirus for your `P4G Mods\Tools\Aemulus Package Manager` folder.
* Redownload AemulusPackageManager.exe (either redownload P4G CEP or ask on [Discord](https://discord.gg/aZkkqnw)).

----

### I want to reset the order of my packages.

We're working on a new way to do this. For now, ask on Discord and we'll help you out.

----

## Persona 4 Golden

### P4G won't launch/P4G immediately crashes.

* Launch P4G directly through Steam to see if it works without mods.
* If you are using custom packages with Aemulus, make sure they are correctly formatted.
* Check for any loose files in your `Persona 4 Golden\mods` folder.
* Wait until *after* the game launches to start RivaTuner Statistics Server or MSI Afterburner.
* Disable any "game boost" software (Razer Cortex, MSI Dragon Center) and try again.
----

### The game crashes during the first battle after awakening Izanagi.

* Play without mods (launch directly from Steam) until you finish the tutorial battles.
* Save and close the game. You should now be able to play the game modded without any more crashes.

----

### The game softlocks during a Social Link event with Rise and I can't progress.
* Make sure you're using the latest release of P4G CEP.
* If you're using v5.1.1+ and still encountering this issue, join the [Discord server](https://discord.gg/aZkkqnw) and let us know. We know it's related to the *Inoue Bustups* mod, but we're trying to figure out what's causing the issue for different people.

----

### The music stops playing when I enter a battle.
* Buy the game please :)

----

### Cutscenes are playing slowly/being skipped entirely.
There are a few possible fixes for this issue.

#### Disable Additional Reloaded II Programs
This issue most commonly occurs when Reloaded II runs out of memory (this is unrelated to how much RAM your system has).
* Disable any additional programs you have added to your Reloaded II folder, such as *EXP Share*.
 
#### Use Low Cutscene Quality
* Launch P4G. 
* Open Config from the main menu. 
* Go to the **Graphics** tab.
* Set the **Cutscene Quality** setting to **Low**.

> If you are not using the *Config Clarity* mod, this setting will be called **Animation Quality**.

#### Install Windows Media Player
Atlus recommends installing **Windows Media Player** if you're  having trouble with cutscene playback.

* Open the Windows **Start Menu**.
* Type **"apps and features"** and press Enter to open the Apps and features page in Settings.
* Select **optional features** below the second "Apps and features" header.
* Select **add a feature** at the top of the Optional features page.
* Type **"Windows Media Player"** into the search bar. If Windows Media player is not installed, it should appear in the list below.
* Check the box for **Windows Media Player**, then click **Install (1)** at the bottom of the window.
* Wait for Windows to finish downloading and installing Windows Media Player, then restart your computer.
>If you are using **Windows 10 N** or **Windows 10 KN**, search for and install the **Media Feature Pack** as well.

#### Force Dedicated GPU
If you have a laptop with both an Nvidia graphics card and Intel integrated graphics, Windows might be choosing the weak Intel graphics automatically to save power. 

* Right-click on the Desktop and select **NVIDIA Control Panel**.
* Select **Manage 3D settings** on the left panel.
* Select the **Program Settings** tab.
* Click **Add** and select **Persona 4 Golden** from the list of applications.
* From the dropdown menu under the application, select **High-performance NVIDIA processor**.
* Click **Apply**.

*These instructions were modified from content on [**PC Gaming Wiki**](https://www.pcgamingwiki.com/wiki/Persona_4_Golden#Very_low_fps_on_decent_specs_PC.2C_automatically_skipped_cutscenes) and are licensed under [CC BY-NC-SA 3.0](https://creativecommons.org/licenses/by-nc-sa/3.0).*

----

### This motion blur sucks!

The higher the game's framerate is, the more the motion blur is reduced.

> This trick will only work if your computer can run the game at a high framerate.

* Launch P4G.
* Open **Config** from the main menu.
* Go to the **Graphics** tab.
* Set the **Vsync** setting to **Off**.

If you can get 100+ FPS, the motion blur effect will be seriously reduced.

----

### My save data disappeared.
Don't panic! This is a nasty bug that’s related to how P4G and the Steam cloud exchange information, but **you can safely get your save data back**.

#### Launch P4G Without Mods
- Restart your computer.
- Run P4G without any mods by launching the game directly through Steam. **Make sure you are not in offline mode!**
> If your save data has reappeared, you're all done.

#### Get Steam ID
- Close P4G.
- Open steamidfinder.com and paste a link to your Steam profile to find your Steam ID.
We just want the big number at the end of the **steamid3** value.
  - For example, my steamid3 value shows `[U:1:103594589]`, so my Steam ID is **103594589**.

#### Back Up Save Data
- Open the following folder on your computer:`<Steam-folder>\userdata\<Steam-ID>\1113000\`
- Copy the `remote` folder to your `P4G Mods\Backups\Save Data` folder.

#### Save Over Save Data
- Launch P4G (with or without mods, it doesn't matter) and start a New Game. 
-	Skip through the opening scenes (double-tap Z on your keyboard) until you reach the first save point in Central Shopping District.
- Save the game on **all 16 save slots**.
> Don’t worry, you aren’t deleting your actual save data forever because you made a backup!

#### Restore Save Data
- Close P4G.
- Delete the `remote` folder in `<Steam-folder\userdata\Steam-ID\1113000`.
- Copy the `remote` folder in `P4G Mods\Backups\Save Data` into the `1113000` folder.

After following all of these steps, your save data should work again.

*Unfortunately, we don’t know very much about why this bug happens or how to prevent it from happening. If you can reliably reproduce this bug or have found a better solution, please get in touch with us on [**Discord**](https://discord.gg/aZkkqnw).*
