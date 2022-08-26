# Castlevania: Lords of Shadow

**[link to release](https://github.com/ZeusOfTheCrows/nsx-button-prompts/releases/tag/cv-los)**

### to install:

* (optionally) backup/rename your vanilla `Data00.dat`
* copy `Data00.dat` to your game directory, overwriting existing file


a backup of the original file is included for convenient uninstallation, but one can safely
ignore it.

## dev miscellany

### to unpack .dat files:

* download [quickBMS from here](http://aluigi.altervista.org/quickbms.htm)
* place the folder inside the LoS folder (not necessary, but it makes things easier)
* place the included .bms script (plaintext file) in the LoS folder ([source](https://forum.xentax.com/viewtopic.php?f=10&t=5102&start=15#p87025))
* open a cmd prompt, and run `cd C:\Program Files (x86)\Steam\steamapps\common\CastlevaniaLoS\unpacked`
	* (or wherever your game install location is)
* run `quickbms\quickbms.exe castlevania.bms Data00.dat unpacked\`
* edit the files you wish inside the `.\unpacked\` folder
* run `quickbms\quickbms.exe -w -r castlevania.bms Data00.dat unpacked\` to repack the .dat file

**if only editing this mod, it is not necessary to unpack all files, repacking the included files is sufficient**

### other useful info

* it's easier to export from gimp to .png, and then use (e.g.) paint.net to convert to dds
* texture compression is DXT5
* ~~font is bradley gratis~~ not used
* modified files are (i don't know which files influence what):
	* `.\2d\hud\dds\hudpcmg.alpha.dds`
	* `.\2d\fonts\dds\arial20.alpha.dds`
	* `.\2d\fonts\dds\bradley47.alpha.dds`
* gimp filters to recolour buttons are as follows:
	* A - green → red: hue -75, light +0, sat +0
	* B - red → yellow: hue +50, light +20, sat +0
	* Y - yellow → green: hue +25, light -40, sat -35