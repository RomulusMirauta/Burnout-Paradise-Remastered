<div align="center">
    <h1>🏁 Welcome, racers! 🏁</h1>
</div>

<br>

<a href="https://store.steampowered.com/app/1238080/Burnout_Paradise_Remastered/">
  <img align="center"
    src="https://raw.githubusercontent.com/RomulusMirauta/Burnout-Paradise-Remastered/refs/heads/main/Burnout_Paradise_Remastered_Splash_Art.jpg"
    alt="Burnout_Paradise_Remastered_Splash_Art" />
</a>

<br>

## This is a  centralized repository of INFO, MODS, PATCHES and TOOLS for the game `Burnout Paradise Remastered` *`(PC version)`* <br>

<br>

## Table of Contents
I.   [**Useful Links**](https://github.com/RomulusMirauta/Burnout-Paradise-Remastered#i-useful-links) <br>
II.  [**Base for MODs** ***(Prerequisite)***](https://github.com/RomulusMirauta/Burnout-Paradise-Remastered#ii-base-for-mods-prerequisite) <br>
III. [**My addition: MOD Uninstaller Script**](https://github.com/RomulusMirauta/Burnout-Paradise-Remastered#iii-my-addition-mod-uninstaller-script) <br>
IV.  [**MODs and associated content**](https://github.com/RomulusMirauta/Burnout-Paradise-Remastered#iv-mods-and-associated-content) <br>
V.   [**Disclaimer**](https://github.com/RomulusMirauta/Burnout-Paradise-Remastered#v-disclaimer) <br>

<br>

## I. Useful Links
- THE GAME
  - STEAM <br>
      https://store.steampowered.com/app/1238080/Burnout_Paradise_Remastered/
  - EA App *(Origin is deprecated now)* <br>
      https://www.ea.com/games/burnout/burnout-paradise-remastered

<br>

- YouTube Links
  - [Old To The New - "Restoration Season" Trailer | Burnout Paradise Remastered](https://www.youtube.com/watch?v=zEr__N5fp9Q)
  - [Expanded Map, Free Camera, Portable Junkyard | Burnout Paradise Remastered Mods](https://www.youtube.com/watch?v=QwK0bMuC_rI)
  - [Burnout Paradise But We Play at Super Speed #shorts](https://www.youtube.com/shorts/HxXRZgTffJg)

<br>

- Steam Community
    - [Map Update - Burnout Paradise Remastered](https://steamcommunity.com/sharedfiles/filedetails/?id=2513119453)
    - [Historical Repository of Creations](https://steamcommunity.com/sharedfiles/filedetails/?id=2861222300)

<br>

- Others
    - [Google Drive - Historical Repository of Creations](https://drive.google.com/drive/folders/1VBAyB1Vpm981tBZRprcGHrl6xzkSBaCV)
    - [PCGamingWiki](https://www.pcgamingwiki.com/wiki/Burnout_Paradise_Remastered)
    - [Nexus Mods](https://www.nexusmods.com/games/burnoutparadiseremastered)

<br>

- Links for OG-only Versions *(Burnout Paradise / Burnout Paradise: The Ultimate Box)*
    - [PCGamingWiki](https://www.pcgamingwiki.com/wiki/Burnout_Paradise)
    - [Nexus Mods](https://www.nexusmods.com/games/burnoutparadise/mods)
    - [GameBanana](https://gamebanana.com/games/7098)

<br>

## II. Base for MODs *(Prerequisite)*

### *Bo Anderson's [(Bo98)](https://github.com/Bo98/bpr-bugs) BPR Modder:*
- [Official link](https://bpr.bo98.uk/)
- It also contains 3 MODs
  - Core Bugfixes (v0.2.1)
  - Traffic Toggle (v1.0)
  - Language Unlocker (v1.0)

<!--
- [Backup](https://raw.githubusercontent.com/RomulusMirauta/bpr-bugs/main/Backup/BPRModderInstaller.exe)
-->

<br>

## III. My addition: MOD Uninstaller Script

- [x] [The BPR Modder Tool does not have an uninstall option](https://github.com/RomulusMirauta/bpr-bugs/issues/1) `#1`
- [ ] Create a GUI for the MOD Uninstaller

### Instructions:
1. Download the script from here: [MOD_Uninstaller_Script.ps1](https://raw.githubusercontent.com/RomulusMirauta/Burnout-Paradise-Remastered/main/MOD_Uninstaller_Script/MOD_Uninstaller_Script.ps1) *(right-click and choose "Save link as...")*
2. Execute the script *(right-click and choose "Run with PowerShell")*
3. *If prompted, click Open*
4. Follow the on-screen instructions

<br>

> [!IMPORTANT]
> **If the script executes but the window closes by itself, it means that the current Windows User is not allowed to run scripts.**
> 
> **Here's how to solve this:**
> 1. Open PowerShell's CLI *(click on Windows' Start button - type "powershell" - right-click and choose "Run as administrator")*
> 2. Copy the following command:
> ```ps1
> Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser -Force
> ```
> 3. Paste the command into the previously opened window
> 4. Press `Enter`
> 5. Attempt to start the MOD Uninstaller Script again
> 
> <br> **In order to revert the previously made changes, you can run this PowerShell command:**
>    ```ps1
>    Set-ExecutionPolicy -ExecutionPolicy Restricted -Scope CurrentUser -Force
>    ```

<br>

## IV. MODs and associated content

### 1. Community MODs:
- ***Included in [Bo Anderson's (Bo98) BPR Modder](https://github.com/RomulusMirauta/bpr-bugs#bo-andersons-bo98-bpr-modder)***
- Name: Brick Remastered (v1.0.6d)
- INFO
  - What is this? A mod menu and HUD providing you with various utilities for BPR including
  - Portable junkyard *(including the choice of selecting locked vehicles)*
  - On-the-go and unrestricted car paint choice *(more than what's available in the Junkyard)*
  - Speedometer
  - Wheel changing
  - Boost changing and refill
  - Various other quality-of-life improvements including speedier Junkyard vehicle selection

<br>

### 2. *[orimarc](https://community.pcgamingwiki.com/profile/5329-orimarc/)*'s PATCH:
- [BPR Speed Patch](https://community.pcgamingwiki.com/files/file/2058-bpr-speed-patch/)
- INFO
  - Unlocks framerate, enabling game rendering at `60 FPS` (the game default's being just `30 FPS`)
  - Adds a fan patch - that enables changing traffic density
  - Can cause steering problems at higher frame rates above `60 FPS`
  - High traffic density is enabled by default, but it can be disabled by changing `EnableExtraOptions`'s value to `0`

<br>

### 3. Matty's *[(matty-ross)](https://github.com/matty-ross/bpr-mods-repository)* - [MODs](https://matty-ross.github.io/bpr-mods/):
- Exception Reporter
  - Displays a dialog with exception's information when it rises.
- Free Camera
  - Allows moving the external camera around the city. Plus various camera properties that can be changed.
- Bully Repellent
  - Automatically kicks or mutes a player on the user's blacklist.
- Protection
  - Replaces a new vehicle's or challenge's ID sent over the network to avoid crashing players.

<br>

### 4. Matty's *[(matty-ross)](https://github.com/matty-ross/bpr-mods-repository)* - [PACKs](https://matty-ross.github.io/bpr-mods/#:~:text=avoid%20crashing%20players.-,Packs,-RV1.4%20Remastered):
- RV1.4 Remastered *(ported)*
- RV2 Remastered *(ported)*

<br>

### 5. Nathan V's *[(JeBobs)](https://github.com/JeBobs)* - TOOLs:
- [Blender Helper Tools](https://github.com/JeBobs/blender_burnout_paradise_helpers)
- [BrnDataHandler](https://github.com/JeBobs/BrnDataHandler)

<br>

## V. Disclaimer
> [!NOTE]
> ***I do not claim ownership of any content created or shared by others - that is linked or referenced in this repository. All rights remain with the original creators. If you believe any content here violates intellectual property rights or other guidelines, please feel free to reach out, and I will address the issue promptly.***
