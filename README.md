<p align="center"> <img width="1000px" src="http://forgottenhope.warumdarum.de/images/news/124%20-%20FH2mod.jpg"/> </p>

##  Forgotten Hope 2 Matt Backer's Texture Pack


[![Build and release](https://github.com/Forgotten-Hope-2-community-addons/fh2-matt-bakers-texture-pack/actions/workflows/build-and-release.yml/badge.svg)](https://github.com/Forgotten-Hope-2-community-addons/fh2-matt-bakers-texture-pack/actions/workflows/build-and-release.yml)

This is a texture pack for the [Forgotten Hope 2][website] mod for Battlefield 2. This 
texture pack replaces some of the vehicles' textures (skins) in the game with improved 
and more historically accurate ones.

Some of these textures have already being inlcuded in the main mod, thanks to Matt.


Original add-on website: http://fhpubforum.warumdarum.de/index.php?topic=19770.0


**Disclaimer: this texture pack is not endorsed by the Forgotten Hope 2 team. Use at your own risk.**

### Installation

1. Download the latest version of the texture pack from the [releases page](https://github.com/Forgotten-Hope-2-community-addons/fh2-matt-bakers-texture-pack/releases).

2. Extract the package to any location.

3. Copy `MattBakersTexturePack.zip` and `ClientArchives.con` to your Forgotten Hope 2 mod folder. The path should look like this: `C:\Program Files (x86)\Forgotten Hope 2\mods\fh2`. **DO NOT EXTRACT THAT ZIP FILE**.

4. When prompted, choose to replace the existing files.

This will replace any previous version of the texture pack already installed. Be aware that the `ClientArchives.con` will be replaced too, so any changes made to it will be lost, for example, if you load additional custom content such as this texture pack. If you want to keep your changes, you can merge the two files manually.

```
rem === Custom Archives === 
fileManager.mountArchive MattBakersTexturePack.zip Objects
```

If you are also using the **uncensored** texture pack, load it after this pack in the `ClientArchives.con` file:

```
rem === Custom Archives ===
fileManager.mountArchive MattBakersTexturePack.zip Objects
fileManager.mountArchive menu_uncensored.zip Menu
fileManager.mountArchive objects_uncensored.zip Objects
```

### Uninstall


#### Manual

To uninstall this texture pack, just remove or comment the line added to the `ClientArchives.con` file. To comment a line, prefix it with `rem`:

```
rem fileManager.mountArchive MattBakersTexturePack Objects
```

To completely remove the texture pack, remove the `MattBakersTexturePack.zip` file from your Forgotten Hope 2 mod folder.


#### Using the launcher

**Note: any modified content will be reset to default**

Go to "Options" → "Update / Repair" in the FH2 Launcher and hit "Repair".


### Contributors

This project aims to keep community add-ons like this centralized and alive, improving its 
distribution chain and making it easier for users to install and update. If you want to
contribute to this project, please open a pull request and contact me.

Being said so, I do not own the content of this texture pack, I just made its versioning better.
I've contacted the original authors, and they have given me permission to distribute their work.
Although not directly implicated, this texture pack is based on the work of several people.

- Matt_Baker - original author of the textures.
- Forgotten Hope 2 team - base textures.
- SgtAlex - maintains this repo and its code.

### License

This texture pack is licensed under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License. To view a copy of this license, visit http://creativecommons.org/licenses/by-nc-sa/4.0/ or send a letter to Creative Commons, PO Box 1866, Mountain View, CA 94042, USA.

The code in this repository is licensed under the GNU General Public License v3.0. See [LICENSE](LICENSE) for more information.

**The use of these textures are forbidden outside the context of the Forgotten Hope 2 mod.**


[website]: https://www.moddb.com/mods/forgotten-hope-2/
[86a]: https://en.wikipedia.org/wiki/Strafgesetzbuch_section_86a

