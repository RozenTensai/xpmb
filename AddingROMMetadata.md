# Introduction #

Here I will try to explain how to add some ROMs, and then images and information to them so XPMB can show it to you when exploring the different games submenus (currently supported and implemented are NES and GBA ones.

# Adding ROMs #
If you already tried to open the mentioned submenus, they create the required directory to put ROMs in a directory under /sdcard, if they're are not there already, you must create them. GBA for the _Game Boy Advance_ ROMs and NES for the _Nintendo Entertainment System_ ROMs.

Now you can put any ROM compressed as a .zip or as a raw .gba file

# Adding Metadata #
Now you need to create a directory named **Resources** under the desired ROM directory.
Now you need the full name that XPMB shows to you (for example: _Sonic Advance_, note that names that contains special characters such as '/' or ':' can not be used at this moment)
After you have the full name, you can continue adding metadata to the ROM.

## Adding Game Cover ##
The picture must be in JPEG format, starting with the full name, and ending with the prefix '-CV' with an .jpg extension.
<br />Example: _Sonic Advance-CV.jpg_

The picture can be any size, but a resolution of 256x256 is recommended.

## Adding Game Background ##
If you have any art that you want to use when selecting a ROM (like in PSP's Game selection menu) then the procedure is the same as game cover, but the prefix is '-BG' and the recommended resolution is the maximum the XPERIA Play can do: 854x480
<br />Example: _Sonic Advance-BG.jpg_

## Adding Game summary (currently unused) ##
These metadata must go in a file named **META\_DESC** (yes, without extension), one summary per line, starting with the game full name, followed with a '=' and then the summary, for example:

_/sdcard/GBA/Resources/META\_DESC_
```inf

Final Fantasy Tactics Advance=Square first Game Boy Advance title.
Advance Wars=Turn-based war game strategy comes to the portable screens of the Game Boy Advance.
Pokemon - Edicion Esmeralda=Brave trainers once again face off against wily rivals and hunt for rare, wild pocket monsters in this quest to put a stop to the destructive expansion of Team Magma and Team Aqua..
Final Fantasy VI Advance=Following the story of Terra, players who journey into the portable world of Final Fantasy VI Advance will learn to conjure and control creatures called espers by harnessing the power of magic..
Summon Night - Swordcraft Story=Based on the Japanese original, this console-style role-playing game ventures Stateside via Atlus U.S.A..
```