
![Latest Release](https://img.shields.io/github/v/release/SpellholdStudios/generalized_biffing?include_prereleases&color=darkred)<a name="top" id="top"> </a>
![Platform](https://img.shields.io/static/v1?label=platform&message=windows%20%7C%20Mac%20%7C%20linux&color=informational)
![Language](https://img.shields.io/static/v1?label=language&message=English%20%7C%20French%20%7C%20Italian&color=limegreen)


<div align="center"><h1>Generalized Biffing</h1>

<h3>A Spellhold Studios mod for Infinity Engine games<h3>

</div><br />


**Author:** the bigg (Valerio Bigiani)  
**Mod Website and Forum:** <a href="http://www.shsforums.net/topic/39238-generalized-biffing/">Generalized Biffing</a>  


[Read the mod's readme](http://spellholdstudios.github.io/readmes/generalized_biffing-readme-english.html).

[Download the mod at Spellhold Studios](http://www.shsforums.net/files/file/741-generalized-biffing/).<br>

&nbsp;

<div align="center">
<a href="#intro">Overview</a> &#8226; <a href="#compat">Compatibility</a> &#8226; <a href="#installation">Installation</a> &#8226; <a href="#components">Components</a> &#8226; <a href="#credits">Credits and Acknowledgements</a> &#8226; <a href="#versions">Version History</a></br>
</div>

<hr>


## <a name="intro" id="intro"></a>Overview

This WeiDU mod allows you to biff the content of the override folder for improved performance, that means the files are converted into the BIF file format and moved into the data folder. This works natively under OSX and Linux (if you use the correct executable) and is compatible with the common WeiDU stack un-install operation. The game thereby loads much faster again and the performance is running pretty smoothly without jerking.

**Note:** Recent user reports have indicated that Generalized Biffing is unnecessary for Enhanced Edition games.

<div align="right"><a href="#top">Back to top</a></div>


<hr>


## <a name="compat" id="compat"></a>Compatibility

This mod is designed to work on all Infinity Engine games.

Generalized Biffing is a WeiDU mod, and therefore should be compatible with all WeiDU mods. It is . If you encounter any bugs, please <a href="http://www.shsforums.net/topic/39238-generalized-biffing/">report them on the forum</a>!

<div align="right"><a href="#top">Back to top</a></div>


<hr>


## <a name="installation" id="installation"></a>Installation

#### Notes

*If you've previously installed the mod, remove it before extracting the new version. To do this, run **`setup-generalized_biffing.exe`**, un-install all previously installed components and delete the :file_folder: **generalized_biffing** folder.*

*When installing or un-installing, **do not close the DOS window** by clicking on the **X** button! Instead, press the **Enter** key whenever instructed to do so.*

*__Disable any antivirus__ or other memory-resident software before installing this or any other mod. Some (particularly avast and Norton!) have a tendency to report false positives with mod activity, resulting in failed installs.*

## 

#### Windows

Generalized Biffing for Windows is distributed as an extractable compressed archive and includes a WeiDU installer.

Extract the contents of the mod archive into the folder of the game you wish to modify (*the folder which contains the "CHITIN.KEY" file*), using <a href="http://www.7-zip.org/download.html">7zip</a>, <a href="http://www.rarlab.com/download.htm">WinRAR</a>, or another file compression utility that handles .zip files. On successful extraction, there should be a :file_folder: generalized_biffing folder and a setup-generalized_biffing.exe file in your game folder. To install, simply double-click **`setup-generalized_biffing.exe`** and follow the instructions on screen.

Run **`setup-generalized_biffing.exe`** in your game folder to reinstall, un-install or otherwise change the components settings.

## 

#### Mac OS X

Generalized Biffing for Mac OS X is distributed is distributed in the same compressed archive and includes a WeiDU installer.

First, extract the files from the archive into your game directory. On successful extraction, there should be a :file_folder: generalized_biffing folder, setup-generalized_biffing and setup-generalized_biffing.command files in your game folder. To install, simply double-click **`setup-generalized_biffing.command`** and follow the instructions on screen.

Run **`setup-generalized_biffing.command`** in your game folder to reinstall, un-install or otherwise change the components settings.

## 

#### Linux

Generalized Biffing for Linux is distributed in the same archive and does not include a WeiDU installer.

Extract the contents of the mod to the folder of the game you wish to modify.

Download the latest version of WeiDU for Linux from <a href="https://github.com/WeiDUorg/weidu/releases">WeiDU.org</a> and copy WeiDU and WeInstall to /usr/bin. Following that, open a terminal, **cd** to your game installation directory, run tolower and answer 'Y' to both queries. You can avoid running the second option (linux.ini) if you've already ran it once in the same directory. To save time, the archive is already tolowered, so there's no need to run the first option (lowercasing file names) either if you've extracted only this mod since the last time you lowercased file names. If you're unsure, running tolower and choosing both options is the safe bet.

To install, run **`WeInstall setup-generalized_biffing`** in your game folder. Then run **`wine BGMain.exe`** and start playing.

## 

#### Note for Complete Un-installation

In addition to the methods above for removing individual components, you can completely un-install the mod using **`setup-generalized_biffing --uninstall`** at the command line to remove all components without wading through prompts.</br>
<div align="right"><a href="#top">Back to top</a></div>


<hr>


## <a name="components" id="components"></a>Components

The installer includes the following components. The number of each is the component *DESIGNATED* number which gives it a fixed install position, lets other components and mods detect it and allows automated installers to specify component choices.<br /><br />


#### 0. Biff only .wav, .tis and .bam files

This component might be enough for installations with few mods (recommended by The Bigg and other "*Small World Dudes*").</br>

## 

#### 1. Biff all files

This component is recommended by the "*Big World Dudes*" (practically essential for installations with many mods).

<div align="right"><a href="#top">Back to top</a></div>


<hr>


## <a name="credits" id="credits"></a>Credits and Acknowledgements

**Original author:** <a href="http://www.shsforums.net/user/2083-the bigg/">the bigg</a>  

#### Special Acknowledgements to:

- <a href="http://www.spellholdstudios.net/">Spellhold Studios</a> team for hosting the mod (<a href="http://www.shsforums.net">Forums</a>).
- French translation: Isaya.
- Argent77: BG:EE compatibility patch.
- Everyone else from the <a href="http://gibberlings3.net/forums/">The Gibberlings Three</a>, <a href="http://www.shsforums.net/">Spellhold Studios</a> forums, and the other Infinity Engine gaming and modding communities who offered their help and support.

## 

#### Programs/tools used in creation:

- <a href="https://github.com/WeiDUorg/weidu/releases"><acronym title="Weimer Dialogue Utility">WeiDU</acronym></a>, by Wes Weimer, the bigg and Wisp.
- <a href="https://gibberlings3.github.io/iesdp/"><acronym title="Infinity Engine Structures Description Project">IESDP</acronym></a>, maintained by igi and lynx.
- <a href="http://notepad-plus-plus.org/">Notepad++</a>, by the Notepad++ team, Don Ho, and the spellcheck plug-in.
- <a href="http://www.shsforums.net/files/file/1048-weidu-highlighter-for-notepad/">WeiDU Notepad++ Highlighters </a>, by Argent77.

## 

#### Copyright Information

###### Generalized Biffing is not developed, supported, or endorsed by BioWare&trade; or Interplay/BlackIsle, Overhaul, Beamdog or the Wizards of the Coast. It was developed by the bigg, based on material from the game Baldur's Gate II and its expansion.
###### All mod content is &copy;the bigg.
###### Baldur's Gate II: Shadows of Amn and Baldur's Gate II: Throne of Bhaal &copy; TSR, Inc. The BioWare Infinity Engine is &copy; BioWare Corp. All other trademarks and copyrights are property of their respective owners.

###### This mod was created to be freely enjoyed by all Baldur's Gate II players, and its content is free of rights. However, it should not be sold, published, compiled or redistributed in any form without the consent of the author.
###### Please note that any and all redistribution and/or hosting of this mod is prohibited without permission from the author.

###### If there are any copyright issues or this statement needs revision, then please contact me and advise me what to do about it. Most notably, if you see any artwork in this mod that might conflict with Copyright rules, please let me know as soon as possible, and I will remove the conflicting content immediately.

###### The modding community for the Infinity Engine has been going strong for more than 10 years now, and is the culmination of thousands of unpaid modding hours by fellow fans of the game. Modders produce their best work and players get the best, well-supported mods when we all work together.
###### There are two big ways to upset this harmony. One is to claim someone else's work as your own. The second is to host and redistribute a mod without permission from the author(s).
###### Be kind to your fellow players and modders. Don't do either.</br></br>
<div align="right"><a href="#top">Back to top</a></div>


<hr>


## <a name="versions" id="versions"></a>Version History

#### Version 2.3 (February 24, 2020)

- Added *generalized_biffing.ini* metadata file to support AL|EN's "Project Infinity".
- Included BWP Fixpack (<a href="http://www.shsforums.net/topic/56752-the-official-bwp-fixpack-thread/?p=580487">Argent77's BG:EE compatibility patch</a>).
- Added `DESIGNATED` numbers and "*generalized_biffing_min*" and "*generalized_biffing_all_files*" component `LABELS`.
- Added `README` command in tp2.
- Wrote a new *generalized_biffing-readme-english.html* readme file.
- This version includes all original patches.
- Updated <acronym title="Weimer Dialogue Utility">WeiDU</acronym> installer to v246.
- Included Linux and Mac Os X versions in the same package (thanks AL|EN's Infinity Auto Packager tool!).
- Uploaded mod to official SpellHold Studios GitHub mirror account.
backup

## 

#### Version 2.2 (April 18, 2011)

- Used a better algorithm for listing and moving files.

#### Version 2.1 (January 4, 2011)

- Unknown modifications.

## 

#### Version 2.0 (November 30, 2010)

- Added French translation (thanks Isaya).

## 

#### Version ?.? (November 13, 2010)

- Files whose names don't fit in 8.3 characters aren't biffed.

## 

#### Versions ?.? (July 23, 2010 - January 8, 2010)

- Unknown modifications.

## 

#### Version ?.? (September 16, 2009)

- Only for Linux users.

## 

#### Version ?.? (August 3, 2009)

- Unknown modifications.

## 

#### Version ??? (April 6, 2009)

- Tightened regexp to ensure only valid files will be biffed anyhow.

## 

#### Version 1.0 (March 10, 2009)

- Initial release.
<div align="right"><a href="#top">Back to top</a></div>
