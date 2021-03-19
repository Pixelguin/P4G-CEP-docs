# Upgrade Instructions

> To upgrade from a version older than 5.0, follow the directions in [Getting Started](https://github.com/Pixelguin/P4G-CEP-docs/blob/master/docs/02_getting_started.md).

## Download Version 5.1.2 Upgrade

Download the **Version 5.x to 5.1.2 Upgrade** package for P4G CEP now if you haven't already.

* [Download from **GameBanana**](https://gamebanana.com/gamefiles/12882)
* [Download from **Nexus Mods**](https://www.nexusmods.com/persona4golden/mods/11?tab=files)

## Upgrade to Version 5.1.2

### Prepare for Upgrading Packages
* Open your `P4G Mods\Tools\Aemulus Package Manager` folder and launch **Aemulus**.
* Look at the *Version* value of the *P4G Community Enhancement Pack* package to determine your current version of P4G CEP.
* Unzip your upgrade download and open the appropriate `Aemulus Packages\Upgrade from [5.x]` folder.

![](img/upgrade/aemulus_packages.png)

### Delete Inoue Bustups
> If you don't have Inoue Bustups installed, skip this step.

The *Inoue Bustups* mod has been causing softlocks for some users, so it has been removed from P4G CEP.

* Right-click **Inoue Bustups** in the Aemulus package grid and select **Delete Package**. 

### Upgrade Packages

* Click the **Home** tab at the top of the `Aemulus Packages` folder window.
* Click the button labelled **Select all** to select all of the folders in the window.

![](img/upgrade/select_all.png)

* Drag all of the folders at once onto the ➕ **Add Package** button in Aemulus, then release the mouse button to drop them.

![](img/upgrade/add_package.png)

> If you're having trouble dragging all of the folders at once, you can also drag and drop them one at a time.

* Aemulus will automatically refresh the window and upgrade your packages. All you need to do now is click **Build** again.

### Upgrade Backup File

* Open your `P4G Mods\Backups\Aemulus Package Manager` folder.
* In your upgrade folder, open the `Backups\Aemulus Package Manager` folder.
* Replace the **Persona4GoldenPackages.xml** file in your `P4G Mods\Backups\Aemulus Package Manager` folder with the one in your upgrade folder.
