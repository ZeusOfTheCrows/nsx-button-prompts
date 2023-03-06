# Blasphemous

**[link to release](https://github.com/ZeusOfTheCrows/nsx-button-prompts/releases/tag/blasphemous)**

### to install (simple)

* locate your blasphemous folder
	* (by default: `C:\Program Files (x86)\Steam\steamapps\common\Blasphemous`)
* (optionally) back up your vanilla `data.unity3d` file
	* change the file extension or move to another folder, else the game will load slowly
* copy `data.unity3d` to your `Blasphemous_Data\`

### to install (for merging with other mods)

* follow the *import* section of [this guide](https://github.com/RedFurryDemon/BlasphemousModdingNotes/blob/master/notes/Graphics.md)
* in step 4, select the texture `all_platform_buttons`
* load the included `all_platform_buttons-resources.assets-884.png`
	* optionally, compress as [explained here](https://zenhax.com/viewtopic.php?t=14147)
		* (`file` →`compress`, open file, select compression in bottom panes, save file as)
		* on linux/wine, selecting lz4 crashes, but lzma is okay. i don't know about windows
* install as above

**/!\ game may load slowly first launch after installation - i'm not quite sure
why this is, but it's fine after that**

---

## dev miscellany

* used tools:
	* [uabe](https://github.com/SeriousCache/UABE/releases)
		* i do not vouch for the safety of this programme. virustotal marks it
			[as a trojan](https://github.com/SeriousCache/UABE/issues/479).
			proceed with caution
	* aseprite
		* a free alternative is pixelorama
		* but paint.net or gimp should do fine

* edited files:
	* data.unity3d
		* └ all_platform_buttons-resources.assets-884

* possibly pertinent, but don't seem to be used:
	* data.unity3d
		* ├ xbox_a-sharedassets1.assets-153
		* ├ xbox_b-sharedassets1.assets-36
		* ├ xbox_x-sharedassets1.assets-167
		* ├ xbox_y-sharedassets1.assets-79
		* └ ps_buttons_spritesheet-resources.assets-138

* useful font
	* https://www.splintered.co.uk/experiments/1135/
	* https://fontstruct.com/fontstructions/show/2138043/blasphemous-1
* great instructional information here:
	* https://github.com/RedFurryDemon/BlasphemousModdingNotes/blob/master/notes/Graphics.md
