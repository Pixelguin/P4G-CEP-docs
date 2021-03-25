# Upgrade Instructions

> To upgrade from a version older than 5.0, follow the directions in [Getting Started](https://github.com/Pixelguin/P4G-CEP-docs/blob/master/docs/02_getting_started.md).

## Download Version 5.2 Upgrade

Download the **Version 5.x to 5.2 Upgrade** package for P4G CEP now if you haven't already.

* [Download from **GameBanana**](https://gamebanana.com/gamefiles/12882)
* [Download from **Nexus Mods**](https://www.nexusmods.com/persona4golden/mods/11?tab=files)

## Upgrade to Version 5.2

### Verify Game Files

We need to download a clean copy of **data_e.cpk** from the Steam servers.

- Open Steam and go to your **Library**.
- Select **Persona 4 Golden** in your list of games.
- Right-click it and select **Properties**.

![](img/03/steam_properties.png)

- In the Properties window, select **Local Files**.
- Click **Verify integrity of game files...** and wait for the validation process to complete.
- Click **OK** to close the *Validating Steam files* window. 

![](img/03/verify_files.png)


### Back Up Custom Packages

> If you don't have any custom packages, skip this step.

Version 5.2 completely replaces the `Aemulus Package Manager` folder, so you will need to temporarily back up any custom packages that are not part of P4G CEP.

* Open your `P4G Mods\Tools\Aemulus Package Manager\Packages\Persona 4 Golden` folder.
* Move any custom packages you have into your `P4G Mods\Backups` folder.

### Upgrade Aemulus Folder

* When you are ready, **delete** your `P4G Mods\Tools\Aemulus Package Manager` folder.
* Unzip your upgrade download and locate the `Aemulus Package Manager` folder. Move it into your `P4G Mods\Tools` folder.

### Upgrade Backup File

* Open your `P4G Mods\Backups\Aemulus Package Manager` folder.
* In your upgrade folder, open the `Backups\Aemulus Package Manager` folder.
* Replace the **Persona4GoldenPackages.xml** file in your `P4G Mods\Backups\Aemulus Package Manager` folder with the one in your upgrade folder.

### Set Up Aemulus

* You will need to perform the steps in [Aemulus Setup](05_aemulus_setup.md) again, including setting up the Config window.
* When you have finished setting everything up, click 🔨 **Build** to upgrade your package loadout.

> If you backed up any custom packages, you can restore them by following the instructions for [Adding Custom Packages to Aemulus](extras.md#add-custom-packages-to-aemulus).
