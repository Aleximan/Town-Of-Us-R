# Town Of Impostors

<a href="https://discord.gg/xpsKVpUf4T"><p align="center"><img src="https://user-images.githubusercontent.com/78827892/114307643-77e45c00-9ad8-11eb-81a5-44e985616cc5.png" width="300"></a>
<a href="https://twitter.com/itsAJMix"><img src="https://user-images.githubusercontent.com/78827892/114704193-3a711000-9d1e-11eb-843e-c25ea9cb7488.png" width="300"></p></a>

<p align="center">We now have a discord server! Join the discord server: https://discord.gg/xpsKVpUf4T</p>
<p align="center">Follow me on twitter: https://twitter.com/itsAJMix</p>

<p align="center">Town Of Impostors Mod is a modification for Among Us - <b>PC/Windows (Steam)</b>. This mod aims to add new roles, modifiers & abilities to enhance gameplay, while also providing a full range of options to allow for customising and playing games your way.</p>

<p align="center"><b>Every player in the room must have the mod installed for it to work correctly. Please DO NOT play this mod on public lobbies, it is intended for private organised lobbies.</b></p>

<p align="center">
<img src="Pics/TOI-Animated.gif" width="360">
</p>

<p align="center">
<img src="Pics/TownOfImpostors-Impostor2.png" width="270">
<img src="Pics/TownOfImpostors-Sheriff.png" width="270">
<img src="Pics/TownOfImpostors-Doctor.png" width="270">
<img src="Pics/TownOfImpostors-Jester.png" width="270">
<img src="Pics/TownOfImpostors-Agent.png" width="270">
<img src="Pics/TownOfImpostors-Detective.png" width="270">
<img src="Pics/TownOfImpostors-Plumber.png" width="270">
<img src="Pics/TownOfImpostors-Arsonist.png" width="270">
<img src="Pics/TownOfImpostors-Informant.png" width="270">
<img src="Pics/TownOfImpostors-Trickster.png" width="270">
<img src="Pics/TownOfImpostors-Operative.png" width="270">
<img src="Pics/TownOfImpostors-Mayor.png" width="270">
</p>

---

<p align="center">
<img src="Pics/TownOfImpostors-LoversModifier.png" width="270">
 <img src="Pics/TownOfImpostors-Giant.png" width="270">
 <img src="Pics/TownOfImpostors-Tiny.png" width="270">
 <img src="Pics/TownOfImpostors-Nightowl.png" width="270">
</p>

---

<p align="center">
<img src="Pics/TownOfImpostors-Dragger.png" width="270">
<img src="Pics/TownOfImpostors-Morphling.png" width="270">
<img src="Pics/TownOfImpostors-Deceiver.png" width="270">
 <img src="Pics/TownOfImpostors-Viper.png" width="270">
 <img src="Pics/TownOfImpostors-Hitman.png" width="270">
 <img src="Pics/TownOfImpostors-Joker.png" width="270">
 <img src="Pics/TownOfImpostors-Assassin.png" width="270">
 <img src="Pics/TownOfImpostors-Predator.png" width="270">
 <img src="Pics/TownOfImpostors-Sniper.png" width="270">
</p>

---

Table of Contents
=================
  * [Installation](#installation)
    * [Releases and Compatibility](#releases-and-compatibility)
    * [Saving and Loading Settings](#saving-and-loading)
    * [Uninstalling](#uninstalling-the-mod)
    * [Updating](#updating-the-mod)
  * [Custom Hats](#customhats)
    * [Modifiers](#modifiers)
    * [Advanced Modifiers](#advanced-modifiers)
  * [Custom Colors](#customcolors)
  * [Streamer Mode](#streamermode)
  * [Roles, Abilities, Modifiers & Custom Options](#roles-abilities-modifiers--custom-options)
    * [Crewmate Team](#crewmate-team)
      * [Sheriff](#sheriff)
      * [Doctor](#doctor)
      * [Agent](#agent)
      * [Detective](#detective)
      * [Plumber](#plumber)
      * [Informant](#informant)
      * [Trickster](#trickster)
      * [Operative](#operative)
      * [Mayor](#mayor)
    * [Other Teams](#other-teams)
      * [Jester](#jester)
      * [Arsonist](#arsonist)
      * [Impostor](#impostor-team)
    * [Modifiers](#modifiers)
      * [Lovers](#lovers)
      * [Giant](#giant)
      * [Tiny](#tiny)
      * [Nightowl](#nightowl)
    * [How Role Assignment Works](#how-does-role-assignment-work)
  * [FAQ](#faq)
  * [Troubleshooting](#troubleshooting)
    * [Known Issues](#known-issues)
  * [Contact & Donations](#contact--donations)
  * [Credits](#credits)
  * [License](#license)

---

<h1 id="installation">Installation</h1>

- If you are updating your Town Of Impostors version, please hop to this section [here](#updating-the-mod).

- Before installing, verify your Among Us version by launching the game and checking the version displayed in the top left of the main menu.

- As of the Among Us v2021.3.31.3s update, **you must sign in to your account and set your player name now** to avoid issues later such as setting your name or typing in the chat in the modded game.

- Download the Mod for your specific game version from the table below or check all releases [here](https://github.com/AJMix/TownOfImpostors/releases). **ENSURE THAT YOUR AMONG US VERSION MATCHES EXACTLY - EVERY DIGIT, LETTER, DOT & ALL.**

- Make a copy of your clean, unmodded game’s root directory `Steam/steamapps/common/Among Us` and rename the copied directory to whatever you want e.g. `Steam/steamapps/common/Among Us Town Of Impostors`. This copied directory is what will be modded. You can get to your root directory by right-clicking Among Us in Steam -> Properties -> Local Files -> Browse. **RECOMMENDED STEP TO KEEP SEPARATE COPIES IN CASE YOUR MODDED GAME BREAKS & TO AVOID AN AUTO-UPDATE BREAKING THE MOD.**

- Extract the contents `TownOfImpostors.zip` into the copied folder you created.

- Ensure the copied directory that is being modded now contains at least the following:
```
.
├── Among Us_Data
├── BepInEx <---
├── mono <---
├── Among Us.exe
├── baselib.dll
├── doorstop_config.ini <---
├── GameAssembly.dll
├── steam_appid.txt <---
├── UnityCrashHandler32.exe
├── UnityPlayer.dll
└── winhttp.dll <---
```
<details>
 <summary>Still unsure? Click this for an image of what it should look like if you have hidden file name extensions</summary>
 <img src="Pics/TownOfImpostersDirectoryNew.png">
 </details>
 
- **Make sure to launch the game via the Among Us.exe from this directory**. Please note that the first time launching the game with this mod may take a while - give it one minute before worrying that nothing is appearing.

**Verifying installation success**
- Launching the game via Among Us.exe
- In the top-left corner of the main menu, below the Among Us version, you should see _Town Of Impostors vX.X.X Mod by AJMix_ to indicate the mod is running and has been successfully installed.

If you don't see this message or have any other issues, please take a look at the <a href="#troubleshooting">troubleshooting section</a>.


**Version Mismatch Checker:**
- Starting from v1.8.1 onwards, there is now a version mismatch checker that'll make sure that all users in the lobby are using the same game version. If a red message appears on the top right stating **"Warning: Player Version Mismatch"**, then there's a potential that someone in the lobby is not using the correct version.
- Sometimes this warning message can appear when something strange occurs, even if all users in the lobby are using the same version. If you're 100% sure all users in the lobby are using the same mod version, simply have players rejoin the lobby.

_Before raising an issue, please double check that you have accurately followed the installation instructions and you are not using any mod manager or other mods._

_Starting from v1.5.0 onwards, there is a new reset custom settings button in the lobby. Please use it if your settings are bugged. Settings can bug when you update from version to version, it's best practice to reset settings._

_Starting from v1.6.0 onwards, this mod should now be compatible with Mod Manager by MatuxGG. Please note that using the Mod Manager to install the mod still does not guarantee that the mod will work as intended._

### Saving and Loading
Starting from v1.8.1, you can now save and load your settings. This is to help lower the issue of settings completely messing up between versions. You should find a new `TownOfImpostorsSettings.txt` in the Among Us folder where the mod is installed. This can also be passed onto others so they can play with your settings!

From v1.8.6 onwards, there are now 5 **Save & Load** slots. You can use these to save multiple settings. You will be able to find them as `TownOfImpostorsSettings_1.txt`, `TownOfImpostorsSettings_2.txt` etc. inside of the `TownOfImpostors_Data` folder. Please launch the game or create the folder yourself if you don't see it. These settings can be passed onto others. If you were using the previous `TownOfImpostorsSettings.txt` before, please move this into the folder and rename it to `TownOfImpostorsSettings_1.txt`.

### Uninstalling the Mod
- If you copied the Among Us folder as instructed by the Installation Steps, simply delete the copied folder.
- If you did not, and you unzipped the mod into your main Among Us folder, then you have to delete the following folders & files:
  - **BepInEx** folder, **mono** folder, **doorstop_config.ini**, **winhttp.dll**
 
<h2>Releases and Compatibility</h2>

<table style="width:100%">
  <tr>
    <th>Among Us Version</th>
    <th>Mod Version</th>
    <th>Link</th>
  </tr>
 <tr>
    <td>v2021.6.15s</td>
    <td>v2.0.8</td>
    <td><a href="https://github.com/AJMix/TownOfImpostors/releases/download/v2.0.8/TownOfImpostors2.0.8.zip">Download</></td></td>
   </tr>
 <tr>
 <tr>
    <td>v2021.6.15s</td>
    <td>v2.0.7</td>
    <td><a href="https://github.com/AJMix/TownOfImpostors/releases/download/v2.0.7/TownOfImpostors2.0.7.zip">Download</></td></td>
   </tr>
 <tr>
 <tr>
    <td>v2021.5.25s & v2021.5.25e</td>
    <td>v2.0.6</td>
    <td><a href="https://github.com/AJMix/TownOfImpostors/releases/download/v2.0.6/TownOfImpostors2.0.6.zip">Download</></td></td>
   </tr>
 <tr>
    <td>v2021.5.10s</td>
    <td>v2.0.5</td>
    <td><a href="https://github.com/AJMix/TownOfImpostors/releases/download/v2.0.5/TownOfImpostors2.0.5.zip">Download</></td></td>
   </tr>
 <tr>
 <tr>
    <td>v2021.5.10s</td>
    <td>v2.0.3</td>
    <td><a href="https://github.com/AJMix/TownOfImpostors/releases/download/v2.0.3/TownOfImpostors2.0.3.zip">Download</></td></td>
   </tr>
 <tr>
 <tr>
    <td>v2021.5.10s</td>
    <td>v2.0.1</td>
    <td><a href="https://github.com/AJMix/TownOfImpostors/releases/download/v2.0.1/TownOfImpostors2.0.1.zip">Download</></td></td>
   </tr>
 <tr>
    <td>v2021.4.12s & v2021.4.14s</td>
    <td>v2.0.0</td>
    <td><a href="https://github.com/AJMix/TownOfImpostors/releases/download/v2.0.0/TownOfImpostors2.0.0.zip">Download</></td></td>
   </tr>
 <tr>
 <tr>
    <td>v2021.4.12s & v2021.4.14s</td>
    <td>v1.9.2</td>
    <td><a href="https://github.com/AJMix/TownOfImpostors/releases/download/v1.9.2/TownOfImpostors1.9.2.zip">Download</></td>
   </tr>
 <tr>
 <tr>
    <td>v2021.4.12s & v2021.4.14s</td>
    <td>v1.8.6.1</td>
    <td><a href="https://github.com/AJMix/TownOfImpostors/releases/download/v1.8.6.1/TownOfImpostors1.8.6.1.zip">Download</></td>
   </tr>
 <tr>
    <td>v2021.4.12s & v2021.4.14s</td>
    <td>v1.8.6</td>
    <td><strike>Download</strike></></td>
   </tr>
  <tr>
 <tr>
    <td>v2021.4.12s & v2021.4.14s</td>
    <td>v1.8.2.1</td>
    <td><a href="https://github.com/AJMix/TownOfImpostors/releases/download/v1.8.2.1/TownOfImpostors1.8.2.1.zip">Download</></td>
   </tr>
  <tr>
    <td>v2021.3.31.3s</td>
    <td>v1.8.1</td>
    <td><a href="https://github.com/AJMix/TownOfImpostors/releases/download/v1.8.1/TownOfImpostors1.8.1.zip">Download</></td>
   </tr>
  <tr>
    <td>v2021.3.31.3s</td>
    <td>v1.7.1</td>
    <td><a href="https://github.com/AJMix/TownOfImpostors/releases/download/v1.7.1/TownOfImpostors1.7.1.zip">Download</></td>
   </tr>
  <tr>
  <tr>
    <td>v2021.3.31.3s</td>
    <td>v1.7.0</td>
    <td><a href="https://github.com/AJMix/TownOfImpostors/releases/download/v1.7.0/TownOfImpostors1.7.0.zip">Download</></td>
   </tr>
  <tr>
  <tr>
    <td>v2021.3.5s</td>
    <td>v1.6.1</td>
    <td><a href="https://github.com/AJMix/TownOfImpostors/releases/download/v1.6.1/TownOfImpostors1.6.1.zip">Download</></td>
   </tr>
  <tr>
    <td>v2021.3.5s</td>
    <td>v1.6.0</td>
    <td><a href="https://github.com/AJMix/TownOfImpostors/releases/download/v1.6.0/TownOfImpostors1.6.0.zip">Download</></td>
   </tr>
   <tr>
    <td>v2021.3.5s</td>
    <td>v1.5.0</td>
    <td><a href="https://github.com/AJMix/TownOfImpostors/releases/download/v1.5.0/TownOfImpostors1.5.0.zip">Download</></td>
   </tr>
    <tr>
    <td>v2021.3.5s</td>
    <td>v1.4.0</td>
    <td><a href="https://github.com/AJMix/TownOfImpostors/releases/download/v1.4.0/TownOfImpostors1.4.0.zip">Download</></td>
  </tr>
    <tr>
    <td>v2021.3.5s</td>
    <td>v1.3.0</td>
    <td><a href="https://github.com/AJMix/TownOfImpostors/releases/download/v1.3.0/TownOfImpostors1.3.0.zip">Download</></td>
  </tr>
    <tr>
    <td>v2020.12.9s</td>
    <td>v1.2.0</td>
    <td><a href="https://github.com/AJMix/TownOfImpostors/releases/download/v1.2.0/TownOfImpostors1.2.0.zip">Download</></td>
  </tr>
   <tr>
    <td>v2020.12.9s</td>
    <td>v1.1.0</td>
    <td><a href="https://github.com/AJMix/TownOfImpostors/releases/download/v1.1.0/TownOfImpostors1.1.0.zip">Download</></td>
  </tr>
  <tr>
    <td>v2020.12.9s</td>
    <td>v1.0.0</td>
    <td><a href="https://github.com/AJMix/TownOfImpostors/releases/download/v1.0.0/TownOfImpostors1.0.0.zip">Download</></td>
  </tr>
</table>

<details>
  <summary>Changelog</summary>
 <details>
  <summary>v2.0.8</summary>
  <h3>v2.0.8</h3>
   <ul>
    <li>Fixed voting issues breaking the game</li>
   </ul>
  <summary>v2.0.7</summary>
  <h3>v2.0.7</h3>
   <ul>
    <li>Compatibility with v2021.6.15s of Among Us</li>
    <li>Various small bug fixes</li>
   </ul>
  <summary>v2.0.6</summary>
  <h3>v2.0.6</h3>
   <ul>
    <li>Fixed bug with custom hat system</li>
<li>Fixed issue with meetings not ending correctly with sniping/poison</li>
<li>Fixed issue with Tiny/Giant modifier kills leading to players going into walls</li>
<li>Added more custom hats</li>
   </ul>
    </details>
 <details>
  <summary>v2.0.5</summary>
  <h3>v2.0.5</h3>
   <ul>
    <li>Fixed and optimised bugs regarding custom options</li>
<li>Further optimised custom button system</li>
<li>Sniper reveal arrow duration can now be set to 0 (so it doesn't appear at all)</li>
<li>dded extra safety checks to Hat System to prevent everything breaking</li>
<li>Fixed speed issues with Tiny</li>
<li>Fixed Tiny not being able to do some tasks</li>
<li>Fixed HidePlayerModel still hiding players on comms sabotage anonymity</li>
<li>Fixed exploit that allowed people to go through walls when morphing into Giant/Tiny</li>
<li>[Balance Change] Comms Anonymous Sabotage now also updates player scale to take into account Giant/Tiny modifiers for consistency</li>
   </ul>
    </details>
 <details>
  <summary>v2.0.3</summary>
  <h3>v2.0.3</h3>
   <ul>
    <li>Morphing fix</li>
   </ul>
    </details>
 <details>
  <summary>v2.0.1</summary>
  <h3>v2.0.1</h3>
   <ul>
<li>New Home Update Button, Easier Updating Of Mod</li>
<li>Fixed Sniper Kill Button exploit</li>
<li>Fixed vote not ending if Sniper dies</li>
<li>Fixed Sniper guess text not displaying properly</li>
<li>Lobby Host Buttons should now appear for new host when previous host leaves</li>
<li>Custom Color txt and Settings txt are now renamed to backup files</li>
   </ul>
    </details>
  <details>
  <summary>v2.0.0</summary>
  <h3>v2.0.0</h3>
   <ul>
<li>Sniper Role (Unique Impostor Role)</li>
<li>Hat System 2.0 (Animated Hats, More Possibilities)</li>
<li>Dead Players Seeing All Roles now also see Lover Icons</li>
<li>Art updates by Con No 1 (Twitter @Con_No_1)</li>
<li>Giant Modifier, Tiny Modifier, Nightowl Modifier</li>
<li>Impostors can now see poisoned players in meetings</li>
<li>[Custom Option] Speed Modifier % for dragging bodies</li>
<li>[Custom Option] Poison Continues In Meeting</li>
<li>Fixed a bug with venting with Plumber & Jester</li>
<li>Fixed bug with blind traps not being disabled when toggle off</li>
<li>Fixed bug with sabotages not ending game in some cases with All Crewmates Must Die Mode On</li>
<li>Fixed Jester Footprints not disappearing on death</li>
<li>Fixed bug with revived Informants losing role and seeing everyone as their own name</li>
<li>Fixed bug with Poison Kills on Decoys not properly setting cooldown</li>
<li>Fixed exploit allowing Impostors to reset cooldown after poison ability</li>
   </ul>
    </details>
 <details>
  <summary>v1.9.2</summary>
  <h3>v1.9.2</h3>
   <ul>
<li>Settings 2.0</li>
<li>[Custom Option] Enable Impostor Abilities (only if Impostor Roles are off)</li>
    <li>[Custom Option] Mayor Cannot Be Lover</li>
<li>ALL MUST DIE Gamemode (Impostors only win if ALL crewmates are dead)</li>
<li>Impostor Blind Trap Ability</li>
<li>Impostor Poison Ability</li>
<li>Detective Body Scan Ability</li>
<li>Detective Body Report shows whether victim was poisoned</li>
<li>Impostor Viper Role (Tier 1)</li>
<li>Impostor Assassin Role (Tier 2)</li>
<li>Impostor Predator Role (Tier 3)</li>
<li>New warning for when settings are bugged (messed up values)</li>
<li>Added foolproof checks to prevent errors in custom colors, settings and hats from stopping the mod from loading</li>
<li>Using chat (between meetings) no longer freezes kill cooldown, this should encourage more Impostor Comms/Lover chat</li>
<li>Jester can see their own footprints if paint ability toggled on</li>
<li>Game Continues With Arsonist is now a "Gamemode"</li>
<li>Mayor Hats will no longer show in meeting hud if player is dead</li>
<li>Fixed bug with ghosts still having issues with vision</li>
<li>Arsonist douse time now defaults to 2 seconds</li>
<li>Detective Anonymous Footprints defaults off, footprint time default 15 seconds</li>
<li>Fixed bug with uninteractable bodies</li>
<li>Fixed exploit that allowed Doctors to revive & report someone at the same time</li>
<li>Fixed bug with Arsonist dousing players in vents</li>
<li>QoL update, hats tab mentions hat pages</li>
<li>Progress Bar QoL update</li>
<li>Fixed small bug with loaded settings not synced between players</li>
<li>Various small bug fixes</li>
<li>Even more optimisations for even smoother performance</li>
   </ul>
    </details>
  <details>
  <summary>v1.8.6.1</summary>
  <h3>v1.8.6.1</h3>
   <ul>
<li>Fixed major game breaking bugs with voting</li>
<li>Fixed issue with bodies disappearing if player dies while dragging a body through vent</li>
<li>Fixed potential issues with trickster disguised decoy</li>
    <li>Various small bug fixes and optimisations</li>
   </ul>
    </details>
 <details>
  <summary>v1.8.6</summary>
  <h3>v1.8.6</h3>
   <ul>
<li>Mayor Role</li>
<li>Map Randomisation Game Mode</li>
<li>Brought back "dlekS ehT" map</li>
<li>Hat Pages to store more custom hats</li>
<li>Arsonist can now douse players in vents</li>
<li>Optional hat name modifiers for hats to display better in menu _<xOffset>_<yOffset> (example _0.0f_0.1f)</li>
<li>Sheriff kill timer will start at 10 seconds, matching Impostors</li>
<li>Impostors inside of vents can now kill Plumbers & Jesters inside of vents</li>
<li>Moved "Can Vent With Body" to General Options</li>
<li>Trickster Disguise Ability</li>
<li>Hitman & Joker Impostor Roles</li>
<li>Fixed bug associated with disguise & start meeting</li>
<li>Fixed color name bug</li>
<li>Fixed Impostors setting names as red in messages even with Impostors Do Not Know Each Other option</li>
<li>Fixed desyncs with dispose body</li>
<li>Fixed Streamer Mode</li>
<li>Implemented Host Checks for Sheriff & Impostor kills to prevent kill desyncs (this will introduce host advantage and delay to kills if you're not the host, but this fixes all desyncs on kills)</li>
<li>Fixed gamebreaking bugs with impostors kills</li>
<li>Fixed bug with lover death not removing disguise</li>
<li>Compatibilities with Reactor & Reactor.Essentials</li>
<li>Impostor Retrieve Body Ability</li>
<li>Plumber Retrieve Body Ability</li>
<li>Doctor Retrieve Body Ability</li>
<li>Jester Retrieve Body Ability</li>
<li>[Custom Option] Vents Hold Multiple Bodies</li>
<li>[Custom Option] Imps Can Kill Inside Vents</li>
<li>Massive optimisations</li>
<li>Various other null ref and bug fixes</li>
   </ul>
    </details>
 <details>
  <summary>v1.8.2.1</summary>
  <h3>v1.8.2.1</h3>
   <ul>
    <li>Separate Impostor roles (Dragger, Morphling, Deceiver)</li>
    <li>Custom Hats can now match Crewmate color with _anycolor modifier</li>
    <li>More custom hats from community</li>
    <li>Fixed issue with Lover getting stuck in Airship</li>
     <li>Name fixes (fixed issue with host role being revealed sometimes)</li>
     <li>Fixed issues with colours of certain hats messing up in ladder climb in airship</li>
     <li>Fixed issues with people seeing Lover's chat</li>
     <li>Bug fixes and polishes</li>
     <li>[Custom Option] Dead Player See All Roles</li>
     <li>[Custom Option] Sheriff Does Not Die</li>
     <li>[Custom Option] Imps Do Not Know Each Other</li>
   </ul>
    </details>
 <details>
  <summary>v1.8.1</summary>
  <h3>v1.8.1</h3>
   <ul>
    <li>Bunch of awesome custom hats from the community</li>
    <li>Operative Role</li>
    <li>More colours to select from</li>
    <li>Improved Naming/Role, colorblind-friendly</li>
     <li>Save/Load Settings Button In Lobby</li>
     <li>Fixed game breaking bugs with custom colours</li>
     <li>Fixed Text: Lovers Wins -> Lovers Win</li>
     <li>Fixed specific hats not working with Decoys</li>
     <li>Impostors can now use destroy decoy, disguise and dispose body again in vents (Sorry for breaking this before)</li>
     <li>Fixed an issue with "Impostors Can Kill Each Other" somehow causing infinite disguise</li>
     <li>Fixed a small issue with some hats & disguise</li>
     <li>Fixed issue with agent cams ability broken on airship</li>
     <li>Fixed an issue with arsonist continuing douse even while dead</li>
    <li>Fixed sabotage comms anonymity not working on decoys</li>
    <li>Fixed an issue where player's hats would appear for a frame while anonymous when climbing ladders/performing a kill</li>
    <li>[Custom Option] Jester Bloody Footprints</li>
    <li>[Custom Option] Jester Body Drag</li>
    <li>[Custom Option] Jester Can Use Vents</li>
   </ul>
    </details>
 <details>
  <summary>v1.7.1</summary>
  <h3>v1.7.1</h3>
   <ul>
    <li>Compatibility with 2021.3.31.3s</li>
    <li>CUSTOM HATS! (See instructions on how this works at the top)</li>
    <li>Streamer Mode (See instructions on how this works at the top)</li>
    <li>Fixed role selection not properly randomising player list (host always got a role no matter what)</li>
     <li>Bloodstains on vents should now properly disappear after meetings</li>
     <li>Detective footprints now properly disappear after they lose their role from revives)</li>
     <li>Fixed ghost crewmate vision that broke in the latest version</li>
     <li>Made Informant arrows bigger</li>
     <li>Fixed issue with disguise revealing impostors before meetings</li>
     <li>Fixed role description text not appearing properly</li>
     <li>Fixed a bug that caused infinite duration for some abilities</li>
     <li>Fixed agent abilities being broken in some maps</li>
     <li>[Modifier] Lover Modifier</li>
    <li>[Custom Option] Disguised Footprints: Toggles whether Disguised Impostors leave Disguised Footprints</li>
    <li>[Custom Option] Agent Abilities Share Cooldown: Toggles whether all Agent abilities should go into cooldown when using one ability</li>
    <li>[Custom Option] Game Continues With Arsonist: Toggles whether the game continues if Arsonist is still alive</li>
    <li>[Custom Option] Disable Body Report: Toggles whether body reports are enabled or not</li>
   </ul>
    </details>
  <details>
  <summary>v1.7.0</summary>
  <h3>v1.7.0</h3>
   <ul>
    <li>Compatibility with 2021.3.31.3s</li>
    <li>Compatibilities with Airship</li>
    <li>Trickster Role</li>
    <li>Impostor Decoy Abilities (Like Trickster)</li>
     <li>Lobby Role Summary for Chances and Count</li>
     <li>Lobby Improvements (Role Bookmarks)</li>
     <li>Colorblind Friendly Updates</li>
     <li>Fixed bugs with Impostor Comms</li>
     <li>Dousing & Reviving now show progress bars instead</li>
     <li>Fixed bugs with dead bodies using wrong colours on Comms Sabotage</li>
     <li>Fixed some buttons resetting CDs on opening windows</li>
     <li>Fixed issue with toggle buttons blocking scrolling/clickable anywhere (don't know why Innersloth made it like this)</li>
     <li>Various bug fixes & optimisations</li>
   </ul>
    </details>
  <details>
  <summary>v1.6.1</summary>
  <h3>v1.6.1</h3>
   <ul>
    <li>Fixed issue with DLL plugin no longer working</li>
    <li>Disguise issues with Meetings and KillOverlay fixed</li>
    <li>Fixed revived players losing "Douse" state</li>
    <li>Fixed hotkeys still working while other windows are opened</li>
     <li>Fixed abilities being able to be used while doing other things</li>
   </ul>
    </details>
  <details>
  <summary>v1.6.0</summary>
  <h3>v1.6.0</h3>
   <ul>
    <li>Informant role</li>
    <li>Doctor Medbay only fix for Polus</li>
    <li>DNA Sample button improved</li>
    <li>Mod Manager (by MatuxGG)/Reactor.Essentials compatibility</li>
    <li>Fixed disguising-pet-vent bug</li>
    <li>Custom Option: Crewmate Ghosts Use Crewmate Vision</li>
    <li>Percentage Chance for Roles</li>
    <li>New 1,2,3,4.. Keybinds for Abilities</li>
     <li>Arsonist better end visuals</li>
     <li>Custom Option for killers to leave bloody footprints for detective</li>
     <li>Custom Option to allow Impostors to kill each other</li>
     <li>Custom Option for Arsonist to refuel</li>
     <li>Custom Option for Jester to win from Sheriff Kill</li>
     <li>Custom Option for Doctor Revive to remove Crewmate special role</li>
     <li>Custom Option to change whether Impostor can vent with body or not</li>
     <li>Custom Option for Doctor Revive Time</li>
     <li>Fixed bug with Detective seeing Impostor colour footprints despite being disguised</li>
     <li>Fixed bug with Pets reappearing during comms sabotage after meeting</li>
     <li>Fixed bug with buttons being used in meetings</li>
     <li>Balance Fix: Custom Buttons cooldowns no longer continue going down during meetings</li>
     <li>Removed CUSTOM server option (please look into Unify by MoltenMods)</li>
     <li>Various null fixes</li>
     <li>Optimisations</li>
   </ul>
    </details>
  <details>
  <summary>v1.5.0</summary>
  <h3>v1.5.0</h3>
   <ul>
    <li>Impostor Drag & Drop Body Ability toggle</li>
    <li>Arsonist Role</li>
    <li>Plumber Role</li>
    <li>Detective Role</li>
    <li>Doctor Drag & Drop Body Ability</li>
    <li>Doctor Option: Medbay revives only</li>
    <li>Impostor Comms</li>
    <li>Comms sabotage causes anonymity</li>
     <li>Jester Victory Screen Fix</li>
     <li>Dead bodies won't play kill animation on vent exit</li>
     <li>You can now sample DNA from dead bodies</li>
     <li>Fake tasks for Jester & Arsonist</li>
     <li>Role description in task list</li>
     <li>Reset custom settings button in lobby</li>
     <li>Updated role selection process</li>
     <li>Dispose Bodies leave bloodsplat</li>
     <li>Button bug fixes</li>
     <li>Anonymous Votes resetting fix</li>
     <li>Various null fixes</li>
     <li>Optimisations</li>
   </ul>
    </details>
  <details>
  <summary>v1.4.0</summary>
  <h3>v1.4.0</h3>
   <ul>
    <li>Agent Role</li>
    <li>Fixed settings resetting bug</li>
    <li>Added CUSTOM server option</li>
    <li>Sheriff custom kill button sprite</li>
    <li>Option for same roles to know each other</li>
    <li>Option for Sheriff to kill non-impostors</li>
    <li>Sheriff Kill CD changes</li>
    <li>Various null fixes</li>
   </ul>
  </details>
  <details>
  <summary>v1.3.0</summary>
    <h3>v1.3.0</h3>
   <ul>
    <li>Compatibility with v2021.3.5s</li>
    <li>Updated custom options to be more clean & clear</li>
    <li>New ability to cycle through options HUD display</li>
    <li>Jester role</li>
    <li>Fixed issue with Sheriff being able to kill through walls</li>
    <li>Fixed detection through walls for other abilities</li>
    <li>Fixed issue with dragging body sometimes not rendering on top of ground</li>
    <li>Various null fixes</li>
   </ul>
  </details>
  <details>
  <summary>v1.2.0</summary>
  <h3>v1.2.0</h3>
   <ul>
    <li>Fixed Sheriff being able to kill Impostor in vent</li>
    <li>Disguise should now work properly with pets</li>
    <li>Several other null bugs</li>
   </ul>
  </details>
  <details>
  <summary>v1.1.0</summary>
  <h3>v1.1.0</h3>
   <ul>
    <li>Fixed taskbar not updating and removing "you are dead" line when revived</li>
    <li>Fixed bug with Sheriff not being able to kill Impostor</li>
    <li>Several nullpointer bugfixes</li>
   </ul>
  </details>
</details>
 
### Updating the Mod
It is recommended to keep separate folders for each version of Town Of Impostors instead of overwriting, even if the Among Us version between them is the same and it appears that the bundled files are the same in each release. But if you're intent on updating an existing version of the mod with a new version that is compatible to that version of Among Us: 

- Please ensure you **extract and overwrite all** that has been asked. Do not pick and mix, or extract only the `TownOfImpostors.dll` for updating. Each release was crafted for the BepInEx it is bundled with, so there will be errors if the wrong version of BepInEx is used.

- We've begun labelling the mod with `TownOfImpostors-X.X.X.dll` to help differentiate between the versions under file explorers, so you may not receive a confirmation to overwrite the mod itself. Whilst this should not cause any issues as BepInEx checks and uses the latest version of a mod, if there are any problems, please proceed to `\Among Us Modded\BepInEx\plugins\` and delete the older versions of the mod.

- Inside your `\Among Us Modded\BepInEx\`, please delete the `\cache\` folder.

- You may have to sign in again to your account. If it does not work inside the modded game, please launch the unmodded version and sign in through there first before returning to the modded game. This is why we recommend copying and working with a copied directory of Among Us that is not auto-updated by Steam but also a backup for any issues involving modding.

- In the lobby, please click Reset Settings on the bottom left when playing a new version of Town Of Impostors. See [Known Issues](#known-issues) for why. If you're running v1.8.1 or higher, you may use the Save Settings before the update, then Load Settings after the update to restore your Town Of Impostors configuration.

- Now hope all is good! If there are errors, you can always resort to a fresh installation of the mod with another copy of the unmodded Among Us folder!   

<h2>Curseforge</h2>
You can download the mod on Curseforge <a href="https://www.curseforge.com/among-us/all-mods/town-of-impostors">here</a>.

---

<h1 id="customhats">Custom Hats</h1>

**Only for versions v1.7.1 onwards**

## How do I add my own Custom Hat?

### New System:
* Download the **new** template, along with the default empty manifest.json to being making Custom Hats for Town Of Impostors (you may still use the old template if you want to) **Massive thanks to JonyKasual for working hard to create an advanced template**
  * Download an empty `manifest.json` [here](https://github.com/AJMix/TownOfImpostors/releases/download/v2.0.0/manifest.json)
  * Download .psd template 150x185 [here](https://github.com/AJMix/TownOfImpostors/releases/download/v2.0.0/ToI_CustomHat_Template_150x185_v2.psd)
  * Download .psd template 225x280 [here](https://github.com/AJMix/TownOfImpostors/releases/download/v2.0.0/ToIHat_AdvancedTemplate_225x280.psd)
  * Download .psd template 300x370 [here](https://github.com/AJMix/TownOfImpostors/releases/download/v2.0.0/ToIHat_AdvancedTemplate_300x370.psd)
  * Download .png template for Idle (150x185) [here](https://github.com/AJMix/TownOfImpostors/releases/download/v2.0.0/ToI_CustomHat_Template_150x185_Idle_v2.png)
  * Download .png template for Climbing (150x185) [here](https://github.com/AJMix/TownOfImpostors/releases/download/v2.0.0/ToI_CustomHat_Template_150x185_Climbing_v2.png) 
* Draw your hat on the template and save in PNG format, with a unique name (make sure to also hide the crewmate and shadow). Preserve the resolution.

* With the new system, you will be able to create hats for all layers (Front, Back, Climbing) and have to all compiled into one, as long as it is all specified in the manifest.json. You will also be able to create animated hats, and specify other parameters such as hat bounce, adaptive color and whether to hide crewmate.
* To get animated hats, set the animated parameter in the manifest.json to `true` and add to the list of Front, Back or Climb images
* Please leave `PivotPoint` and `PixelsPerUnit` as default values if you don't know how they work
* You may use any name for the folder and files as long as everything is specified correctly in the manifest.json, but for the folder it is recommended to use the naming convention `<hat name>_<creator name>` for clarity
* Submit your entire hat bundle as a `.zip` file in the discord
* Please see the `ExampleHat_AJMix` bundled in the build for an example of how the new system works
* If the new system is too complicated, you may always continue using the **Old System**

### Old System:
* Download the template used to make the Custom Hat for Town Of Impostors **(Big Thanks to Con No 1 for the template)**:
  * Download .psd template [here](https://github.com/AJMix/TownOfImpostors/releases/download/v1.8.2.1/ConTemplate.psd)
  * Download .png template [here](https://github.com/AJMix/TownOfImpostors/releases/download/v1.8.2.1/ConTemplate.png)
* Draw your hat on the template and save in PNG format, with a unique name (make sure to also hide the crewmate and shadow). Preserve the resolution.
  
* **IMPORTANT:** Please follow this naming convention `<HatName>_<Credits>_<Modifiers>` for your PNG. See below for list of modifiers. If you want spaces in your names, use `-` to represent spaces. For example, `Bouncy-Hat` will be processed into `Bouncy Hat` inside the game.

**Example Names:** `Wing_Spaced-AJMix_back.png`, `Bouncy-Hat_AJMix_bounce.png`, `BouncyWings_AJMix_back_bounce.png`, `Simple-Hat_AJMix.png`, `Advanced-Hat_AJMix_bounce_anycolor_-1.1f_+2.3f.png`

* Place the custom hat png into the `TownOfImpostors_CustomHats` which can be found inside of the Among Us directory you have the mod installed (launch the game once and start a lobby with the mod or create the folder yourself if it does not exist)

* Your custom hat should now appear in the hats tab **locally**. If you want everyone to see the same thing **make sure everyone has the same hats in the custom hats folder.**

---

### Modifiers
*All hat modifiers are **case sensitive**!*


`_back`
> If you want your hat to be behind the crewmate (i.e. wings). 

`_bounce`
> If you want it to bounce while the crewmate walks.

`_anycolor`
> **From v1.8.2 onwards**, you'll be able to also add this as an additional modifier to have your hat match the colour of your crewmate. You'll need to use **Red** _(Hex: FF0000)_ for the base colour, and **Blue** _(Hex: 0000FF)_ for the shading. See example of how this is done here: 

![ExampleByDark](https://user-images.githubusercontent.com/78827892/114481635-dacf1380-9bfc-11eb-8032-e839df7240ec.PNG)  

### Advanced Modifiers
*All hat modifiers are **case sensitive**!*


`_0.0f_0.0f`  
> **From v1.8.6 onwards**, you can now add **X** and **Y** offsets to the name to position the hat more accurately in the menu i.e. `Simple-Hat_AJMix_-0.5f_+0.3f`. You need to specify both an **X** and a **Y** offset. Placing a **+** or **-** in front will indicate whether it should be positive or negative. _Placing no symbols will default it to positive._ The offsets must follow the exact example as shown, with a decimal number followed by an _"**f**"_.

## Want to add your hat as part of the mod so everyone can use it?
* Simply follow the same steps above to create a Custom Hat, please join the discord server and post your hat in the custom hat channel there so it can be ready to add in the next release. Please also follow the naming convention so I know the hat name, credits and whether you'd like it to be added to the **back** of the crewmate and whether you'd like it to **bounce**.
* The Hat Name and Credits will be grabbed from the file name, as long as you have followed the naming convention. When someone wears your hat, credits will appear underneath the mod credits! (i.e. `AJ Scarf by AJMix`, `Dark Scarf by Darkbrussel`)
* I'll try my best to get your Custom Hat into the next release of Town Of Impostors!

## Where can I download more custom hats from the community?
Please join the discord to find more custom hats from the community, as well as download links!

---

<h1 id="customcolors">Custom Colors</h1>

**From v1.8.6 onwards**, you will be able to add your own custom colors.

Add your custom colors to the file `TownOfImpostors_CustomColors.txt` which can be found in the `TownOfImpostors_Data` folder. Please launch the game and create a lobby once if you don't see the folder or file, or manually create them yourselves. 

Follow this example to add a color:
> `255,255,255,255 220,220,220,255 Pure_White PWH`

Each part of the entry stands for this:
> `MainColor` `ShadingColor` `LongName` `ShortName`
> 
> For the colors the format is: R,G,B,A (values between 0-255)
> 
> Separate each part with a space, use `_` to represent spaces in the long name.

**In multiplayer, everyone must have the same `TownOfImpostors_CustomColors.txt` to see and use the same custom colors!**

---

<h1 id="streamermode">Streamer Mode</h1>

**From v1.7.1 onwards**, there is a new streamer mode that can be toggled on.

This makes it easier for streamers as they won't have to manually hide the code anymore on stream, it will be hidden automatically.

### How do I get the room code?
When you create a room, the room code will be copied to your clipboard. Simply paste it somewhere and pass it onto others.

If you accidentally copied something else before pasting the room code somewhere, you can get your copy/clipboard history by using `Windows Key + V`. Or you can just make another room.

---

# Roles, Abilities, Modifiers & Custom Options

### Keybindings
From 1.6.0 onwards, you can now use keys **1, 2, 3, 4, Z, X** to activate abilities.

### Gamemodes
- **Map Randomise Mode:** When toggled on, map will be randomised upon starting the game
- **All Crewmates Must Die Mode:** When toggled on, game will continue as long as a crewmate is alive (special win conditions still occur for Jester, Arsonist and Lovers)
- **Game Continues With Arsonist:** Toggles whether the game should continue as long as Arsonist is alive

### Extra Settings
- **Custom Role Eject Confirmation:** Enables ejects to show the special role of the player being ejected, assuming "Confirm Ejects" option is on
- **Same Roles Know Each Other:** Allows players of the same role to see each other (via highlighted names)
- **Comms Sabotage Causes Anonymity:** Improves the Comms Sabotage to turn everyone anonymous
- **Ghosts Use Crewmate Vision:** Ghosts will no longer have ghost vision (where they can see everything), they will now instead use normal crewmate vision. Impostors are unaffected. _This option is recommended if there is a Doctor in the game_
- **Disable Body Report:** Toggles on/off body reporting (to get a different kind of gameplay)
- **Dead Player See All Roles:** Toggles whether dead players should see all roles (after a meeting only)
- **Can Vent With Body:** Toggle whether players can vent with bodies
- **% Boddy Drag Speed Modifier:** % Movement Modifier for dragging bodies

## Crewmate Team

The special roles in the Crewmate Team. The goal of the Crewmate Team is to combine their abilities and knowledge to **find the Impostors**. The Crewmate Team will win if all Impostors are ejected or killed.

### Sheriff
The Sheriff is a role that has the ability to kill Impostors. However, if they attempt to kill a fellow crewmate, they will lose their own life instead as a punishment.
<details>
<summary>Custom Options</summary>
  
+ **% Sheriff Chance:** Chance of a Sheriff being added to the role selection pool
+ **# Max Sheriff Count:** The maximum number of Sheriffs that can be added to the role selection pool
+ **Sheriff Kill Cooldown:** Kill cooldown for the Sheriff
+ **Show Sheriff:** Shows the Sheriff to other players (via a highlighted name)
+ **Innocent Target Also Dies:** The Innocent target will also be killed along with the Sheriff
+ **Jester Is Enemy:** Jester will no longer count as "Innocent"
+ **Arsonist Is Enemy:** Arsonist will no longer count as "Innocent"
+ **Sheriff Does Not Die:** Toggles whether Sheriff will die as a punishment or not

</details>

### Doctor
The Doctor is a role that has the ability to revive dead players. However, this means they are also able to revive Impostors that have been killed by the Sheriff.
<details>
<summary>Custom Options</summary>
  
+ **% Doctor Chance:** Chance of a Doctor being added to the role selection pool
+ **# Max Doctor Count:** The maximum number of Doctors that can be added to the role selection pool
+ **Doctor Revive Cooldown:** Cooldown for the Doctor Revive Ability
+ **Doctor Revive Time:** The time is takes for a Doctor to successfully revive a player
+ **Start Cooldown On Failed Revives:** Start Revive Ability Cooldown if revive fails (if body is removed or disposed)
+ **Medbay Revive Only:** Only allow revives in the Medbay location of a map
+ **Lose Role On Revive:** Crewmates with special roles lose their role if revived (Does not affect Jester & Arsonist)
+ **Retrieve Body Ability:** Toggle the Retrieve Body Ability
+ **Retreive Body Cooldown:** Cooldown for the Retrieve Body Ability

</details>

### Agent
The Agent is a powerful role that has abilities allowing them to access map intel from anywhere. This includes the admin table map, security cameras, door logs and vitals if any are accessible. This gives them much more information on what is going on around the map, but they shouldn't neglect their tasks either.
<details>
<summary>Custom Options</summary>
  
+ **% Agent Chance:** Chance of a Agent being added to the role selection pool
+ **# Max Agent Count:** The maximum number of Agents that can be added to the role selection pool
+ **Agent Tech Cooldown:** The cooldown of Agent's abilities (the cooldowns are separate between the abilities, but they will all have the same cooldown time)
+ **Can Use Admin Map:** Agent can activate Admin Map
+ **Can Use Cameras:** Agent can activate Cameras _(Skeld and Polus Only)_
+ **Can Use Door Logs:** Agent can activate Door Logs _(MIRA HQ Only)_
+ **Can Use Vitals:** Agent can activate Vitals _(Polus Only)_
+ **Agent Abilities Share Cooldown:** Toggle whether all agent abilities go into cooldown after using one ability

</details>

### Detective
The Detective is a role that can see footprints and get extra information when reporting bodies (They will get a body report in chat only they can see, which shows time of death and if the body was moved or not). They should use this ability to track down Impostors, but they should also be careful not to frame the wrong person.
<details>
<summary>Custom Options</summary>
  
+ **% Detective Chance:** Chance of a Detective being added to the role selection pool
+ **# Max Detective Count:** The maximum number of Detectives that can be added to the role selection pool
+ **Enable Body Scan Ability:** Toggles body scan ability for Detective
+ **Body Scan Cooldown:** Body scan ability cooldown
+ **Body Scan Radius:** Body scan radius
+ **Footprint Duration:** How long the footprints will last in seconds
+ **Anonymous Footprints:** Whether the footprints should be anonymous or not
+ **Extra Information On Report:** If Detective reports a body, they will get an additional "Body Report" via messages (which only they can see). Shows how long the player has been dead for, as well as whether the body has been moved or not. Also shows whether the body was poisoned.
+ **Killers Leave Bloody Prints:** Killers _(includes both Sheriffs & Impostors)_ will leave bloody footprints after a kill
+ **Bloody Prints Duration:** Duration for how long Killers should have bloody footprints
+ **Disguised Footprints:** Toggles whether Impostors leave behind disguised footprints if they are disguised

</details>

### Plumber
The Plumber is a role that can use vents to travel around. They can also stay in vents to observe the room. But they should be careful not to be suspected as the Impostor or noticed by the Impostor.
<details>
<summary>Custom Options</summary>
  
+ **% Plumber Chance:** Chance of a Plumber being added to the role selection pool
+ **# Max Plumber Count:** The maximum number of Plumbers that can be added to the role selection pool
+ **Retrieve Body Ability:** Toggle the Retrieve Body Ability
+ **Retreive Body Cooldown:** Cooldown for the Retrieve Body Ability

</details>

### Informant
The Informant is a role that can see other roles after they are finished with ALL their tasks. They will be "Informed" after finishing tasks, but should also be careful of Impostors that are notified about them. The Informant can only be informed or revealed after **completing at least one task**.

**NOTE: Comms Anonymous Sabotage (if toggled on) will prevent Informant from seeing roles, even in meetings. This is the counterplay to Informant.**

<details>
<summary>Custom Options</summary>
  
+ **% Informant Chance:** Chance of a Informant being added to the role selection pool
+ **# Max Informant Count:** The maximum number of Informants that can be added to the role selection pool
+ **Impostors Are Notified:** Toggles whether Impostors will be notified and also have the Informant revealed to them
+ **Tasks Left When Impostors Notified:** How many tasks left for the Informant before Impostors are notified about them
+ **Show Arrows (Informants And Impostors):** Show arrows pointing to Informants/Impostors if either have been revealed. These can only be seen by Informants or Impostors depending on options that are enabled
+ **See Jester After Tasks:** Toggles whether Informants can see Jesters after tasks
+ **See Arsonists After Tasks:** Toggles whether Informants can see Arsonists after tasks
+ **See Crewmate Roles After Tasks:** Toggles whether Informants can see Crewmate special roles _(if any)_ after tasks
+ **Highlight Names In Meetings:** Toggles whether names are highlighted in meetings too _(for Informants & Impostors)_

</details>

### Trickster
The Trickster is a role that can create a decoy to trick the Impostor. If the Impostor kills the decoy, they will go into kill cooldown which will slow them down. However, the Sheriff is also able to kill decoys. The Trickster may also swap positions with their decoys to avoid danger or cover more ground quicker.
<details>
<summary>Custom Options</summary>
  
+ **% Trickster Chance:** Chance of a Trickster being added to the role selection pool
+ **# Max Trickster Count:** The maximum number of Tricksters that can be added to the role selection pool
+ **Trickster Decoy Cooldown:** Cooldown duration for the Trickster Decoy ability
+ **Trickster Decoy Duration:** Duration of how long the decoy should last
+ **Enable Trickster Swap Ability:** Allow Trickster to swap positions with the decoy
+ **Trickster Swap Cooldown:** Cooldown duration for the Trickster Swap ability
+ **Trickster Disguise Ability:** Toggles whether triggers can disguise as other players
+ **Trickster Disguise Cooldown:** Cooldown for Trickster disguise
+ **Trickster Disguise Duration:** Duration for Trickster's disguise

</details>

### Operative
The Operative is a role that can place down gadgets that allow them to track other players. A sticky tracker can be placed down that'll stick to other players and reveal them for the duration. An AOE sensor can be placed down to reveal players in an area (revealed players will be anonymous) for a duration. **All revealed players will be shown on the map.** The Operative gadgets are only visible to the Operative.
<details>
<summary>Custom Options</summary>
  
+ **% Operative Chance:** Chance of an Operative being added to the role selection pool
+ **# Max Operative Count:** The maximum number of Operatives that can be added to the role selection pool
+ **# Max Tracker Storage:** Maximum number of trackers that can be stored
+ **Tracker Duration:** How long Trackers should last before disappearing
+ **Tracker Cooldown:** Cooldown to gain a tracker charge
+ **# Max Sensor Storage:** Maximum number of sensors that can be stored
+ **Sensor Radius:** Size of the sensor radius for revealing players
+ **Sensor Duration:** How long Sensors should last before disappearing
+ **Sensor Cooldown:** Cooldown to gain a sensor charge
+ **Show Tracking Arrows:** Toggle whether the tracker should also show a tracking arrow when tracking someone
+ **Track Dead Bodies:** Toggle whether trackers/sensors should continue tracking dead players

</details>

### Mayor
The Mayor is a role that gets additional votes they can use to influence the results of a meeting. They are able to store votes each meeting and can add votes to any player in the meeting (or skip vote) at any time, as long as they have not locked in their final vote. They should use this if they want to force someone to be voted out or force a skip vote. But they should be careful not to reveal themselves too early.

<details>
<summary>Custom Options</summary>
  
+ **% Mayor Chance:** Chance of a Mayor being added to the role selection pool
+ **Enable Mayor:** Toggle whether Mayor is enabled or not
+ **Mayor Cannot Be Lover:** Toggles whether a Mayor can be lover or not
+ **Starting Vote Bank:** How many votes should Mayor start with
+ **Votes Gained Per Meeting:** How many votes Mayor should gain per meeting
+ **Enable Emergency Ability:** Toggle Mayor's Emergency Meeting Ability
+ **Emergency Ability Cooldown:** Mayor Emergency Meeting Ability cooldown
+ **Emergency Ability Limit:** Maximum number of times Mayor can use the ability

</details>

## Neutral Team

### Jester
The Jester is a role with no abilities and no tasks to do (they get fake tasks like Impostors). They are in their own team, and their goal is to get themselves ejected from the ship and make sure not to get killed by the Impostors. They will win instantly if ejected from the ship. However, if they are killed, they will have no way to win and essentially lose. The have extra abilities to help them act suspicious, such as dragging bodies, leaving bloody footprints and using vents.
<details>
<summary>Custom Options</summary>
  
+ **% Jester Chance:** Chance of a Jester being added to the role selection pool
+ **Enable Jester:** Allow Jester to be added to the role selection pool 
+ **Jester Can Fix Sabotages:** Allow Jester to fix sabotages
+ **Jester Wins From Sheriff Kill:** Jester will win if killed by the Sheriff
+ **Jester Bloody Footprints Ability:** Toggles whether the Jester can leave bloody footprints to trick the detective
+ **Jester Body Drag Ability:** Toggles whether the Jester can drag bodies
+ **Jester Can Use Vents:** Toggles whether the Jester can use vents
+ **Retrieve Body Ability:** Toggle the Retrieve Body Ability
+ **Retreive Body Cooldown:** Cooldown for the Retrieve Body Ability

</details>

### Arsonist
The Arsonist is a role that aims to douse everyone alive and igniting them all to win alone. They need to do this before the Crewmate Team wins by finding all the Impostors. They have no tasks (they get fake tasks like Impostors), but should be careful not to be suspected as they have to say close for the duration of time they are dousing. They should also be careful not to be killed by the Impostor.
<details>
<summary>Custom Options</summary>
  
+ **% Arsonist Chance:** Chance of a Arsonist being added to the role selection pool
+ **Enable Arsonist:** Allow Arsonist to be added to the role selection pool 
+ **Douse Time:** How long it takes for Arsonist to douse a target
+ **Arsonist Can Fix Sabotages:** Toggles whether Arsonists can fix sabotages
+ **Arsonist Must Refuel:** Toggles whether Arsonists must refuel after set amount of douses
+ **# Douses Stored:** Number of successful Douses before Arsonists must refuel _(if refuel option is toggled on)_

</details>

## Impostor Team

### New Abilities:
- Drag & Drop Bodies - The Impostor may now drag & drop bodies to reposition them, bodies may also be dragged through vents
- Dispose Body - The Impostor can dispose a body they are dragging, if they are close to or inside a vent. A bloodstain is left behind to give crewmates a clue
- Disguise/Sample DNA - The Impostor can disguise as another player, by first sampling their DNA
- Decoy - The Impostor can drop a decoy, much like the Trickster, and can drop decoys of other players by first disguising as them
- Swap - The Impostor can swap positions with their decoy
- Blind Trap - The Impostor can leave blind traps that will blind players that walk on it
- Poison - The Impostor can poison a player, they will die after a set duration

### Impostor Settings

<details>
  
<summary>Custom Options</summary>
  
+ **Enable Impostor Roles:** Enable separate Impostor roles. If this is toggled off, the Impostor is a "Super Impostor" with all abilities
+ **Enable Impostor Abilities:** This option is available is Impostor Roles is toggled off. Enables/Disables abilities for the normal Impostor
+ **Impostors Can Kill Each Other:** Allows Impostors to target and kill each other
+ **Impostors Do Not Know Each Other:** Toggles whether Impostors know each other
+ **Impostors Can Kill Inside Vents:** Toggles whether Impostors can kill any other players inside of vents (if they are in the vent too)
+ **Enable Impostor Messaging:** Toggle on/off Impostor Comms. Impostor Comms allows Impostors to chat to each other in-game via the chat messaging system, outside of meetings

</details>

### Dragger
The Dragger is an Impostor role that can drag & drop dead bodies. They are also able to dispose the dead bodies in vents.

<details>
<summary>Custom Options</summary>
  
+ **% Dragger Chance:** Chance of a Dragger being added to the role selection pool
+ **Dragger Count:** The maximum number of Draggers that can be added to the role selection pool
+ **Drag And Drop Ability:** Toggle the Drag and Drop Ability
+ **Dispose Body Ability:** Toggle the Dispose Body Ability
+ **Dispose Body Cooldown:** Cooldown for the Dispose Body Ability
+ **Retrieve Body Ability:** Toggle the Retrieve Body Ability
+ **Retreive Body Cooldown:** Cooldown for the Retrieve Body Ability
+ **Vents Hold Multiple Bodies:** Toggles whether multiple bodies can be disposed in one vent (default is 1 body maximum if toggled off)

</details>

### Morphling
The Morphling is an Impostor role that can sample DNA of other players and disguise into them, confusing everyone.

<details>
<summary>Custom Options</summary>
  
+ **% Morphling Chance:** Chance of a Morphling being added to the role selection pool
+ **Morphling Count:** The maximum number of Morphlings that can be added to the role selection pool
+ **Disguise Ability:** Toggle the Disguise Ability
+ **Disguise Cooldown:** Cooldown for the Disguise Ability
+ **Disguise Duration:** How long the Disguise lasts for in seconds

</details>

### Deceiver
The Deceiver is an Impostor role that can leave decoys and swap to them, confusing players and allowing them to reposition themselves.

<details>
<summary>Custom Options</summary>
  
+ **% Deceiver Chance:** Chance of a Deceiver being added to the role selection pool
+ **Deceiver Count:** The maximum number of Deceivers that can be added to the role selection pool
+ **Enable Decoy Ability:** Toggle the Decoy Ability for Impostors
+ **Decoy Cooldown:** Cooldown for the Decoy ability
+ **Decoy Duration:** Duration for how long the Decoy will last
+ **Enable Decoy Swap Ability:** Toggle the Decoy Swap Ability for Impostors
+ **Decoy Swap Cooldown:** Cooldown for the Decoy Swap Ability

</details>

### Viper
The Viper is an Impostor role that can blind and poison other players.

<details>
<summary>Custom Options</summary>
  
+ **% Viper Chance:** Chance of a Viper being added to the role selection pool
+ **Viper Count:** The maximum number of Vipers that can be added to the role selection pool
+ **Blind Trap Ability:** Toggle the blind trap ability
+ **Blind Trap Charges:** Max charges of blind traps Viper can hold
+ **Blind Trap Cooldown:** Blind trap cooldown to regain a charge
+ **Blind Trap Duration:** How long the blind trap should last
+ **Blind Duration:** How long players are blinded for
+ **Poison Ability:** Toggle the poison ability
+ **Poison Duration:** Duration before player is killed by poison
+ **Poison Additional Kill Cooldown:** How much extra cooldown is added to the kill button
+ **Poison Cure Duration:** How long it takes to cure the poison in medbay
+ **Poison Continues In Meeting:** Toggles whether Poison Timer should continue ticking in meetings

</details>

</details>

### Sniper
The Sniper has the ability to kill players during meetings if they are able to guess their roles. But they may be punished for wrong guesses. They may also use a Sniper in-game if toggled on. (Note: Sniper Rotation is not synced between players, so you will not see where the player is aiming)

**REMINDER:** Toggling on the Sniper Rifle will hide/replace the original Kill Button

<details>
<summary>Custom Options</summary>
  
+ **% Sniper Chance:** Chance of a Sniper being added to the role selection pool
+ **Sniper Count:** The maximum number of Snipers that can be added to the role selection pool
+ **Max Snipe Per Meeting:** The number of times the Sniper can attempt to kill players in meetings with role guesses
+ **Sniper Dies On Wrong Guess:** Punish the Sniper with death if they guess wrong
+ **Sniper Rifle Ability:** Toggled On/Off the Sniper Rifle to use between meetings, a long range killing ability _**(NOTE: This hides/replaces the normal kill)**_
+ **Sniper Rifle Cooldown:** Cooldown for Sniper Rifle Shots
+ **Rifle Unholster Cooldown:** Cooldown to unholster the Sniper Rifle
+ **Rifle Holster Cooldown:** Cooldown to holster the Sniper Rifle
+ **Gunshot Revealed Duration:** Duration for how the Sniper Shot Reveal Arrow lasts

</details>

**If seperate Impostor Roles are disabled, the normal Impostors will use all abilities (configured with the same custom options as the separate roles). Basically every Impostor is a "Predator"**

## If separate Impostor Roles are enabled:
### Tier 1 Impostors:
- **Dragger** has the drag/drop & dispose body abilities
- **Morphling** has the sample & disguise abilities
- **Deceiver** has the decoy & swap abilities
- **Viper** has the blind trap & poison abilities

### Tier 2 Impostors:
- **Hitman** has the combined abilities of Dragger and Morphling
- **Joker** has the combined abilities of Morphling and Deceiver
- **Assassin** has the combined abilities of Dragger and Viper

### Tier 3 Impostors:
- **Predator** has the abilities of all Impostor roles

**Any Impostor without a special Impostor role will be a normal vanilla Impostor with no abilities. Impostor Role abilities are configured with the same options used to configure the normal Impostor**

## Modifiers

### Lovers
This activates the Lovers modifier. Two players are selected as random to be lovers (if applicable). Impostors can also be selected as Lovers. Jesters & Arsonists cannot be selected as Lovers. There can not be more than 1 Impostor Lover.

Lovers can still get their own special roles, and can still win as normal with their respective teams.

However, the Lovers can achieve a special "Lovers Win". The goal of the Lovers is to stay alive together and win together at the end. Lovers will achieve the special Lovers Win if they are both among the **last 3 players** standing. The only exception to this is if the custom option **Game Continues With Arsonist** is toggled on and the Arsonist is among the last 3. The game will continue as long as the Arsonist is alive.

Lovers are given the ability to chat with each other via a special Lovers Chat in-between meetings.

<details>
<summary>Custom Options</summary>
  
+ **% Lovers Chance:** Chance for Lovers to appear
+ **Enable Lovers:** Toggles Lovers on/off
+ **Lovers Die Together:** Toggles whether Lovers should die together (if one dies, the other dies, like a life link)

</details>

### Giant
This activates the Giant modifier. A Giant player will have a larger sight radius to see more things, but will suffer from slower movement speed.

<details>
<summary>Custom Options</summary>
  
+ **% Giant Chance:** Chance for Giant to appear
+ **Enable Giant:** Toggles Giant on/off
+ **% Movement Modifier:** Percentage movement modifier for Giant
+ **% Vision Modifier:** Percentage vision modifier for Giant

</details>

### Tiny
This activates the Tiny modifier. A Tiny player will be able to move around faster, but will suffer from lower vision (opposite of Giant)

<details>
<summary>Custom Options</summary>
  
+ **% Tiny Chance:** Chance for Tiny to appear
+ **Enable Tiny:** Toggles Tiny on/off
+ **% Movement Modifier:** Percentage movement modifier for Tiny
+ **% Vision Modifier:** Percentage vision modifier for Tiny

</details>

### Nightowl
This activates the Nightowl modifier. A Nightowl will be able to see better when lights are out compared to other players, but will suffer from worse vision when lights are on.

<details>
<summary>Custom Options</summary>
  
+ **% Nightowl Chance:** Chance for Nightowl to appear
+ **Enable Nightowl:** Toggles Nightowl on/off
+ **% Lights On Vision Modifier:** Percentage Lights On Vision modifier for Nightowl
+ **% Lights Off Vision Modifier:** Percentage Lights Off Vision modifier for Nightowl

</details>

# How does role assignment work?
The role selection works as follows:
For each role, it will attempt to add that to the selection pool **X** number of times, where **X** is the maximum count. The chance of the role being added to the selection pool each time is based on the percentage chance set in the custom options for the specified role.

Once the selection pool is filled, the roles in there will then be randomly assigned to Crewmates (who are not already Impostors and don't already have a special role). As long as there are roles in the pool to assign and Crewmates to assign them to, they will be assigned out. If there are no more roles to be assigned out, the remaining players will just stay as normal Crewmates.

Example:
_**Sheriffs - # Max Count: 3 | % Chance: 50**_

This means that the role selection will try to put 3 sheriffs into the pool, at 50% chance each time. So the pool can end up with 0, 1, 2 or even the maximum of 3 Sheriffs.

---

# FAQ
 
### Can you play Proximity Chat (Crewlink) with it?
Yes, Crewlink supports Among Us Modifications

### Can this mod work with other mods?
I cannot guarantee that this mod will work with other mods. There will likely be conflicts. You will have to test yourself. 

### Do my friends need to install the mod to play it together?
Yes. Every player in the lobby must have the mod installed. Please don't use and play mods in unorganised public lobbies.

### Can you get banned for playing on public servers?
At the current state of the game there is no perma ban system, though this may change depending on the stance of the Among Us developers. The mod is designed in a way that it does not send prohibited server requests. In a public lobby with randoms, with only you having the mod installed, you would either be kicked for strange behaviour or have a desync between you and other users that do not have the same mods, or both. In short, as long as this mod is played among friends in your own private lobby, you're safe.

If you are really worried, I recommend checking out <a href="https://github.com/Impostor/Impostor">Impostor</a> to start your own custom, private server. (You may have to disable their AntiCheat implementation for it to work with mods like this).
**Still, a disclaimer that you use this mod at your own risk and I am not responsible for any account suspensions that may occur from the use of this mod.**

### How can I join servers of a custom region?
This functionality has been removed from 1.6.0 onwards. Please look into using <a href="https://github.com/MoltenMods/Unify">Unify</a>

### Can this mod work with controllers?
This mod was not made to be compatible with controllers in mind; it was intended to be played with keyboard and mouse.

---

<h1 id="troubleshooting">Troubleshooting</h1>

### The mod isn't installed or game doesn't launch
- Please make sure you're using the latest version of the mod and the correct version of Among Us for it
- Please make sure you're using Windows, this mod is not compatible on Android, Mac or any other OS/devices
- Please make sure you're using this with the **Steam** version of Among Us; this is not compatible with the itch.io version unfortunately
- Please make sure you're not loading other mods along with this one
- The first time launching the mod may take a while, so please allow a minute before worrying that nothing is appearing. If nothing has happened for a while, please open your Task Manager (CTRL+ALT+DEL) and close the Among Us process, then attempt launching again.
- Make sure you have followed all the <a href="#installation">installation steps</a>, especially launching the game via the Among Us.exe file in the modified game directory.
- Try uninstalling the mod (see uninstalling the mod in the Installation Steps) and following the installation steps again
- If you're using a Mod Manager to install the mod, it is not guaranteed to work
- You might be missing some cpp libs (software libraries used by the mod); please install Visual C++ redistributable packages [x86](https://aka.ms/vs/16/release/vc_redist.x86.exe) & [x64](https://aka.ms/vs/16/release/vc_redist.x64.exe)

### The mod still doesn't work or found a bug?
You can <a href="https://github.com/AJMix/TownOfImpostors/issues/new">raise an issue within GitHub</a> documenting your issue. You will need to be logged into GitHub to do this.
For any bugs, take a quick check if your bug has already been listed under the below [Known Issues](#known-issues) or if it has already been reported. Please give as much detail as possible regarding the issue, including steps to reproduce it if possible. If it exists, please also attach your **LogOutput.log**, generated in the Among Us\BepInEx\ folder.

## Known Issues
- When updating from version to version, settings can bug and cause unintended effects. This is due to how new custom settings are being added in each update. If you are getting strange bugs occurring with the settings, try manually settings everything again (to overwrite the saved settings on your computer) by manually toggling options on and off, setting timers and settings counts. You can also do a hard reset by running vanilla among us and creating a lobby, then reopening among us with this mod. In v1.5.0 onwards, there is a new reset settings button the host can make use of to do a hard reset on all custom settings to reset everything to default values

- Disconnections in the middle of the game can cause bugs to occur, and the only way to fix them would be starting a new game or restarting the game. This mod was made with the assumption that no one would disconnect as disconnections are a whole other edgecase to fix. Future updates will hopefully fix this, but for now, just start another game or restart the client if a disconnection causes your game to bug

---

# Contact & Donations

### Contact:
- **Discord:** AJMix#1111
- **Email:** <a href="mailto:ajmixdev@gmail.com">ajmixdev@gmail.com</a>

### Updates:
- **Twitter:** <a href="https://twitter.com/itsAJMix">itsAJMix</a>
- **Youtube:** <a href="https://www.youtube.com/user/AJMixChannel">AJMix</a>
- **Discord Server: https://discord.gg/xpsKVpUf4T**

### Donations:
<a href="https://www.paypal.com/donate?hosted_button_id=M2FL98EWXTQDE"><img src ="https://www.paypalobjects.com/en_US/DK/i/btn/btn_donateCC_LG.gif" alt="Donate with PayPal button" ></img></a>

Buy me a coffee at [Ko-fi](https://ko-fi.com/ajmix)

All donations are appreciated and will go towards the development of mods.

---

# Credits

**_Please let me know if you'd like me to attach a social media next to your name, change your name or remove your name from the list._**

### Big thanks to the following Donator(s):
**Bernie Choy**

### Big thanks to the following for supporting in the development of the mod:
- **Darkbrussel** for the Artwork
- **JonyKasual** for thorough testing and general support

---

<h1>License</h1>
<a href="https://github.com/BepInEx/BepInEx">BepinEx</a> is distributed under <b>LGPL-2.1</b> License.</p>


## *Note: This repository is an unofficial continuation of Town of Us due to the original repository being discontinued.*

![LOGO](./Images/TOU-logo.png)
![Roles](./Images/Roles.png)

An Among Us mod that adds a bunch of roles, modifiers and game settings

Join our [Discord](https://discord.gg/ugyc4EVUYZ) if you have any problems or want to find people to play with!

**Crewmate Roles**
- [Aurial](#aurial)
- [Detective](#detective)
- [Haunter](#haunter)
- [Investigator](#investigator)
- [Mystic](#mystic)
- [Oracle](#oracle)
- [Seer](#seer)
- [Snitch](#snitch)
- [Spy](#spy)
- [Tracker](#tracker)
- [Trapper](#trapper)
- [Sheriff](#sheriff)
- [Vampire Hunter](#vampire-hunter)
- [Veteran](#veteran)
- [Vigilante](#vigilante)
- [Altruist](#altruist)
- [Medic](#medic)
- [Engineer](#engineer)
- [Imitator](#imitator)
- [Mayor](#mayor)
- [Medium](#medium)
- [Prosecutor](#prosecutor)
- [Swapper](#swapper)
- [Transporter](#transporter)

**Neutral Roles**
- [Amnesiac](#amnesiac)
- [Guardian Angel](#guardian-angel)
- [Survivor](#survivor)
- [Doomsayer](#doomsayer)
- [Executioner](#executioner)
- [Jester](#jester)
- [Phantom](#phantom)
- [Arsonist](#arsonist)
- [Juggernaut](#juggernaut)
- [Plaguebearer](#plaguebearer)
- [The Glitch](#the-glitch)
- [Vampire](#vampire)
- [Werewolf](#werewolf)

**Impostor Roles**
- [Escapist](#escapist)
- [Grenadier](#grenadier)
- [Morphling](#morphling)
- [Swooper](#swooper)
- [Venerer](#venerer)
- [Bomber](#bomber)
- [Traitor](#traitor)
- [Warlock](#warlock)
- [Blackmailer](#blackmailer)
- [Janitor](#janitor)
- [Miner](#miner)
- [Undertaker](#undertaker)

**Modifiers**
- [Aftermath](#aftermath)
- [Bait](#bait)
- [Diseased](#diseased)
- [Frosty](#frosty)
- [Multitasker](#multitasker)
- [Torch](#torch)
- [Button Barry](#button-barry)
- [Flash](#flash)
- [Giant](#giant)
- [Radar](#radar)
- [Lovers](#lovers)
- [Sleuth](#sleuth)
- [Tiebreaker](#tiebreaker)
- [Disperser](#disperser)
- [Double Shot](#double-shot)
- [Underdog](#underdog)

-----------------------
# Releases
| Among Us - Version| Mod Version | Link |
|----------|-------------|-----------------|
| 2023.6.13s & 2023.6.13e | v5.0.1 | [Download](https://github.com/eDonnes124/Town-Of-Us/releases/download/v5.0.1/ToU.v5.0.1.zip) |
| 2023.6.13s & 2023.6.13e | v5.0.0 | [Download](https://github.com/eDonnes124/Town-Of-Us/releases/download/v5.0.0/ToU.v5.0.0.zip) |
| 2023.3.28s & 2023.3.28e | v4.0.6 | [Download](https://github.com/eDonnes124/Town-Of-Us/releases/download/v4.0.6/ToU.v4.0.6.zip) |
| 2023.3.28s & 2023.3.28e | v4.0.5 | [Download](https://github.com/eDonnes124/Town-Of-Us/releases/download/v4.0.5/ToU.v4.0.5.zip) |
| 2023.3.28s & 2023.3.28e | v4.0.4 | [Download](https://github.com/eDonnes124/Town-Of-Us/releases/download/v4.0.4/ToU.v4.0.4.zip) |
| 2023.2.28s & 2023.2.28e | v4.0.3 | [Download](https://github.com/eDonnes124/Town-Of-Us/releases/download/v4.0.3/ToU.v4.0.3.zip) |
| 2022.12.14s & 2022.12.14e | v4.0.2 | [Download](https://github.com/eDonnes124/Town-Of-Us/releases/download/v4.0.2/ToU.v4.0.2.zip) |
| 2022.12.14s & 2022.12.14e | v4.0.1 | [Download](https://github.com/eDonnes124/Town-Of-Us/releases/download/v4.0.1/ToU.v4.0.1.zip) |
| 2022.12.14s & 2022.12.14e | v4.0.0 | [Download](https://github.com/eDonnes124/Town-Of-Us/releases/download/v4.0.0/ToU.v4.0.0.zip) |
| 2022.10.25s & 2022.10.25e | v3.4.0 | [Download](https://github.com/eDonnes124/Town-Of-Us/releases/download/v3.4.0/ToU.v3.4.0.zip) |
| 2022.8.24s & 2022.8.24e & 2022.9.20s & 2022.9.20e | v3.3.2 | [Download](https://github.com/eDonnes124/Town-Of-Us/releases/download/v3.3.2/ToU.v3.3.2.zip) |
| 2022.8.24s & 2022.8.24e & 2022.9.20s & 2022.9.20e | v3.3.1 | [Download](https://github.com/eDonnes124/Town-Of-Us/releases/download/v3.3.1/ToU.v3.3.1.zip) |
| 2022.8.24s & 2022.8.24e & 2022.9.20s & 2022.9.20e | v3.3.0 | [Download](https://github.com/eDonnes124/Town-Of-Us/releases/download/v3.3.0/ToU.v3.3.0.zip) |
| 2022.6.21s & 2022.6.21e & 2022.7.12s & 2022.7.12e | v3.2.0 | [Download](https://github.com/eDonnes124/Town-Of-Us/releases/download/v3.2.0/ToU.v3.2.0.zip) |
| 2022.3.29s & 2022.3.29e & 2022.4.19e | v3.1.0 | [Download](https://github.com/eDonnes124/Town-Of-Us/releases/download/v3.1.0/ToU.v3.1.0.zip) |
| 2022.3.29s & 2022.3.29e & 2022.4.19e | v3.0.1 | [Download](https://github.com/eDonnes124/Town-Of-Us/releases/download/v3.0.1/ToU.v3.0.1.zip) |
| 2022.3.29s & 2022.3.29e & 2022.4.19e | v3.0.0 | [Download](https://github.com/eDonnes124/Town-Of-Us/releases/download/v3.0.0/ToU.v3.0.0.zip) |
| 2021.12.15s & 2021.12.15e Until 2022.2.24s & 2022.2.24e | v2.6.5 | [Download](https://github.com/eDonnes124/Town-Of-Us/releases/download/v2.6.5/ToU.v2.6.5.zip) |
| 2021.12.15s & 2021.12.15e Until 2022.2.24s & 2022.2.24e | v2.6.4 | [Download](https://github.com/eDonnes124/Town-Of-Us/releases/download/v2.6.4/ToU.v2.6.4.zip) |
| 2021.6.30s & 2021.6.30e & 2021.7.20e | v2.6.4 | [Download](https://github.com/eDonnes124/Town-Of-Us/releases/download/v2.6.4/ToU.v2.6.4-2021.6.30.zip) |
| 2021.12.15s & 2021.12.15e Until 2022.2.24s & 2022.2.24e | v2.6.3 | [Download](https://github.com/eDonnes124/Town-Of-Us/releases/download/v2.6.3/ToU.v2.6.3.zip) |
| 2021.6.30s & 2021.6.30e & 2021.7.20e | v2.6.3 | [Download](https://github.com/eDonnes124/Town-Of-Us/releases/download/v2.6.3/ToU.v2.6.3-2021.6.30.zip) |
| 2021.12.15s & 2021.12.15e Until 2022.2.24s & 2022.2.24e | v2.6.2 | [Download](https://github.com/eDonnes124/Town-Of-Us/releases/download/v2.6.2/ToU.v2.6.2.zip) |
| 2021.6.30s & 2021.6.30e & 2021.7.20e | v2.6.2 | [Download](https://github.com/eDonnes124/Town-Of-Us/releases/download/v2.6.2/ToU.v2.6.2-2021.6.30.zip) |
| 2021.12.15s & 2021.12.15e Until 2022.2.24s & 2022.2.24e | v2.6.1 | [Download](https://github.com/eDonnes124/Town-Of-Us/releases/download/v2.6.1/ToU.v2.6.1.zip) |
| 2021.6.30s & 2021.6.30e & 2021.7.20e | v2.6.1 | [Download](https://github.com/eDonnes124/Town-Of-Us/releases/download/v2.6.1/ToU.v2.6.1.Old.zip) |
| 2021.12.15s & 2021.12.15e Until 2022.2.24s & 2022.2.24e | v2.6.0 | [Download](https://github.com/eDonnes124/Town-Of-Us/releases/download/v2.6.0/ToU.v2.6.0.zip) |
| 2021.6.30s & 2021.6.30e & 2021.7.20e | v2.6.0 | [Download](https://github.com/eDonnes124/Town-Of-Us/releases/download/v2.6.0/ToU.v2.6.0.Old.zip) |
| 2021.12.15s & 2021.12.15e Until 2022.2.24s & 2022.2.24e | v2.5.1 | [Download](https://github.com/eDonnes124/Town-Of-Us/releases/download/v2.5.1/ToU.v2.5.1.zip) |
| 2021.12.15s & 2021.12.15e Until 2022.2.24s & 2022.2.24e | v2.5.0 | [Download](https://github.com/eDonnes124/Town-Of-Us/releases/download/v2.5.0/ToU.v2.5.0.zip) |
| 2021.6.30s & 2021.6.30e & 2021.7.20e | v2.5.0 | [Download](https://github.com/eDonnes124/Town-Of-Us/releases/download/v2.5.0/ToU.v2.5.0.Old.zip) |
| 2021.12.15s & 2021.12.15e Until 2022.2.24s & 2022.2.24e | v2.4.2 | [Download](https://github.com/eDonnes124/Town-Of-Us/releases/download/v2.4.2/ToU.v2.4.2.zip) |
| 2021.12.15s & 2021.12.15e Until 2022.2.24s & 2022.2.24e | v2.4.1 | [Download](https://github.com/eDonnes124/Town-Of-Us/releases/download/v2.4.1/ToU.v2.4.1.zip) |
| 2021.11.9.5s & 2021.11.9.5e | v2.4.0 | [Download](https://github.com/eDonnes124/Town-Of-Us/releases/download/v2.4.0/ToU.v2.4.0.zip) |
| 2021.6.30s & 2021.6.30e & 2021.7.20e | v2.3.4 | [Download](https://github.com/eDonnes124/Town-Of-Us/releases/download/v2.3.4/ToU.v2.3.4.zip) |
| 2021.6.30s & 2021.6.30e & 2021.7.20e | v2.3.3 | [Download](https://github.com/eDonnes124/Town-Of-Us/releases/download/v2.3.3/ToU.v2.3.3.zip) |
| 2021.6.30s & 2021.6.30e & 2021.7.20e | v2.3.2 | [Download](https://github.com/eDonnes124/Town-Of-Us/releases/download/v2.3.2/ToU.v2.3.2.zip) |
| 2021.6.30s & 2021.6.30e & 2021.7.20e | v2.3.1 | [Download](https://github.com/eDonnes124/Town-Of-Us/releases/download/v2.3.1/ToU.v2.3.1.zip) |
| 2021.6.30s & 2021.6.30e & 2021.7.20e | v2.3.0 | [Download](https://github.com/eDonnes124/Town-Of-Us/releases/download/v2.3.0/ToU.v2.3.0.zip) |
| 2021.6.30s & 2021.6.30e & 2021.7.20e | v2.2.1 | [Download](https://github.com/polusgg/Town-Of-Us/releases/download/v2.2.1/TOU_221.zip) |
| 2021.6.30s & 2021.6.30e & 2021.7.20e | v2.2.0 | [Download](https://github.com/polusgg/Town-Of-Us/releases/download/v2.2.0/TOU_220.zip) |
| 2021.6.15s & 2021.6.15e | v2.1.4 | [Download](https://github.com/polusgg/Town-Of-Us/releases/download/v2.1.4/TOU_214.zip) |
| 2021.6.15s & 2021.6.15e | v2.1.3 | [Download](https://github.com/polusgg/Town-Of-Us/releases/download/v2.1.3/TownOfUs213_1.zip) |
| 2021.6.15s & 2021.6.15e | v2.1.2 | [Download](https://github.com/polusgg/Town-Of-Us/releases/download/v2.1.2/TownOfUs212_1.zip) |
| 2021.6.15s & 2021.6.15e | v2.1.1 | [Download](https://github.com/polusgg/Town-Of-Us/releases/download/v2.1.1/TownOfUs211_1.zip) |
| 2021.5.10s | v2.0.4 | [Download](https://github.com/polusgg/Town-Of-Us/releases/download/v2.0.4/TownOfUs-v2.0.4.zip) |
| 2021.5.10s | v2.0.3 | [Download](https://github.com/polusgg/Town-Of-Us/releases/download/v2.0.3/TownOfUs-v2.0.3.zip) |
| 2021.4.12s & 2021.4.14s | v2.0.2 | [Download](https://github.com/polusgg/Town-Of-Us/releases/download/v2.0.2/TownOfUs-v2.0.2.zip) |
| 2021.4.12s | v2.0.1 | [Download](https://github.com/polusgg/Town-Of-Us/releases/download/v2.0.1/TownOfUs-v2.0.1.zip) |
| 2021.3.31.3s | v2.0.0 | [Download](https://github.com/polusgg/Town-Of-Us/releases/download/v2.0.0/TownOfUs-v2.0.0.zip) |
| 2021.3.5s | v1.2.0 | [Download](https://github.com/polusgg/Town-Of-Us/releases/download/v1.2.0/TownOfUs-v1.2.0.zip) |
| 2021.3.5s | v1.1.0 | [Download](https://github.com/polusgg/Town-Of-Us/releases/download/v1.1.0/TownOfUs-v1.1.0-2021.3.5s.zip) |
| 2020.12.19s | v1.1.0 | [Download](https://github.com/polusgg/Town-Of-Us/releases/download/v1.1.0/TownOfUs-v1.1.0-2020.12.9s.zip) |
| 2020.12.19s | v1.0.3 | [Download](https://github.com/polusgg/Town-Of-Us/releases/download/v1.0.3/TownOfUs-v1.0.3.zip) |
| 2020.12.19s | v1.0.2 | [Download](https://github.com/polusgg/Town-Of-Us/releases/download/v1.0.2/TownOfUs-v1.0.2.zip) |
| 2020.12.19s | v1.0.1 | [Download](https://github.com/polusgg/Town-Of-Us/releases/download/v1.0.1/TownOfUs-v1.0.1.zip) |
| 2020.12.19s | v1.0.0 | [Download](https://github.com/polusgg/Town-Of-Us/releases/download/v1.0.0/TownOfUs-v1.0.0.zip) |

<details>
  <summary> Changelog </summary>
  <details>
  <summary> v5.0.1 </summary>
  <ul> <li>Bug Fix: Airship Ladders work again</li> </ul>
  </details>
  <details>
  <summary> v5.0.0 </summary>
  <ul> <li>New Role: Doomsayer</li> </ul>
  <ul> <li>New Role: Vampire</li> </ul>
  <ul> <li>New Role: Vampire Hunter</li> </ul>
  <ul> <li>New Role: Prosecutor</li> </ul>
  <ul> <li>New Role: Warlock</li> </ul>
  <ul> <li>New Role: Oracle</li> </ul>
  <ul> <li>New Role: Venerer</li> </ul>
  <ul> <li>New Role: Aurial</li> </ul>
  <ul> <li>Reworked Detective</li> </ul>
  <ul> <li>Reworked Mayor</li> </ul>
  <ul> <li>New Modifier: Frosty</li> </ul>
  <ul> <li>New Modifier: Aftermath</li> </ul>
  <ul> <li>Removed Blind</li> </ul>
  <ul> <li>Neutral Non-Killing settings split into Neutral Benign and Neutral Evil</li> </ul>
  <ul> <li>New Setting: First round shield for first death in prior game</li> </ul>
  <ul> <li>New Setting: Guardian Angel target evil percentage</li> </ul>
  <ul> <li>Removed Settings for disabling name plates and level numbers</li> </ul>
  <ul> <li>Guardian Angel targets can now be a Neutral Killer</li> </ul>
  <ul> <li>Bug Fix: Plaguebearer no longer turns into Pestilence early</li> </ul>
  <ul> <li>Added a new version of Snitch to Cultist</li> </ul>
  </details>
  <details>
  <summary> v4.0.6 </summary>
  <ul> <li>Bug Fixes: Reverted alot of the changes from the last few patches...</li> </ul>
  </details>
  <details>
  <summary> v4.0.5 </summary>
  <ul> <li>Bug Fix: Exile Functions now work when someone disconnects right after being assassinated</li> </ul>
  </details>
  <details>
  <summary> v4.0.4 </summary>
  <ul> <li>Compatibility with the new Among Us version v2023.3.28</li> </ul>
  <ul> <li>Haunter/Phantom/Traitor spawn adjustments</li> </ul>
  </details>
  <details>
  <summary> v4.0.3 </summary>
  <ul> <li>Compatibility with the new Among Us version v2023.2.28</li> </ul>
  <ul> <li>New Setting: Who can see dead players on admin (under Spy)</li> </ul>
  <ul> <li>Bug Fix: Transporter and Glitch get everyone alive on their transport/mimic menus</li> </ul>
  <ul> <li>Bug Fix: Undertaker can no longer drag bodies to unreportable positions</li> </ul>
  <ul> <li>Bug Fix: Players can no longer infinitely vent in Hide & Seek</li> </ul>
  <ul> <li>Bug Fix: Swapper swap bugs... all of them... I think</li> </ul>
  <ul> <li>Optimisation: As Imitator you no longer need to deselect someone to select another player</li> </ul>
  <ul> <li>Medic Shields and Guardian Angel Protects now stop a Bomb detonation and Arsonist ignites</li> </ul>
  </details>
  <details>
  <summary> v4.0.2 </summary>
  <ul> <li>Bug Fix: Cultist no longer doesn't automatically set the Impostors to 1 for the game mode</li> </ul>
  <ul> <li>Bug Fix: Dead people no longer interfere with how many people die to a bomb</li> </ul>
  <ul> <li>Added a new Examine Report to Detective</li> </ul>
  <ul> <li>Engineer Fix Per Round/Game changed to Uses throughout the game</li> </ul>
  <ul> <li>Made Medic & Trapper imitatable for the Imitator</li> </ul>
  <ul> <li>Added indications so the dead can see who the Guardian Angel and Executioner targets are</li> </ul>
  <ul> <li>Removed option for Snitch to be hidden on Game Start</li> </ul>
  </details>
  <details>
  <summary> v4.0.1 </summary>
  <ul> <li>Fixed the Kill Button not working in Hide & Seek</li> </ul>
  </details>
  <details>
  <summary> v4.0.0 </summary>
  <ul> <li>Compatibility with the new Among Us version v2022.12.14</li> </ul>
  <ul> <li>New Role: Imitator (Replacing Time Lord)</li> </ul>
  <ul> <li>New Role: Bomber (Poisoner rework)</li> </ul>
  <ul> <li>New Game Mode: Cultist</li> </ul>
  <ul> <li>New Game Mode Roles: Necromancer & Whisperer as well as Crewmate/Impostor variants of already existing roles</li> </ul>
  <ul> <li>New Setting: Enable Hidden Roles</li> </ul>
  <ul> <li>New Settings for hidden roles</li> </ul>
  <ul> <li>New Setting: Undertaker Drag Speed</li> </ul>
  <ul> <li>Bug Fix: Executioner/Guardian Angel turned Amnesiac/Jester/Survivor no longer have red text after changing role</li> </ul>
  <ul> <li>Amnesiac remembering a role no longer makes their task list swap with the player they remembered</li> </ul>
  <ul> <li>Bug Fix: Amnesiac no longer sees themself with the remembered players' modifier</li> </ul>
  <ul> <li>Bug Fix: Amnesiac no longer loses tasks if the person they remembered from disconnects or vice versa</li> </ul>
  <ul> <li>Bug Fix: Underdog kill timer is now in sync with normal kill cooldowns</li> </ul>
  <ul> <li>Bug Fix: Underdog now has the correct kill cooldown on game start</li> </ul>
  <ul> <li>Bug Fix: Underdog now can have a kill cooldown below 10secs</li> </ul>
  <ul> <li>Bug Fix: Miner's mines are no longer invisible in certain places</li> </ul>
  <ul> <li>Bug Fix: Undertaker no longer can make a body become invisible in certain places</li> </ul>
  <ul> <li>Bug Fix: Neutral Killers now get correct cooldowns when attacking a vesting Survivor or a Guardian Angel shield</li> </ul>
  <ul> <li>Adjusted the Trapper's trap & Grenadier's flash radius so they scale correctly</li> </ul>
  </details>
  <details>
  <summary> v3.4.0 </summary>
  <ul> <li>New Role: Escapist</li> </ul>
  <ul> <li>New Modifier: Radar</li> </ul>
  <ul> <li>New Modifier: Disperser</li> </ul>
  <ul> <li>New Modifier: Multitasker</li> </ul>
  <ul> <li>New Modifier: Double Shot</li> </ul>
  <ul> <li>New Settings: Arsonist/Jester has Impostor Vision</li> </ul>
  <ul> <li>New Setting: Arsonist Ignite Cooldown removed when they're the final killer</li> </ul>
  <ul> <li>Reporting bodies now spreads the Plaguebearer's infection</li> </ul>
  <ul> <li>Changed Underdog from a role to a modifier</li> </ul>
  <ul> <li>Changed Blind to a Crewmate Modifier</li> </ul>
  </details>
  <details>
  <summary> v3.3.2 </summary>
  <ul> <li>New Setting: Snitch doesn't see Traitor</li> </ul>
  <ul> <li>New Settings: Neutral Killing Roles can assassinate</li> </ul>
  <ul> <li>Bug Fix: People no longer show as Phantom/Haunter when they're not</li> </ul>
  </details>
  <details>
  <summary> v3.3.1 </summary>
  <ul> <li>Bug Fix: The game no longer occasionally freezes after a meeting</li> </ul>
  </details>
  <details>
  <summary> v3.3.0 </summary>
  <ul> <li>New Game Mode: All Any</li> </ul>
  <ul> <li>New Game Mode: Killers Only</li> </ul>
  <ul> <li>New Settings for Random Maps</li> </ul>
  <ul> <li>New Settings for Automatically adjusting settings depending on the map</li> </ul>
  <ul> <li>New Settings for Better Polus (and some adjustments were added as well)</li> </ul>
  <ul> <li>Split Settings Menu into 5 different menus (however settings are still loaded from the main one)</li> </ul>
  <ul> <li>Added 2 more Settings slots (bringing the total to 5)</li> </ul>
  <ul> <li>Bug Fix: Sheriff can no longer get the report button through walls</li> </ul>
  <ul> <li>Bug Fix: Starting Impostor Kill Cooldown is now always set to the right amount</li> </ul>
  <ul> <li>Bug Fix: Amnesiac remembering Traitor no longer makes another Traitor spawn</li> </ul>
  <ul> <li>Bug Fix: Underdog now gets the correct cooldown when there is more then 1 Impostor</li> </ul>
  <ul> <li>Bug Fix: An Impostor killing a Diseased player will now get the correct cooldown</li> </ul>
  <ul> <li>Bug Fix: The only person who will know they have a GA is the GA target (if target knows they have a GA)</li> </ul>
  <ul> <li>Bug Fix: Revived players from Poisoner kills no longer instantly die at the start of the next meeting</li> </ul>
  </details>
  <details>
  <summary> v3.2.0 </summary>
  <ul> <li>Compatability with the new Among Us version thanks to MyDragonBreath</li> </ul>
  <ul> <li>New Role: Plaguebearer/Pestilence</li> </ul>
  <ul> <li>New Role: Werewolf</li> </ul>
  <ul> <li>New Role: Trapper</li> </ul>
  <ul> <li>New Role: Detective</li> </ul>
  <ul> <li>New Modifier: Blind (replacing Drunk)</li> </ul>
  <ul> <li>Arsonist Rework: Douse and Ignite are on the same cooldown, however to ignite they must be standing next to one of their douses</li> </ul>
  <ul> <li>New Settings: Vigilante/Assassin can guess lovers</li> </ul>
  <ul> <li>New Setting: Traitor does not swap colours for Seer</li> </ul>
  <ul> <li>New Settings: Sheriff can shoot Werewolf/Plaguebearer</li> </ul>
  <ul> <li>New Settings: Min and Max Neutral Killing/Non-Killing Roles</li> </ul>
  <ul> <li>Setting Change: Traitor does not spawn if Glitch is alive to Traitor does not spawn if Neutral Killing is alive</li> </ul>
  <ul> <li>Survivor can now win with neutral killing roles and can get a Survivor only win</li> </ul>
  <ul> <li>Tasks can now be set above the maximum default values</li> </ul>
  <ul> <li>Transporter can now die to a Veteran on alert if they transport the Veteran</li> </ul>
  <ul> <li>Bug Fix: Impostors on high ping can no longer kill multiple players</li> </ul>
  <ul> <li>Bug Fix: Poisoned players now die before a meeting and not during a meeting</li> </ul>
  <ul> <li>Bug Fix: Glitch and Poisoner can no longer kill/poison in vents</li> </ul>
  <ul> <li>Bug Fix: Underdog now gets the correct cooldown when killing a diseased player</li> </ul>
  <ul> <li>Bug Fix: Phantom/Haunter now appear in the correct places</li> </ul>
  <ul> <li>Bug Fix: The Blackmailer now sees the correct colour name of their teammates depending on if they are blackmailed or not</li> </ul>
  <ul> <li>Bug Fix: Lag is no longer caused when attempting to repick the Traitor</li> </ul>
  </details>
  <details>
  <summary> v3.1.0 </summary>
  <ul> <li>Submerged Compatibility mostly thanks to MyDragonBreath</li> </ul>
  <ul> <li>New Setting: Assassins can guess Crewmate Modifiers</li> </ul>
  <ul> <li>New Setting: Assassins and Vigilante can guess after voting</li> </ul>
  <ul> <li>New Settings: Guardian Angel knows their target's role and Guardian Angel's target knows they have a Guardian Angel</li> </ul>
  <ul> <li>New Settings: Bait minimum and maximum delay</li> </ul>
  <ul> <li>New Setting: Diseased Kill Multiplier</li> </ul>
  <ul> <li>New Setting: Flash Speed</li> </ul>
  <ul> <li>New Setting: Giant Speed</li> </ul>
  <ul> <li>New Setting: Disable meeting skip button</li> </ul>
  <ul> <li>Bug Fix: Kill buttons should have the correct text and sprite now</li> </ul>
  <ul> <li>Bug Fix: Glitch kills no longer bypass Survivor Vests and GA Protects</li> </ul>
  <ul> <li>Lighter and Darker indicators for Medic</li> </ul>
  </details>
  <details>
  <summary> v3.0.1 </summary>
  <ul> <li>Bug Fix: All the flashes on screen now work again</li> </ul>
  <ul> <li>Bug Fix: Amnesiac turned Sheriff/Glitch/Impostor now has a kill button again</li> </ul>
  <ul> <li>Bug Fix: The kill button now has the word 'Kill' on it again</li> </ul>
  <ul> <li>Bug Fix: The Blackmailer's blackmail button will now not always show active even when not near someone</li> </ul>
  <ul> <li>Blackmailer now only has an initial cooldown, meaning the cooldown doesn't reset after a use now</li> </ul>
  </details>
  <details>
  <summary> v3.0.0 </summary>
  <ul> <li>New Role: Medium</li> </ul>
  <ul> <li>New Role: Survivor</li> </ul>
  <ul> <li>New Role: Guardian Angel</li> </ul>
  <ul> <li>New Role: Blackmailer</li> </ul>
  <ul> <li>New Role: Mystic</li> </ul>
  <ul> <li>Camouflager removed</li> </ul>
  <ul> <li>New Settings for Vigilante to kill each type of Neutral role</li> </ul>
  <ul> <li>New Settings for Assassins to kill each type of Neutral role</li> </ul>
  <ul> <li>Bug Fix: Executioner will always get a target unless there is no feasible target</li> </ul>
  <ul> <li>Bug Fix: Executioner will always win when their target is voted out</li> </ul>
  <ul> <li>The future Phantom, Haunter and Traitor will change depending on the current circumstances</li> </ul>
  <ul> <li>Bug Fix: Abilities can no longer be used while loading into a game</li> </ul>
  <ul> <li>Added an option to cycle backwards for Assassins and Vigilante</li> </ul>
  </details>
  <details>
  <summary> v2.6.5 </summary>
  <ul> <li>Fixed Amnesiac remembering Poisoner interaction</li> </ul>
  <ul> <li>Fixed Button Barry not working during sabotages</li> </ul>
  <ul> <li>Fixed Poisoner interactions against Medic shields and Veteran alerts</li> </ul>
  <ul> <li>Transporting now works a little differently</li> </ul>
  <ul> <li>If a player is transported when they are in a position out of bounds while on something like a ladder, it rejects the transport</li> </ul>
  <ul> <li>Glitch and Transporter can now be lovers</li> </ul>
  </details>
  <details>
  <summary> v2.6.4 </summary>
  <ul> <li>Fixed Transporter bugging out after transporting a dead body</li> </ul>
  <ul> <li>Reduced Tracker arrow lag</li> </ul>
  <ul> <li>Fixed bug with Swapper where you wouldn't appear as dead after being assassinated with your swap targets already selected</li> </ul>
  <ul> <li>Fixed Medic shield not protecting the target from impostors if the Shield Breaks option is off</li> </ul>
  <ul> <li>Fixed Medic reports saying the wrong color if the body's killer was morphed</li> </ul>
  <ul> <li>Fixed Investigator showing a morphed player's footprints as the color of the player they were morphed into</li> </ul>
  <ul> <li>Ghosts no longer briefly appear after a player dies</li> </ul>
  </details>
  <details>
  <summary> v2.6.3 </summary>
  <ul> <li>Fixed the bug where games don't end (Sorry about that)</li> </ul>
  <ul> <li>Fixed Bait not causing a self-report sometimes</li> </ul>
  <ul> <li>Fixed Amnesiac turned Impostor not being able to kill</li> </ul>
  <ul> <li>Fixed Traitor not being able to kill</li> </ul>
  <ul> <li>Fixed Impostors not being able to kill a player revived by an Altruist</li> </ul>
  <ul> <li>Fixed Flash and Giant not appearing to move at the correct speed for other players</li> </ul>
  <ul> <li>Changed Giant and Flash colors</li> </ul>
  <ul> <li>Split Classic Nameplates setting into Disable Level Icon and Disable Background Cosmetics</li> </ul>
  </details>
  <details>
  <summary> v2.6.2 </summary>
  <ul> <li>Fixed End Game Tracker Bug</li> </ul>
  <ul> <li>Fixed Snitch Arrows</li> </ul>
  <ul> <li>Added Olive Colour</li> </ul>
  <ul> <li>Dead bodies are now removed after meetings</li> </ul>
  <ul> <li>Added an option for Amnesiac Arrows</li> </ul>
  <ul> <li>Fixed the issue where if a player is transported as they jump in a vent they are freezed in place</li> </ul>
  </details>
  <details>
  <summary> v2.6.1 </summary>
  <ul> <li>Fixed Poisoner killing Bait after another report resulting in a duplicated meeting</li> </ul>
  <ul> <li>Fixed the issue where the Snitch spawning as Crewmate would see their name gold</li> </ul>
  <ul> <li>Fixed Amnesiac remembering Transporter becoming an Impostor</li> </ul>
  <ul> <li>Fixed Tracker Arrows</li> </ul>
  </details>
  <details>
  <summary> v2.6.0 </summary>
  <ul> <li>Fixed killing the Bait instantly banning everyone</li> </ul>
  <ul> <li>Fixed Tracker lag</li> </ul>
  <ul> <li>Seer adjustments</li> </ul>
  <ul> <li>Settings for task tracking</li> </ul>
  <ul> <li>Added a flash radius setting for Grenadier</li> </ul>
  <ul> <li>New Role: Traitor</li> </ul>
  <ul> <li>New Role: Transporter</li> </ul>
  <ul> <li>New Modifier: Sleuth</li> </ul>
  <ul> <li>Fixed Snitch/Haunter meetings when someone disconnects</li> </ul>
  <ul> <li>Fixed Amnesiac/Snitch and Amnesiac/Mayor interactions</li> </ul>
  <ul> <li>Jester can vent Setting</li> </ul>
  <ul> <li>Made Modifiers disable upon death</li> </ul>
  <ul> <li>Made anything that affects the colour of names disable upon death</li> </ul>
  </details>
  <details>
  <summary> v2.5.1 </summary>
  <ul> <li>Fixed Amnesiac/Impostor Interaction</li> </ul>
  </details>
  <details>
  <summary> v2.5.0 </summary>
  <ul> <li>Changed Lovers to a Modifier</li> </ul>
  <ul> <li>Added Loving Impostor Percentage Setting</li> </ul>
  <ul> <li>Added Neutral Lover Setting</li> </ul>
  <ul> <li>Changed Assassin from a Role to a Default Ability</li> </ul>
  <ul> <li>New Role: Amnesiac (replacing Shifter)</li> </ul>
  <ul> <li>New Role: Veteran</li> </ul>
  <ul> <li>New Role: Poisoner</li> </ul>
  <ul> <li>New Role: Tracker</li> </ul>
  <ul> <li>New Modifier: Bait</li> </ul>
  <ul> <li>Renamed Retributionist to Vigilante</li> </ul>
  <ul> <li>End Game Summary Added</li> </ul>
  <ul> <li>In Game Task Tracking Added</li> </ul>
  </details>
  <details>
  <summary> v2.4.2 </summary>
  <ul> <li>New Hats</li> </ul>
  <ul> <li>Bug Fix for Mayor Abstain Button</li> </ul>
  <ul> <li>Readded the Missing Modstamp</li> </ul>
  </details>
  <details>
  <summary> v2.4.1 </summary>
  <ul> <li>Support for the new version of Among Us on v2021.12.15</li> </ul>
  </details>
  <details>
  <summary> v2.4.0 </summary>
  <ul> <li>Support for the new version of Among Us on v2021.11.9.5</li> </ul>
  </details>
  <details>
  <summary> v2.3.4 </summary>
  <ul> <li>Reverted the change made to Mayor as it had an unintended concequence for Assassin and Retributionist</li> </ul>
  </details>
  <details>
  <summary> v2.3.3 </summary>
  <ul> <li>Added the remaining hats with credits from ToU v2.2.1-t</li> </ul>
  <ul> <li>Added some new hats from Pigoletto</li> </ul>
  <ul> <li>Removed Acron’s hats as he requested their removal</li> </ul>
  <ul> <li>Bug Fix: Lovers no longer win if the other disconnects</li> </ul>
  <ul> <li>Bug Fix: Mayor votes no longer double on a disconnect</li> </ul>
  <ul> <li>Bug Fix: When Shifter shifts with Arsonist, the douse also shifts now</li> </ul>
  <ul> <li>Bug Fix: Shifter can now ignite after shifting with the Arsonist</li> </ul>
  <ul> <li>Bug Fix: Impostors no longer see their teammate’s name go pink at the end of the meeting if their teammate is a Loving Impostor</li> </ul>
  <ul> <li>Bug Fix: Investigator no longer lags the player into oblivion</li> </ul>
  <ul> <li>Bug Fix: The game no longer infinitely tries to distribute crewmate modifiers when there are more modifiers than crewmates</li> </ul>
  <ul> <li>Bug Fix: Shield now breaks when Medic disconnects</li> </ul>
  </details>
  <details>
  <summary> v2.3.2 </summary>
  <ul> <li>Bug Fix: Sheriff no longer instantly ends the game and bans the host for hacking</li> </ul>
  <ul> <li>Bug Fix: Retributionist/Mayor interaction</li> </ul>
  <ul> <li>Bug Fix: Executioner always gets a target now</li> </ul>
  <ul> <li>Executioner can not have Lovers, Swapper, Mayor or Retributionist as their target</li> </ul>
  <ul> <li>Made it so dead Impostors don’t see Haunter arrows</li> </ul>
  <ul> <li>Made it so if Haunter reveals Neutral roles, all Neutral roles are alerted when Haunter is nearly finished tasks</li> </ul>
  <ul> <li>Removed alert for Phantom</li> </ul>
  <ul> <li>All hats with credits from v2.2.1-t have been added</li> </ul>
  <ul> <li>Removed the settings about when Phantom/Haunter can be clicked and replaced them with ‘tasks remaining when they can be clicked’</li> </ul>
  <ul> <li>Removed the settings for Phantom/Haunter to have less tasks</li> </ul>
  <ul> <li>Changed kill cooldown bonus for Underdog from 2.5-10secs to 2.5-30secs</li> </ul>
  </details>
  <details>
  <summary> v2.3.1 </summary>
  <ul> <li>Removed Modded Handshake as that was causing the host to crash</li> </ul>
  <ul> <li>Minor Bug Fixes</li> </ul>
  </details>
  <details>
  <summary> v2.3.0 </summary>
  <ul> <li>New Role: Retributionist (Assassin Crewmate)</li> </ul>
  <ul> <li>New Role: Haunter (basically the Phantom but a Crewmate, once tasks are finished Impostors are revealed)</li> </ul>
  <ul> <li>New Role: Grenadier (blinds Crewmates with flashbangs)</li> </ul>
  <ul> <li>Added the remaining missing hats from v2.0.4 and prior</li> </ul>
  <ul> <li>Glitch cooldowns adjusted to be the same as other roles</li> </ul>
  <ul> <li>Made Swapper able to get Button Barry Modifier</li> </ul>
  <ul> <li>Button Barry vision no longer reduced after Button Barry ability was used</li> </ul>
  <ul> <li>Standardised starting cooldowns to not be decreased (for round start only) for all roles</li> </ul>
  <ul> <li>Added alert for when Phantom is nearly finished</li> </ul>
  <ul> <li>Glitch does not get notification for Snitch unless Snitch sees neutral roles</li> </ul>
  <ul> <li>Made it so Impostors know when Snitch is done all tasks</li> </ul>
  <ul> <li>Reworked how Phantom is set because of Haunter addition</li> </ul>
  <ul> <li>Gray colour changed to ‘Darker’ for Medic reports</li> </ul>
  <ul> <li>Made the Seer unable to see through the disguises of Morphling and Glitch</li> </ul>
  <ul> <li>Split shifter into two settings, who can Shifter shift on and what shifted becomes</li> </ul>
  <ul> <li>Setting for Sheriff can kill Executioner</li> </ul>
  <ul> <li>Setting for Morphling, Swooper, Undertaker and Glitch to vent</li> </ul>
  <ul> <li>Setting for Undertaker to vent while dragging a body</li> </ul>
  <ul> <li>Setting for Mayor, Swapper, Jester, Executioner and Arsonist to not be able to button</li> </ul>
  <ul> <li>Setting for Executioner becomes Shifter on target death</li> </ul>
  <ul> <li>Setting for Phantom to do less tasks</li> </ul>
  <ul> <li>Setting for Assassin to assassinate Snitch via ‘Crewmate’ guess</li> </ul>
  <ul> <li>Underdog changes: Setting to choose kill cooldown bonus</li> </ul>
  <ul> <li>Setting for Underdog to not have increased kill cooldown when 2+ imps</li> </ul>
  <ul> <li>Settings for the Phantom to not be clickable before and after alert</li> </ul>
  <ul> <li>Setting for Shifter to win with Crewmates</li> </ul>
  <ul> <li>Setting for starting cooldowns on game start for all roles (a general setting)</li> </ul>
  <ul> <li>Setting for when Snitch is revealed</li> </ul>
  <ul> <li>Settings for clicking Phantom, one for before alert and the other for after alert</li> </ul>
  <ul> <li>Setting for Snitch to not see Impostor names mid-meeting</li> </ul>
  <ul> <li>Time Lord rewind time decreased from 3-15secs to 2-5secs</li> </ul>
  <ul> <li>Time Lord cooldown increased from 10-40secs to 10-60secs</li> </ul>
  <ul> <li>The maximum number of kills an Assassin can do during a meeting increased from 1-5 to 1-15</li> </ul>
  <ul> <li>Bug Fix: Host no longer sees Undertaker dragging a body after they dropped it</li> </ul>
  <ul> <li>Bug Fix: Host now has correct cooldowns on game start</li> </ul>
  <ul> <li>Bug Fix: Investigator footprint interval fixed (lag not entirely fixed)</li> </ul>
  <ul> <li>Bug Fix: Fixed the issue where Torch/Diseased were not given to anyone</li> </ul>
  <ul> <li>Bug Fix: Made it so the Phantom only has to upload data and not download it</li> </ul>
  <ul> <li>Bug Fix: Phantom no longer spawns in the admin vent</li> </ul>
  </details>
  <details>
  <summary> v2.2.1 </summary>
  <ul> <li>Fix for the credits removed in v2.0.3 </li> </ul>
  </details>
  <details>
  <summary> v2.2.0 </summary>
  <ul> <li> Compatibility for v2021.6.30 </li> </ul>
  <ul> <li> Role percentages now change by 10%, or 5% if you hold shift </li> </ul>
  <ul> <li> New Drag/Drop Buttons for the Undertaker </li> </ul>
  <ul> <li> New Button Image for the Button Barry </li> </ul>
  <ul> <li> Phantom can't switch between vents </li> </ul>
  <ul> <li> Increased Max Cooldown for the Shifter to 60s </li> </ul>
  <ul> <li> Swapper can no longer get the Button Barry Modifier </li> </ul>
  <ul> <li> Glitch can no longer get the Button Barry Modifier </li> </ul>
  <ul> <li> Mayor votes are refunded if the player disconnects </li> </ul>
  <ul> <li> Mayor votes are refunded if the player is killed by the assassin </li> </ul>
  <ul> <li> Handshake refactor </li> </ul>
  <ul> <li> Fix for the Crashing Issues </li> </ul>
  <ul> <li> Fix for the Interaction Shifter/Giant </li> </ul>
  <ul> <li> Fix for the Interaction Shifter/Engineer </li> </ul>    
  <ul> <li> Fix for the Interaction Glitch/Jester </li> </ul>
  <ul> <li> Fix for the Interaction Morphling/Giant </li> </ul>
  <ul> <li> Fix for the Altruist Body Issues </li> </ul>
  <ul> <li> Fix for the Assassin DC Issues </li> </ul>
  <ul> <li> Fix for the Executioner Spawn Issues </li> </ul>
  <ul> <li> Fix for the Phantom Vent Spawn Issues </li> </ul>    
  <ul> <li> Fix for the Phantom Walking Through Walls Issues </li> </ul>
  <ul> <li> Fix for the Phantom Doors Issues </li> </ul>
  <ul> <li> Fix for the Phantom Tasks Issues </li> </ul>
  <ul> <li> Fix for the Swooper Invisible Issues </li> </ul>    
  <ul> <li> Fix for the Time Lord Flashing Ability Issues </li> </ul>
  <ul> <li> Fix for the Time Lord Rewind Vent Issues </li> </ul>
  <ul> <li> Fix for the Undertaker Dragging Issues </li> </ul>    
  <ul> <li> Fix for the Underdog Cooldown Issues </li> </ul>
  <ul> <li> Fix for the Giant Modifier Size Issues </li> </ul>
  <ul> <li> Fix for the State Of Dead/DC Bodies In Meeting Issues </li> </ul>   
  <ul> <li> Fix for the Voting Visual Issues </li> </ul>      
  <ul> <li> Minor enhancements and bug fixes </li> </ul>
 </details>
  <details>
  <summary> v2.1.4 </summary>
  <ul> <li> New Role (Phantom, Undertaker, Underdog) </li> </ul>
  <ul> <li> Custom Color </li> </ul>
  <ul> <li> Hats </li> </ul>
  <ul> <li> Fix for launching issues </li> </ul>
  <ul> <li> Fix for the Voting issues </li> </ul>
  <ul> <li> Fix for the disconnect issue</li> </ul>
  <ul> <li> Fix for the username placement </li> </ul>
  <ul> <li> Fix for the Medic  </li> </ul>
  <ul> <li> Fix for the Spy </li> </ul>
  <ul> <li> Fix for the Mayor </li> </ul>
  <ul> <li> Fix for the Arsonist </li> </ul>
  <ul> <li> Fix for the Assassin </li> </ul>
  <ul> <li> Fix for the Phantom </li> </ul>
  <ul> <li> Modded Handshake </li> </ul>
  <ul> <li> Child is removed </li> </ul>
  <ul> <li> Minor enhancements and bug fixes </li> </ul>
 </details>
 <details>
  <summary> v2.1.3 </summary>
  <ul> <li> Fix the launch issue </li> </ul>
  <ul> <li> Fix for the swooper role </li> </ul>
  <ul> <li> Fix for the janitor role </li> </ul>
  <ul> <li> Minor enhancements and bug fixes </li> </ul>
 </details>
 <details>
  <summary> v2.1.2 </summary>
  <ul> <li> Crucial bug fixes </li> </ul>
 </details>
 <details>
  <summary> v2.1.1 </summary>
  <ul> <li> 2021.6.15 support, Epic Games compatibility and Assassin Role </li> </ul>
 </details>
  <details>
  <summary> v2.0.4 </summary>
  <ul> <li> Crucial bug fixes </li> </ul>
 </details>
 <details>
  <summary> v2.0.3 </summary>
  <ul> <li> 2021.5.10s support </li> </ul>
 </details>
 <details>
  <summary> v2.0.2 </summary>
  <ul> <li> 2021.4.14s support and temporary auth fixes </li> </ul>
 </details>
 <details>
  <summary> v2.0.1 </summary>
  <ul> <li> 2021.4.12s support </li> </ul>
 </details>
 <details>
  <summary> v2.0.0 </summary>
  <ul>
   <li> Airship support! </li>
   <li> New role - Altruist </li>
   <li> New modifiers - Giant & Button Barry </li>
   <li> Airship comms fix built-in </li>
   <li> Bug fixes with Lovers, Time Lord etc. </li>
   <li> New hats based on streamers! </li>
   <li> Investigator cannot spawn on airship due to too much lag with handling footprints </li>
  </ul>
 </details>
  
 <details>
  <summary> v1.2.0 </summary>
  <ul>
    <li> New roles (see above)</a>
    <li> New modifiers (see above)</li>
    <li> Exporting and Importing game settings which sync between versions 1.2.0 and future versions</li>
    <li> Disconnect fix </li>
    <li> Mayor additions - Abstain button, Option for Mayor's extra votes to be anonymous </li>
    <li> Option for dead to see the roles of everyone </li>
    <li> Custom colours now work! </li>
  </ul>
 </details>
 <details>
  <summary> v1.1.0 </summary>
  <ul>
    <li> New roles (see above)</a>
    <li> New modifiers (see above)</li>
    <li> The Engineer has been changed to the <a href="https://github.com/NotHunter101/ExtraRolesAmongUs">ExtraRoles</a> version </li>
    <li> Backend overhaul! This will make it easier to add new roles </li>
    <li> New Button Art! </li>
    <li> Maps and Impostor Count can be changed from the Lobby! </li>
    <li> Shadows for the Custom Colours </li>
    <li> Fixes </li>
    <ul>
      <li> The Jester and The Shifter unable to fix Sabotages </li>
      <li> The Time Lord's Rewind not auto-force closing tasks </li>
      <li> The Q button not working for Sheriff </li>
      <li> The Shifter's Shift looking too much like a Kill </li>
      <li> Changing colours would render you weirdly green in normal Among Us </li>
    </ul>
  </ul>
  </details>


  <details>
  <summary> v1.0.3 </summary>
  <p> Fixes: </p>
  <ul>
    <li> Engineer being able to Fix every sabotage </li>
    <li> The Investigator being able to revive people voted out (and instead made it an option) </li>
    <li> Footprints not appearing if a person walks over old footprints </li>
    <li> Graphical glitch where Jester and Lovers simultaneously win </li>
    <li> Players spawning back into positions from the last game when time is rewound right at the beginning of a new game </li>
    <li> Graphical Bug of Time Lord's name not being blue in Meetings </li>
    <li> Fixed Medbay Scan not working for custom colours </li>
  </ul>
  </details>

  <details>
  <summary> v1.0.2 </summary>
  <p> Fixes: </p>
  <ul>
    <li>  The Swapper being unable to vote </li>
    Swapper unable to vote
    <li> Mayor Vote Bank ending up negative </li>
    <li> Anonymous Voting not working when Mayor is in a game </li>
    <li> Chats not working in the lobby </li>
    <li> Sheriff desync (I think) </li>
    <li> Buttons being able to be used during meetings </li>
  </ul>
  <hr>
  </details>

  <details>
  <summary> v1.0.1 </summary>
  <p> Fixes errors of not being able to launch. </p>
  </details>
</details>


-----------------------
# Installation
## Requirements 
- Among Us
- Steam or Epic Games

## Installation Guide (Steam)
**1. [Download](#releases) the Town of Us version corresponding to the installed Among Us version.**\
\
**2. Go to your Steam library.**\
\
**3. Right-click Among Us > click `Manage` > click `Browse local files`.**\
\
**4. In the File Explorer, delete the entire `Among Us` folder.**\
\
**5. Go back to your Steam library.**\
\
**6. Right-Click Among Us > click `Properties...` > click `LOCAL FILES`.**\
\
**7. Click on `VERIFY INTEGRITY OF GAME FILES...`.**\
\
**8. Wait for Steam to download a clean version of Among Us.**\
\
**9. Duplicate the new Among Us Folder.**\
\
**10. Rename it to `Among Us - ToU`.**\
\
**11. Double-click on the zip file you downloaded.**\
\
**12. Drag all the files from the zip file in the new ToU folder.**\
\
**13. Finally, launch `Among Us.exe` from that folder.**\
\
A first launch may take up to 5 minutes, so be patient if it doesn't launch immediately.<br/>
<br/>

## Installation Guide (Epic Games)
**1. [Download](#releases) the Town of Us version corresponding to the installed Among Us version.**\
\
**2. Go to your Epic Games library.**\
\
**3. Find Among Us and click on the 3 dots `...` > click `Uninstall`.**\
\
**4. Confirm you want to Uninstall Among Us.**\
\
**5. In the Epic library, click on Among Us to install.**\
\
**6. Copy the Folder Path.**\
\
**7. Uncheck Auto-Update.**\
\
**8. Click on Install.**\
\
**9. Click Yes on the Windows popup.**\
\
**10. Paste the folder path in Windows search bar.**\
\
**11. Click on Enter.**\
\
**12. Copy or move the contents of the Town Of Us zip file into the AmongUs folder.**\
\
**13. Finally, launch Among Us from Epic Games library.**\
\
A first launch may take up to 5 minutes, so be patient if it doesn't launch immediately.<br/>
<br/>

![Install](https://i.imgur.com/pvBAyZN.png)
<br/>
## Issues
If you have issues installing Town of Us, you can join our [Discord](https://discord.gg/ugyc4EVUYZ) to receive help.

-----------------------
# Roles
# Crewmate Roles
## Aurial
### **Team: Crewmates**
The Aurial is a Crewmate that can see the Auras of other players.\
At the beginning of the game all players are white, once radiated enough the Aurial can see their alignment.\
Green is Crewmate, Grey is Neutral and Red is Impostor.\
However, as a consequence the Aurial cannot see who is who.
### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Aurial | The percentage probability of the Aurial appearing | Percentage | 0% |
| Radiate Range | The range of the Aurial's radiation | Multiplier | 1x |
| Radiate Cooldown | The cooldown of the Aurial's Radiate button | Time | 25s |
| Radiate See Delay | The duration of time after meetings where the Aurial can't see players | Time | 10s |
| Radiate Uses To See | The number of times required to radiate to see a player's aura | Number | 3 |
| Radiate Succeed Chance | The percentage probability of the Aurial successfully radiating someone | Percentage | 100% |

-----------------------
## Detective
### **Team: Crewmates**
The Detective is a Crewmate that can inspect bodies and then examine players.\
The Detective must first find a body and inspect it.\
During the same or following rounds the Detective can then examine players to see if they were the killer.\
If the examined player is the killer they will receive a red flash, else the flash will be green.\
If the killer of the inspected player dies, the following round the examine button will disable indicating to the Detective the killer is dead.
### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Detective | The percentage probability of the Detective appearing | Percentage | 0% |
| Examine Cooldown | The cooldown of the Detective's Examine button | Time | 25s |
| Show Detective Reports | Whether the Detective should get information when reporting a body | Toggle | True |
| Time Where Detective Reports Will Have Role | If a body has been dead for shorter than this amount, the Detective's report will contain the killer's role | Time | 15s |
| Time Where Detective Reports Will Have Faction | If a body has been dead for shorter than this amount, the Detective's report will contain the killer's faction | Time | 30s |

-----------------------
## Haunter
### **Team: Crewmates**
The Haunter is a dead Crewmate that can reveal Impostors if they finish all their tasks.\
Upon finishing all of their tasks, Impostors are revealed to alive crewmates after a meeting is called.\
However, if the Haunter is clicked they lose their ability to reveal Impostors and are once again a normal ghost.
### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Haunter | The percentage probability of the Haunter appearing | Percentage | 0% |
| When Haunter Can Be Clicked | The amount of tasks remaining when the Haunter Can Be Clicked | Number | 5 |
| Haunter Alert | The amount of tasks remaining when the Impostors are alreted that the Haunter is nearly finished | Number | 1 |
| Haunter Reveals Neutral Roles | Whether the Haunter also Reveals Neutral Roles | Toggle | False |
| Who can Click Haunter | Whether even other Crewmates can click the Haunter | All / Non-Crew / Imps Only | All |

-----------------------
## Investigator
### **Team: Crewmates**
The Investigator is a Crewmate that can see the footprints of players.\
Every footprint disappears after a set amount of time.

### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Investigator | The percentage probability of the Investigator appearing | Percentage | 0% |
| Footprint Size | The size of the footprint on a scale of 1 to 10 | Number | 4 |
| Footprint Interval | The time interval between two footprints | Time | 0.1s |
| Footprint Duration | The amount of time that the footprint stays on the ground for | Time | 10s |
| Anonymous Footprint | When enabled, all footprints are grey instead of the player's colors | Toggle | False |
| Footprint Vent Visible | Whether footprints near vents are shown | Toggle | False |

-----------------------
## Mystic
### **Team: Crewmates**
The Mystic is a Crewmate that gets an alert revealing when someone has died.\
On top of this, the Mystic briefly gets an arrow pointing in the direction of the body.
### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Mystic | The percentage probability of the Mystic appearing | Percentage | 0% |
| Arrow Duration | The duration of the arrows pointing to the bodies | Time | 0.1s |

-----------------------
## Oracle
### **Team: Crewmates**
The Oracle is a Crewmate that can get another player to confess information to them.\
The Oracle has 3 abilities, the first is that when they die, the person confessin to them will reveal their alignment.\
The second, is that every meeting the Oracle receives a confession about who might be evil.\
The final ability is giving a blessing to the person confessing to them, with this the confessing player gains vote immunity!
### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Oracle | The percentage probability of the Oracle appearing | Percentage | 0% |
| Confess Cooldown | The Cooldown of the Oracle's Confess button | Time | 25s |
| Reveal Accuracy | The percentage probability of the Oracle's confessed player telling the truth | Percentage | 80% |
| Neutral Benign show up as Evil | Neutral Benign roles show up as Evil | Toggle | False |
| Neutral Evil show up as Evil | Neutral Evil roles show up as Evil | Toggle | False |
| Neutral Killing show up as Evil | Neutral Killing roles show up as Evil | Toggle | True |

-----------------------
## Seer
### **Team: Crewmates**
The Seer is a Crewmate that can reveal the alliance of other players.\
Based on settings, the Seer can find out whether a player is a Good or an Evil role.\
A player's name will change color depending on faction and role.
### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Seer | The percentage probability of the Seer appearing | Percentage | 0% |
| Seer Cooldown | The Cooldown of the Seer's Reveal button | Time | 25s |
| Crewmate Killing Roles Are Red | Crewmate Killing roles show up as Red | Toggle | False |
| Neutral Benign Roles Are Red | Neutral Benign roles show up as Red | Toggle | False |
| Neutral Evil Roles Are Red | Neutral Evil roles show up as Red | Toggle | False |
| Neutral Killing Roles Are Red | Neutral Killing roles show up as Red | Toggle | True |
| Traitor does not swap Colours | The Traitor remains their original colour | Toggle | False |

-----------------------
## Snitch
### **Team: Crewmates**

The Snitch is a Crewmate that can get arrows pointing towards the Impostors, once all their tasks are finished.\
The names of the Impostors will also show up as red on their screen.\
However, when they only have a single task left, the Impostors get an arrow pointing towards the Snitch.
### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Snitch | The percentage probability of the Snitch appearing | Percentage | 0% |
| Snitch Sees Neutral Roles | Whether the Snitch also Reveals Neutral Roles | Toggle | False |
| Tasks Remaining When Revealed | The number of tasks remaining when the Snitch is revealed to Impostors | Number | 1 |
| Snitch Sees Impostors in Meetings | Whether the Snitch sees the Impostor's names red in Meetings | Toggle | True |
| Snitch Sees Traitor | Whether the Snitch sees the Traitor | Toggle | True |

-----------------------
## Spy
### **Team: Crewmates**

The Spy is a Crewmate that gains more information when on the Admin Table.\
On Admin Table, the Spy can see the colors of every person on the map.
### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Spy | The percentage probability of the Spy appearing | Percentage | 0% |
| Who Sees Dead Bodies On Admin | Which players see dead bodies on the admin map | Nobody / Spy / Everyone But Spy / Everyone | Nobody |

-----------------------
## Tracker
### **Team: Crewmates**

The Tracker is a Crewmate that can track other players by tracking them during a round.\
Once they track someone, an arrow is continuously pointing to them, which updates in set intervals.
### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Tracker | The percentage probability of the Tracker appearing | Percentage | 0% |
| Arrow Update Interval | The time it takes for the arrow to update to the new location of the tracked player | Time | 5s |
| Track Cooldown | The cooldown on the Tracker's track button | Time | 25s |
| Tracker Arrows Reset Each Round | Whether Tracker Arrows are removed after each meeting | Toggle | False |
| Maximum Number of Tracks Per Round | The number of new people they can track each round | Number | 3 |

-----------------------
## Trapper
### **Team: Crewmates**

The Trapper is a Crewmate that can place traps around the map.\
When players enter a trap they trigger the trap.\
In the following meeting, all players who triggered a trap will have their role displayed to the trapper.\
However, this is done so in a random order, not stating who entered the trap, nor what role a specific player is.
### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Trapper | The percentage probability of the Trapper appearing | Percentage | 0% |
| Min Amount of Time in Trap to Register | How long a player must stay in the trap for it to trigger | Time | 1s |
| Trap Cooldown | The cooldown on the Trapper's trap button | Time | 25s |
| Traps Removed Each Round | Whether the Trapper's traps are removed after each meeting | Toggle | True |
| Maximum Number of Traps Per Game | The number of traps they can place in a game | Number | 5 |
| Trap Size | The size of each trap | Factor | 0.25x |
| Minimum Number of Roles required to Trigger Trap | The number of players that must enter the trap for it to be triggered | Number | 3 |

-----------------------
## Sheriff
### **Team: Crewmates**
The Sheriff is a Crewmate that has the ability to eliminate the Impostors using their kill button.\
However, if they kill a Crewmate or a Neutral player they can't kill, they instead die themselves.

### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Sheriff | The percentage probability of the Sheriff appearing | Percentage | 0% |
| Sheriff Miskill Kills Crewmate | Whether the other player is killed if the Sheriff Misfires | Toggle | False |
| Sheriff Kills Doomsayer | Whether the Sheriff is able to kill the Doomsayer | Toggle | False |
| Sheriff Kills Executioner | Whether the Sheriff is able to kill the Executioner | Toggle | False |
| Sheriff Kills Jester | Whether the Sheriff is able to kill the Jester | Toggle | False |
| Sheriff Kills Arsonist | Whether the Sheriff is able to kill the Arsonist | Toggle | False |
| Sheriff Kills The Glitch | Whether the Sheriff is able to kill The Glitch | Toggle | False |
| Sheriff Kills Juggernaut | Whether the Sheriff is able to kill the Juggernaut | Toggle | False |
| Sheriff Kills Plaguebearer | Whether the Sheriff is able to kill the Plaguebearer | Toggle | False |
| Sheriff Kills Vampire | Whether the Sheriff is able to kill the Vampire | Toggle | False |
| Sheriff Kills Werewolf | Whether the Sheriff is able to kill the Werewolf | Toggle | False |
| Sheriff Kill Cooldown | The cooldown on the Sheriff's kill button | Time | 25s |
| Sheriff can report who they've killed | Whether the Sheriff is able to report their own kills | Toggle | True |

-----------------------
## Vampire Hunter
### **Team: Crewmates**
The Vampire Hunter is a Crewmate role which can hunt Vampires.\
Their job is to kill all Vampires.\
Once all Vampires are dead they turn into a different Crewmate role after the following meeting.

### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Vampire Hunter | The percentage probability of the Vampire Hunter appearing | Percentage | 0% |
| Stake Cooldown | The cooldown of the Vampire Hunter's Stake button | Time | 25s |
| Max Failed Stakes Per Game | The amount of times the Stake ability can be used per game incorrectly | Number | 5 |
| Can Stake Round One | If the Vampire Hunter can stake players on the first round | Toggle | False |
| Self Kill On Failure To Kill A Vamp With All Stakes | Whether the Vampire Hunter will die if they fail to stake any Vampires | Toggle | False |
| Vampire Hunter becomes on Vampire Death | Which role the Vampire Hunter becomes when all Vampires die | Crewmate / Sheriff / Veteran / Vigilante | Crewmate |

-----------------------
## Veteran
### **Team: Crewmates**

The Veteran is a Crewmate that can go on alert.\
When the Veteran is on alert, anyone, whether crew, neutral or impostor, if they interact with the Veteran, they die.
### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Veteran | The percentage probability of the Veteran appearing | Percentage | 0% |
| Can Be Killed On Alert | Whether the Veteran dies when someone tries to kill them when they're on alert | Toggle | False |
| Alert Cooldown | The cooldown on the Veteran's alert button. | Time | 5s |
| Alert Duration | The duration of the alert | Time | 25s |
| Maximum Number of Alerts | The number of times the Veteran can alert throughout the game | Number | 3 |

-----------------------
## Vigilante
### **Team: Crewmates**

The Vigilante is a Crewmate that can kill during meetings.\
During meetings, the Vigilante can choose to kill someone by guessing their role, however, if they guess incorrectly, they die instead.
### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Vigilante | The percentage probability of the Vigilante appearing | Percentage | 0% |
| Vigilante Kill | The number of kill the Vigilante can do with his ability | Number | 1 |
| Vigilante Multiple Kill  | Whether the Vigilante can kill more than once per meeting | Toggle | False |
| Vigilante Guess Neutral Benign  | Whether the Vigilante can Guess Neutral Benign roles | Toggle | False |
| Vigilante Guess Neutral Evil  | Whether the Vigilante can Guess Neutral Evil roles | Toggle | False |
| Vigilante Guess Neutral Killing  | Whether the Vigilante can Guess Neutral Killing roles | Toggle | False |
| Vigilante Guess Lovers  | Whether the Vigilante can Guess Lovers | Toggle | False |
| Vigilante Guess After Voting  | Whether the Vigilante can Guess after they have voted | Toggle | False |

-----------------------
## Altruist
### **Team: Crewmates**

The Altruist is a Crewmate that is capable of reviving dead players.\
Upon finding a dead body, the Altruist can hit their revive button, risking sacrificing themselves for the revival of another player.\
If enabled, the dead body disappears, so only the Altruist's body remains at the scene.\
After a set period of time, the player will be resurrected, if the revival isn't interrupted.
### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Altruist | The percentage probability of the Altruist appearing | Percentage | 0% |
| Altruist Revive Duration | The time it takes for the Altruist to revive a dead body | Time | 10s |
| Target's body disappears on beginning of revive | Whether the dead body of the player the Altruist is reviving disappears upon revival | Toggle | False |

-----------------------
## Medic
### **Team: Crewmates**
The Medic is a Crewmate that can give any player a shield that will make them immortal until the Medic dies.\
A Shielded player cannot be killed by anyone, unless by suicide.\
If the Medic reports a dead body, they can get a report containing clues to the Killer's identity.\
A report can contain the name of the killer or the color type (Darker/Lighter)
### Colors
- Red - Darker
- Blue - Darker
- Green - Darker
- Pink - Lighter
- Orange - Lighter
- Yellow - Lighter
- Black - Darker
- White - Lighter
- Purple - Darker
- Brown - Darker
- Cyan - Lighter
- Lime - Lighter
- Maroon - Darker
- Rose - Lighter
- Banana - Lighter
- Gray - Darker
- Tan - Darker
- Coral - Lighter
- Watermelon - Darker
- Chocolate - Darker
- Sky Blue - Lighter
- Beige - Lighter
- Magenta - Darker
- Turquoise - Lighter
- Lilac - Lighter
- Olive - Darker
- Azure - Lighter
- Plum - Darker
- Jungle - Darker
- Mint - Lighter
- Chartreuse - Lighter
- Macau - Darker
- Tawny - Darker
- Gold - Lighter
- Rainbow - Lighter

### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Medic | The percentage probability of the Medic appearing | Percentage | 0% |
| Show Shielded Player | Who should be able to see who is Shielded | Self / Medic / Self + Medic / Everyone | Self |
| Show Medic Reports | Whether the Medic should get information when reporting a body | Toggle | True |
| Time Where Medic Reports Will Have Name | If a body has been dead for shorter than this amount, the Medic's report will contain the killer's name | Time | 0s |
| Time Where Medic Reports Will Have Color Type | If a body has been dead for shorter than this amount, the Medic's report will have the type of color | Time | 15s |
| Who gets murder attempt indicator | Who will receive an indicator when someone tries to Kill them | Medic / Shielded / Everyone / Nobody | Medic |
| Shield breaks on murder attempt | Whether the Shield breaks when someone attempts to Kill them | Toggle | False |

-----------------------
## Engineer
### **Team: Crewmates**
The Engineer is a Crewmate that can fix sabotages from anywhere on the map.\
They can use vents to get across the map easily.

### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Engineer | The percentage probability of the Engineer appearing | Percentage | 0% |
| Maximum Fixes | The number of times the Engineer can fix a sabotage | Number | 5 |

-----------------------
## Imitator
### **Team: Crewmates**
The Imitator is a Crewmate that can mimic dead crewamtes.\
During meetings the Imitator can select who they are going to imitate the following round from the dead.\
They can choose to use each dead players as many times as they wish.\
It should be noted the Imitator can not imitate all crew roles.

### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Imitator | The percentage probability of the Imitator appearing | Percentage | 0% |

-----------------------
## Mayor
### **Team: Crewmates**
The Mayor is a Crewmate that can reveal themself to everyone.\
Once revealed the Mayor cannot be assassinated, gains an additional 2 votes and everyone can see that they are the Mayor.\
As a consequence of revealing, they have half vision when lights are on.

### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Mayor | The percentage probability of the Mayor appearing | Percentage | 0% |

-----------------------
## Medium
### **Team: Crewmates**
The Medium is a Crewmate that can see ghosts.\
During each round the Medium has an ability called Mediate.\
If the Medium uses this ability and no one is dead, nothing will happen.\
However, if someone is dead, the Medium and the dead player will be able to see each other and communicate from beyond the grave!

### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Medium | The percentage probability of the Medium appearing | Percentage | 0% |
| Mediate Cooldown | The cooldown of the Medium's Mediate button | Time | 10s |
| Reveal Appearance of Mediate Target | Whether the Ghosts will show as themselves, or camouflaged | Toggle | True |
| Reveal the Medium to the Mediate Target | Whether the ghosts can see that the Medium is the Medium | Toggle | True |
| Who is Revealed | Which players are revealed to the Medium | Oldest Dead / Newest Dead / All Dead | Oldest Dead |

-----------------------
## Prosecutor
### **Team: Crewmates**
The Prosecutor is a Crewmate that can once per game prosecute a player which results in them being exiled that meeting.\
The Prosecutor can also see votes non-anonymously.

### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Prosecutor | The percentage probability of the Prosecutor appearing | Percentage | 0% |
| Prosecutor Dies When They Exile A Crewmate | Whether the Prosecutor also gets exiled when they exile a Crewmate | Toggle | False |

-----------------------
## Swapper
### **Team: Crewmates**
The Swapper is a Crewmate that can swap the votes on 2 players during a meeting.\
All the votes for the first player will instead be counted towards the second player and vice versa.

### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Swapper | The percentage probability of the Swapper appearing | Percentage | 0% |
| Swapper Can Button | Whether the Swapper Can Press the Button | Toggle | True |

-----------------------
## Transporter
### **Team: Crewmates**
The Transporter is a Crewmate that can change the locations of two random players at will.\
Players who have been transported are alerted with a blue flash on their screen.

### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Transporter | The percentage probability of the Transporter appearing | Percentage | 0% |
| Transport Cooldown | The cooldown of the Transporter's transport ability | Time | 25s |
| Max Uses | The amount of times the Transport ability can be used | Number | 5 |
| Transporter can use Vitals | Whether the Transporter has the ability to use Vitals | Toggle | False |

-----------------------
# Neutral Roles
## Amnesiac
### **Team: Neutral**
The Amnesiac is a Neutral role with no win condition.\
They have zero tasks and are essentially roleless.\
However, they can remember a role by finding a dead player.\
Once they remember their role, they go on to try win with their new win condition.

### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Amnesiac | The percentage probability of the Amnesiac appearing | Percentage | 0% |
| Amnesiac Gets Arrows | Whether the Amnesiac has arrows pointing to dead bodies | Toggle | False |
| Arrow Appear Delay | The delay of the arrows appearing after the person died | Time | 5s |

-----------------------
## Guardian Angel
### **Team: Neutral**
The Guardian Angel is a Neutral role which aligns with the faction of their target.\
Their job is to protect their target at all costs.\
If their target loses, they lose.

### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Guardian Angel | The percentage probability of the Guardian Angel appearing | Percentage | 0% |
| Protect Cooldown | The cooldown of the Guardian Angel's Protect button | Time | 25s |
| Protect Duration | How long The Guardian Angel's Protect lasts | Time | 10s |
| Kill Cooldown Reset on Attack | The attackers kill cooldown after they attacked the protected target | Time | 2.5s |
| Max Uses | The amount of times the Protect ability can be used | Number | 5 |
| Show Protected Player | Who should be able to see who is Protected | Self / GA / Self + GA / Everyone | Self |
| Guardian Angel becomes on Target Dead | Which role the Guardian Angel becomes when their target dies | Crewmate / Amnesiac / Survivor / Jester | Crewmate |
| Target Knows GA Exists | Whether the GA's Target knows they have a GA | Toggle | False |
| GA Knows Targets Role | Whether the GA knows their target's role | Toggle | False |
| Odds Of Target Being Evil | The chances of the Guardian Angel's target being evil | Percentage | 20% |

-----------------------
## Survivor
### **Team: Neutral**
The Survivor is a Neutral role which can win by simply surviving.\
However, if Lovers, or a Neutral Evil role wins the game, the survivor loses.

### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Survivor | The percentage probability of the Survivor appearing | Percentage | 0% |
| Vest Cooldown | The cooldown of the Survivor's Vest button | Time | 25s |
| Vest Duration | How long The Survivor's Vest lasts | Time | 10s |
| Kill Cooldown Reset on Attack | The attackers kill cooldown after they attacked the veste Survivor | Time | 2.5s |
| Max Uses | The amount of times the Vest ability can be used | Number | 5 |

-----------------------
## Doomsayer
### **Team: Neutral**
The Doomsayer is a Neutral role with its own win condition.\
Their goal is to assassinate a certain number of players.\
Once done so they win the game.\
They have an additional observe ability that hints towards certain player's roles.
### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Doomsayer | The percentage probability of the Doomsayer appearing | Percentage | 0% |
| Observe Cooldown | The Cooldown of the Doomsayer's Observe button | Time | 25s |
| Doomsayer Guess Neutral Benign  | Whether the Doomsayer can Guess Neutral Benign roles | Toggle | False |
| Doomsayer Guess Neutral Evil  | Whether the Doomsayer can Guess Neutral Evil roles | Toggle | False |
| Doomsayer Guess Neutral Killing  | Whether the Doomsayer can Guess Neutral Killing roles | Toggle | False |
| Doomsayer Guess Impostors  | Whether the Doomsayer can Guess Impostor roles | Toggle | False |
| Doomsayer Can Guess After Voting  | Whether the Doomsayer can Guess after voting | Toggle | False |
| Number Of Doomsayer Kills To Win | The amount of kills in order for the Doomsayer to win | Number | 3 |

-----------------------
## Executioner
### **Team: Neutral**

The Executioner is a Neutral role with its own win condition.\
Their goal is to vote out a player, specified in the beginning of a game.\
If that player gets voted out, they win the game.
### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Executioner | The percentage probability of the Executioner appearing | Percentage | 0% |
| Executioner becomes on Target Dead | Which role the Executioner becomes when their target dies | Crewmate / Amnesiac / Survivor / Jester | Crewmate |
| Executioner Can Button | Whether the Executioner Can Press the Button | Toggle | True |

-----------------------
## Jester
### **Team: Neutral**
The Jester is a Neutral role with its own win condition.\
If they are voted out after a meeting, the game finishes and they win.\
However, the Jester does not win if the Crewmates, Impostors or another Neutral role wins.

### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Jester | The percentage probability of the Jester appearing | Percentage | 0% |
| Jester Can Button | Whether the Jester Can Press the Button | Toggle | True |
| Jester Can Vent | Whether the Jester Can Vent | Toggle | False |
| Jester Has Impostor Vision | Whether the Jester Has Impostor Vision | Toggle | False |

-----------------------
## Phantom
### **Team: Neutral**

The Phantom is a Neutral role with its own win condition.\
They become half-invisible when they die and has to complete all their tasks without getting caught.
### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Phantom | The percentage probability of the Phantom appearing | Percentage | 0% |
| When Phantom Can Be Clicked | The amount of tasks remaining when the Phantom Can Be Clicked | Number | 5 |

-----------------------
## Arsonist
### **Team: Neutral**

The Arsonist is a Neutral role with its own win condition.\
They have two abilities, one is to douse other players with gasoline.\
The other is to ignite all doused players.\
The Arsonist needs to be the last killer alive to win the game.
### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Arsonist | The percentage probability of the Arsonist appearing | Percentage | 0% |
| Douse Cooldown | The cooldown of the Arsonist's Douse button | Time | 25s |
| Maximum Alive Players Doused | The maximum amount of players that the Arsonist can have doused | Number | 5 |
| Arsonist Has Impostor Vision | Whether the Arsonist Has Impostor Vision | Toggle | False |
| Ignite Cooldown Removed When Arso Is Last Killer | Whether the Arsonist's Ignite Cooldown is removed when they're the final killer | Toggle | False |

-----------------------
## Juggernaut
### **Team: Neutral**

The Juggernaut is a Neutral role with its own win condition.\
The Juggernaut's special ability is that their kill cooldown reduces with each kill.\
This means in theory the Juggernaut can have a 0 second kill cooldown!\
The Juggernaut is also a hidden role, meaning it will show up randomly and can not be toggled by percentages like other roles.\
The Juggernaut needs to be the last killer alive to win the game.
### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Juggernaut Kill Cooldown | The initial cooldown of the Juggernaut's Kill button | Time | 25s |
| Reduced Kill Cooldown Per Kill | The amount of time removed from the Juggernaut's Kill Cooldown Per Kill | Time | 5s |
| Juggernaut can Vent | Whether the Juggernaut can Vent | Toggle | False |

-----------------------
## Plaguebearer
### **Team: Neutral**

The Plaguebearer is a Neutral role with its own win condition, as well as an ability to transform into another role.\
The Plaguebearer has one ability, which allows them to infect other players.\
Once infected, the infected player can go and infect other players via interacting with them.\
Once all players are infected, the Plaguebearer becomes Pestilence.\
The Pestilence is a unkillable force which can only be killed by being voted out, even their lover dying won't kill them.\
The Plaguebearer or Pestilence needs to be the last killer alive to win the game.
### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Plaguebearer | The percentage probability of the Plaguebearer appearing | Percentage | 0% |
| Infect Cooldown | The cooldown of the Plaguebearer's Infect button | Time | 25s |
| Pestilence Kill Cooldown | The cooldown of the Pestilence's Kill button | Time | 25s |
| Pestilence can Vent | Whether the Pestilence can Vent | Toggle | False |

-----------------------
## The Glitch
### **Team: Neutral**

The Glitch is a Neutral role with its own win condition.\
The Glitch's aim is to kill everyone and be the last person standing.\
The Glitch can Hack players, resulting in them being unable to report bodies and do tasks.\
Hacking prevents the hacked player from doing anything but walk around the map.\
The Glitch can Mimic someone, which results in them looking exactly like the other person.

### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| The Glitch | The percentage probability of The Glitch appearing | Percentage | 0% |
| Mimic Cooldown | The cooldown of The Glitch's Mimic button | Time | 25s |
| Mimic Duration | How long The Glitch can Mimic a player | Time | 10s |
| Hack Cooldown | The cooldown of The Glitch's Hack button | Time | 25s |
| Hack Duration | How long The Glitch can Hack a player | Time | 10s |
| Glitch Kill Cooldown | The cooldown of the Glitch's Kill button | Time | 25s |
| Glitch Hack Distance | How far away The Glitch can Hack someone from | Short / Normal / Long | Short |
| Glitch can Vent | Whether the Glitch can Vent | Toggle | False |

-----------------------
## Vampire
### **Team: Neutral**

The Vampire is a Neutral role with its own win condition.\
The Vampire can convert or kill other players by biting them.\
If the bitten player was a Crewmate they will turn into a Vampire (unless there are 2 Vampires alive)\
Else they will kill the bitten player.
### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Vampire | The percentage probability of the Vampire appearing | Percentage | 0% |
| Bite Cooldown | The cooldown of the Vampire's Bite button | Time | 25s |
| Vampire Has Impostor Vision | Whether the Vampire Has Impostor Vision | Toggle | False |
| Vampire Can Vent | Whether the Vampire Can Vent | Toggle | False |
| New Vampire Can Assassinated | Whether the new Vampire can assassinate | Toggle | False |
| Maximum Vampires Per Game | The maximum amount of players that can be Vampires | Number | 2 |
| Can Convert Neutral Benign Roles | Whether Neutral Benign Roles can be turned into Vampires | Toggle | False |
| Can Convert Neutral Evil Roles | Whether Neutral Evil Roles can be turned into Vampires | Toggle | False |

-----------------------
## Werewolf
### **Team: Neutral**

The Werewolf is a Neutral role with its own win condition.\
Although the Werwolf has a kill button, they can't use it unless they are Rampaged.\
Once the Werewolf rampages they gain Impostor vision and the ability to kill.\
However, unlike most killers their kill cooldown is really short.\
The Werewolf needs to be the last killer alive to win the game.
### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Werewolf | The percentage probability of the Werewolf appearing | Percentage | 0% |
| Rampage Cooldown | The cooldown of the Werewolf's Rampage button | Time | 25s |
| Rampage Duration | The duration of the Werewolf's Rampage | Time | 25s |
| Rampage Kill Cooldown | The cooldown of the Werewolf's Kill button | Time | 10s |
| Werewolf can Vent when Rampaged | Whether the Werewolf can Vent when Rampaged | Toggle | False |

-----------------------
# Impostor Roles
## Escapist
### **Team: Impostors**

The Escapist is an Impostor that can teleport to a different location.\
Once per round the Escapist can Mark a location which they can then escape to later in the round.

### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Escapist | The percentage probability of the Escapist appearing | Percentage | 0% |
| Recall Cooldown | The cooldown of the Escapist's Recall button | Time | 25s |
| Escapist can Vent | Whether the Escapist can Vent | Toggle | False |

-----------------------
## Grenadier
### **Team: Impostors**

The Grenadier is an Impostor that can throw smoke grenades.\
During the game, the Grenadier has the option to throw down a smoke grenade which blinds crewmates so they can't see.\
However, a sabotage and a smoke grenade can not be active at the same time.

### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Grenadier | The percentage probability of the Grenadier appearing | Percentage | 0% |
| Flash Grenade Cooldown | The cooldown of the Grenadier's Flash button | Time | 25s |
| Flash Grenade Duration | How long the Flash Grenade lasts for | Time | 10s |
| Flash Radius | How wide the flash radius is | Multiplier | 1x |
| Indicate Flashed Crewmates | Whether the Grenadier can see who has been flashed | Toggle | False |
| Grenadier can Vent | Whether the Grenadier can Vent | Toggle | False |
-----------------------
## Morphling
### **Team: Impostors**

The Morphling is an Impostor that can Morph into another player.\
At the beginning of the game and after every meeting, they can choose someone to Sample.\
They can then Morph into that person at any time for a limited amount of time.

### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Morphling | The percentage probability of the Morphling appearing | Percentage | 0% |
| Morph Cooldown | The cooldown of the Morphling's Morph button | Time | 25s |
| Morph Duration | How long the Morph lasts for | Time | 10s |
| Morphling can Vent | Whether the Morphling can Vent | Toggle | False |

-----------------------
## Swooper
### **Team: Impostors**

The Swooper is an Impostor that can temporarily turn invisible.

### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Swooper | The percentage probability of the Swooper appearing | Percentage | 0% |
| Swooper Cooldown | The cooldown of the Swooper's Swoop button | Time | 25s |
| Swooper Duration | How long the Swooping lasts for | Time | 10s |
| Swooper can Vent | Whether the Swooper can Vent | Toggle | False |

-----------------------
## Venerer
### **Team: Impostors**

The Venerer is an Impostor that gains abilities through killing.\
After their first kill, the Venerer can camouflage themself.\
After their second kill, the Venerer can sprint.\
After their third kill, every other player is slowed while their ability is activated.\
All abilities are activated by the one button and have the same duration.

### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Venerer | The percentage probability of the Venerer appearing | Percentage | 0% |
| Ability Cooldown | The cooldown of the Venerer's Ability button | Time | 25s |
| Ability Duration | How long the Venerer's ability lasts for | Time | 10s |
| Sprint Speed | How fast the speed increase of the Venerer is when sprinting | Multiplier | 1.25x |
| Freeze Speed | How slow the speed decrease of other players is when the Venerer's ability is active | Multiplier | 0.75x |
-----------------------
## Bomber
### **Team: Impostors**

The Bomber is an Impostor who has the ability to plant bombs instead of kill.\
After a bomb is planted, the bomb will detonate a fixed time period as per settings.\
Once the bomb detonates it will kill all crewmates (and Impostors!) inside the radius.

### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Bomber | The percentage probability of the Bomber appearing | Percentage | 0% |
| Detonate Delay | The delay of the detonation after bomb has been planted | Time | 5s |
| Max Kills In Detonation | Maximum number of kills in the detonation | Time | 5s |
| Detonate Radius | How wide the detonate radius is | Multiplier | 0.25x |
| Bomber can Vent | Whether the Bomber can Vent | Toggle | False |

-----------------------
## Traitor
### **Team: Impostors**

If all Impostors die before a certain point in the game, a random crewmate is selected to become the Traitor.\
The Traitor has no additional abilities and their job is simply to avenge the dead Impostors.\
Once this player has turned into the Traitor their alliance sits with the Impostors.

### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Traitor | The percentage probability of the Traitor appearing | Percentage | 0% |
| Latest Spawn | The minimum number of people alive when a Traitor can spawn | Number | 5 |
| Traitor Won't Spawn if Neutral Killing are Alive | Whether the Traitor won't spawn if any Neutral Killing roles are alive | Toggle | False |

-----------------------
## Warlock
### **Team: Impostors**

The Warlock is an Impostor that can charge up their kill button.\
Once activated the Warlock can use their kill button infinitely until they run out of charge.\
However, they do not need to fully charge their kill button to use it.

### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Warlock | The percentage probability of the Warlock appearing | Percentage | 0% |
| Time It Takes To Fully Charge | The time it takes to fully charge the Warlock's Kill Button | Time | 25s |
| Time It Takes To Use Full Charge | The maximum duration a charge of the Warlock's Kill Button lasts | Time | 1s |

-----------------------
## Blackmailer
### **Team: Impostors**
The Blackmailer is an Impostor that can silence people in meetings.\
During each round, the Blackmailer can go up to someone and blackmail them.\
This prevents the blackmailed person from speaking during the next meeting.

### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Blackmailer | The percentage probability of the Blackmailer appearing | Percentage | 0% |
| Initial Blackmail Cooldown | The initial cooldown of the Blackmailer's Blackmail button | Time | 10s |

-----------------------
## Janitor
### **Team: Impostors**
The Janitor is an Impostor that can clean up bodies.\
Both their Kill and Clean ability have a shared cooldown, meaning they have to choose which one they want to use.

### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Janitor | The percentage probability of the Janitor appearing | Percentage | 0% |

-----------------------
## Miner
### **Team: Impostors**

The Miner is an Impostor that can create new vents.\
These vents only connect to each other, forming a new passway.

### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Miner | The percentage probability of the Miner appearing | Percentage | 0% |
| Mine Cooldown | The cooldown of the Miner's Mine button | Time | 25s |

-----------------------
## Undertaker
### **Team: Impostors**

The Undertaker is an Impostor that can drag and drop bodies.

### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Undertaker | The percentage probability of the Undertaker appearing | Percentage | 0% |
| Undertaker Drag Cooldown | The cooldown of the Undertaker Drag ability | Time | 25s |
| Undertaker Speed While Dragging | How fast the Undertaker moves while dragging a body in comparison to normal | Multiplier | 0.75x |
| Undertaker can Vent | Whether the Undertaker can Vent | Toggle | False |
| Undertaker can Vent while Dragging | Whether the Undertaker can Vent when they are Dragging a Body | Toggle | False |

-----------------------

# Modifiers
Modifiers are added on top of players' roles.
## Aftermath
### **Applied to: Crewmates**
Killing the Aftermath forces their killer to use their ability (if they have one and it's not in use).
### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Aftermath | The percentage probability of the Aftermath appearing | Percentage | 0% |

-----------------------
## Bait
### **Applied to: Crewmates**
Killing the Bait makes the killer auto self-report.
### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Bait | The percentage probability of the Bait appearing | Percentage | 0% |
| Bait Minimum Delay | The minimum time the killer of the Bait reports the body | Time | 0s |
| Bait Maximum Delay | The maximum time the killer of the Bait reports the body | Time | 1s |

-----------------------
## Diseased
### **Applied to: Crewmates**
Killing the Diseased increases the killer's kill cooldown.
### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Diseased | The percentage probability of the Diseased appearing | Percentage | 0% |
| Kill Multiplier | How much the Kill Cooldown of the Impostor is increased by | Multiplier | 3x |

-----------------------
## Frosty
### **Applied to: Crewmates**
Killing the Frosty slows the killer for a short duration.
### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Frosty | The percentage probability of the Frosty appearing | Percentage | 0% |
| Chill Duration | The duration of the chill after killing the Frosty | Time | 10s |
| Chill Start Speed | The start speed of the chill after killing the Frosty | Multiplier | 0.75x |

-----------------------
## Multitasker
### **Applied to: Crewmates**
The Multitasker's tasks are transparent.
### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Multitasker | The percentage probability of the Multitasker appearing | Percentage | 0% |

-----------------------
## Torch
### **Applied to: Crewmates**
The Torch's vision doesn't get reduced when the lights are sabotaged.
### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Torch | The percentage probability of the Torch appearing | Percentage | 0% |

-----------------------
## Button Barry
### **Applied to: All**
Button Barry has the ability to call a meeting from anywhere on the map, even during sabotages.
They have the same amount of meetings as a regular player.
### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Button Barry | The percentage probability of Button Barry appearing | Percentage | 0% |

-----------------------
## Flash
### **Applied to: All**
The Flash travels at a faster speed in comparison to a normal player.
### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Flash | The percentage probability of the Flash appearing | Percentage | 0% |
| Speed | How fast the Flash moves in comparison to normal | Multiplier | 1.25x |

-----------------------
## Giant
### **Applied to: All**
The Giant is a gigantic Crewmate, that has a decreased walk speed.
### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Giant | The percentage probability of the Giant appearing | Percentage | 0% |
| Speed | How fast the Giant moves in comparison to normal | Multiplier | 0.75x |

-----------------------
## Lovers
### **Applied to: All**
The Lovers are two players who are linked together.\
These two players get picked randomly between Crewmates and Impostors.\
They gain the primary objective to stay alive together.\
If they are both among the last 3 players, they win.\
In order to do so, they gain access to a private chat, only visible by them in between meetings.\
However, they can also win with their respective team, hence why the Lovers do not know the role of the other lover.

### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Lovers | The percentage probability of the Lovers appearing | Percentage | 0% |
| Both Lovers Die | Whether the other Lover automatically dies if the other does | Toggle | True |
| Loving Impostor Probability | The chances of one lover being an Impostor | Percentage | 20% |
| Neutral Roles Can Be Lovers | Whether a Lover can be a Neutral Role | Toggle | True |

-----------------------
## Radar
### **Applied to: All**
The Radar is a crewmate who knows where the closest player is to them.
### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Radar | The percentage probability of the Radar appearing | Percentage | 0% |

-----------------------
## Sleuth
### **Applied to: All**
The Sleuth is a crewmate who gains knowledge from reporting dead bodies.\
During meetings the Sleuth can see the roles of all players in which they've reported.
### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Sleuth | The percentage probability of the Sleuth appearing | Percentage | 0% |

-----------------------
## Tiebreaker
### **Applied to: All**
If any vote is a draw, the Tiebreaker's vote will go through.\
If they voted another player, they will get voted out.
### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Tiebreaker | The percentage probability of the Tiebreaker appearing | Percentage | 0% |

-----------------------
## Disperser
### **Applied to: Impostors**
The Disperser is an Impostor who has a 1 time use ability to send all players to a random vent.\
This includes miner vents.\
Does not appear on Airship or Submerged.
### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Disperser | The percentage probability of the Disperser appearing | Percentage | 0% |

-----------------------
## Double Shot
### **Applied to: Impostors**
Double Shot is an Impostor who gets an extra life when assassinating.\
Once they use their life they are indicated with a red flash\
and can no longer guess the person who they guessed wrong for the remainder of that meeting.
### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Double Shot| The percentage probability of Double Shot appearing | Percentage | 0% |

-----------------------
## Underdog
### **Applied to: Impostors**

The Underdog is an Impostor with a prolonged kill cooldown.\
When they are the only remaining Impostor, they will have their kill cooldown shortened.

### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Underdog | The percentage probability of the Underdog appearing | Percentage | 0% |
| Kill Cooldown Bonus | The amount of time added or removed from the Underdog's Kill Cooldown | Time | 5s |
| Increased Kill Cooldown  | Whether the Underdog's Kill Cooldown is Increased when 2+ Imps are alive | Toggle | True |

-----------------------
# Game Mode Settings
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Game Mode | What game mode the next game will be | Classic / All Any / Killing Only / Cultist | Classic |

-----------------------
# Classic Game Mode Settings
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Min Neutral Benign Roles | The minimum number of Neutral Benign roles a game can have | Number | 1 |
| Max Neutral Benign Roles | The maximum number of Neutral Benign roles a game can have | Number | 1 |
| Min Neutral Evil Roles | The minimum number of Neutral Evil roles a game can have | Number | 1 |
| Max Neutral Evil Roles | The maximum number of Neutral Evil roles a game can have | Number | 1 |
| Min Neutral Killing Roles | The minimum number of Neutral Killing roles a game can have | Number | 1 |
| Max Neutral Killing Roles | The maximum number of Neutral Killing roles a game can have | Number | 1 |

-----------------------
# All Any Settings
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Random Number of Impostors | Whether there are a random number of Impostors | Toggle | True |

-----------------------
# Killing Only Settings
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Neutral Roles | How many neutrals roles will spawn | Number | 1 |
| Veteran Count | How many Veterans will spawn | Number | 1 |
| Vigilante Count | How many Vigilantes will spawn | Number | 1 |
| Add Arsonist | Whether Arsonist will be added to the role list | Toggle | True |
| Add Plaguebearer | Whether Plaguebearer will be added to the role list | Toggle | True |

-----------------------
# Cultist Settings
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Mayor | The percentage probability of the Mayor appearing | Percentage | 0% |
| Seer | The percentage probability of the Seer appearing | Percentage | 0% |
| Sheriff | The percentage probability of the Sheriff appearing | Percentage | 0% |
| Survivor | The percentage probability of the Survivor appearing | Percentage | 0% |
| Number Of Special Roles | How many special roles will spawn | Number | 4 |
| Max Chameleons | The maximum number of Chameleons that can spawn | Number | 3 |
| Max Engineers | The maximum number of Engineers that can spawn | Number | 3 |
| Max Investigators | The maximum number of Investigators that can spawn | Number | 3 |
| Max Mystics | The maximum number of Mystics that can spawn | Number | 3 |
| Max Snitches | The maximum number of Snitches that can spawn | Number | 3 |
| Max Spies | The maximum number of Spies that can spawn | Number | 3 |
| Max Transporters | The maximum number of Transporters that can spawn | Number | 3 |
| Max Vigilantes | The maximum number of Vigilantes that can spawn | Number | 3 |
| Initial Whisper Cooldown | The initial cooldown of the Whisperer's Whisper button | Time | 25s |
| Increased Cooldown Per Whisper | The amount of time the Whisperer's whisper cooldown increases by per Whisper | Time | 5s |
| Whisper Radius | How wide the whisper radius is | Multiplier | 0.25x |
| Conversion Percentage | The percentage someone is leant towards being converted (addition not chance) | Percentage | 25% |
| Decreased Conversion Percentage Per Conversion | The percentage decrease of the conversion percentage with each conversion | Percentage | 5% |
| Initial Revive Cooldown | The initial cooldown of the Necromancer's Revive button | Time | 25s |
| Increased Cooldown Per Revive | The amount of time the Necromancer's revive cooldown increases by per Revive | Time | 25s |
| Maximum Number Of Reveals | The maximum number of times the Seer can reveal someone | Number | 5 |

-----------------------
# Map Settings
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Choose Random Map | Whether the Map is randomly picked at the start of the game | Toggle | False |
| Skeld Chance | The percentage probability of the Skeld map being chosen | Percentage | 0% |
| Mira HQ Chance | The percentage probability of the Mira HQ map being chosen | Percentage | 0% |
| Polus Chance | The percentage probability of the Polus map being chosen | Percentage | 0% |
| Airship Chance | The percentage probability of the Airship map being chosen | Percentage | 0% |
| Submerged Chance | The percentage probability of the Submerged map being chosen | Percentage | 0% |
| Auto Adjust Settings | Whether the Settings of the game are auto adjusted depending on the map | Toggle | False |
| Half Vision on Skeld/Mira HQ | Whether the Vision is automatically halved on Skeld/Mira HQ | Toggle | False |
| Mira HQ Decreased Cooldowns | How much less time the cooldowns are set to for Mira HQ | Time | 0s |
| Airship/Submerged Increased Cooldowns | How much more time the cooldowns are set to for Airship/Submerged | Time | 0s |
| Skeld/Mira HQ Increased Short Tasks | How many extra short tasks when the map is Skeld/Mira HQ | Number | 0 |
| Skeld/Mira HQ Increased Longt Tasks | How many extra long tasks when the map is Skeld/Mira HQ | Number | 0 |
| Airship/Submerged Decreased Short Tasks | How many less short tasks when the map is Airship/Submerged | Number | 0 |
| Airship/Submerged Decreased Longt Tasks | How many less long tasks when the map is Airship/Submerged | Number | 0 |

-----------------------
# Better Polus Settings
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Better Polus Vent Layout | Optimises Vent Layout on Polus | Toggle | False |
| Vitals Moved to Lab | Whether the Vitals panel is moved into the Laboratory | Toggle | False |
| Cole Temp Moved to Death Valley | Whether the cold temperaure task is moved to death valley | Toggle | False |
| Reboot Wifi and Chart Course Swapped | Whether the Reboot Wifi and Chart Course swap locations | Toggle | False |

-----------------------
# Custom Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Camouflaged Comms | Whether everyone becomes camouflaged when Comms are sabotaged | Toggle | False |
| Impostors can see the roles of their team | Whether Impostors are able to see which Impostor roles their teammates have | Toggle | False |
| Dead can see everyone's roles and Votes | Whether dead players are able to see the roles and votes of everyone else | Toggle | False |
| Game Start Cooldowns | The cooldown for all roles at the start of the game | Time | 10s |
| Parallel Medbay Scans | Whether players have to wait for others to scan | Toggle | False |
| Disable Meeting Skip Button | Whether the meeting button is disabled | No / Emergency / Always | No |
| Enable Hidden Roles | Whether hidden roles are added to the role selections | Toggle | True |
| First Death Shield Next Game | Whether the first player to die gets a shield for the first round next game | Toggle | False |

-----------------------
# Task Tracking Settings
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| See Tasks During Round | Whether people see their tasks update in game | Toggle | False |
| See Tasks During Meetings | Whether people see their task count during meetings | Toggle | False |
| See Tasks When Dead | Whether people see everyone's tasks when they're dead | Toggle | False |

-----------------------
## Assassin Ability
### **Team: Impostors**

The Assassin Ability is given to a certain number of Impostors or Neutral Killers.\
This ability gives the Impostor or Neutral Killer a chance to kill during meetings by guessing the roles or modifiers of others.\
If they guess wrong, they die instead.

### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Number of Impostor Assassins | How many Impostors can Assassinate | Number | 1 |
| Number of Neutral Killing Assassins | How many Neutral Killers can Assassinate | Number | 1 |
| Amnesiac Turned Impostor Can Assassinate | Whether former Amnesiacs now Impostor can Assassinate | Toggle | False |
| Amnesiac Turned Neutral Killing Can Assassinate | Whether former Amnesiacs now Neutral Killers can Assassinate | Toggle | False |
| Traitor Can Assassinate | If someone turns into a Traitor they can Assassinate | Toggle | False |
| Assassin Kill | The number of kill the Assassin can do with his ability | Number | 1 |
| Assassin Guess Crewmate | Whether the Assassin can Guess "Crewmate" | Toggle | False |
| Assassin Multiple Kill  | Whether the Assassin can kill more than once per meeting | Toggle | False |
| Assassin Guess Neutral Benign  | Whether the Assassin can Guess Neutral Benign roles | Toggle | False |
| Assassin Guess Neutral Evil  | Whether the Assassin can Guess Neutral Evil roles | Toggle | False |
| Assassin Guess Neutral Killing  | Whether the Assassin can Guess Neutral Killing roles | Toggle | False |
| Assassin Guess Impostors  | Whether the Assassin can Guess Impostor roles | Toggle | False |
| Assassin Guess Crewmate Modifiers  | Whether the Assassin can Guess Crewmate Modifiers | Toggle | False |
| Assassin Can Guess Lovers  | Whether the Assassin can Guess Lovers | Toggle | False |
| Assassin Can Guess After Voting  | Whether the Assassin can Guess after voting | Toggle | False |

-----------------------
# Extras
## New Colors!
New colors are added for crewmates to pick from.
## Rainbow Color!
A rainbow color has also been added. Anyone who equips this color will constantly switch between the colors of the rainbow.
## Custom Hats!
Custom hats have been added, made by some very talented artists. These are mostly hats for streamers.

-----------------------
# Bug / Suggestions
If you have any bugs or any need to contact me, join the [Discord Server](https://discord.gg/ugyc4EVUYZ) or create a ticket on GitHub.

-----------------------
# Credits & Resources
[Reactor](https://github.com/NuclearPowered/Reactor) - The framework of the mod\
[BepInEx](https://github.com/BepInEx) - For hooking game functions\
[Among-Us-Sheriff-Mod](https://github.com/Woodi-dev/Among-Us-Sheriff-Mod) - For the Sheriff role.\
[Among-Us-Love-Couple-Mod](https://github.com/Woodi-dev/Among-Us-Love-Couple-Mod) - For the inspiration of Lovers role.\
[ExtraRolesAmongUs](https://github.com/NotHunter101/ExtraRolesAmongUs) - For the Engineer & Medic roles.\
[TooManyRolesMods](https://github.com/Hardel-DW/TooManyRolesMods) - For the Investigator & Time Lord roles.\
[TorchMod](https://github.com/tomozbot/TorchMod) - For the inspiration of the Torch modifier.\
[XtraCube](https://github.com/XtraCube) - For the RainbowMod.\
[PhasmoFireGod](https://twitch.tv/PhasmoFireGod) and [Ophidian](https://www.instagram.com/ixean.studio) - Button Art.\
[TheOtherRoles](https://github.com/Eisbison/TheOtherRoles) - For the inspiration of the Vigilante, Tracker and Spy roles, as well as the Bait modifier.\
[5up](https://www.twitch.tv/5uppp) and the Submarine Team - For the inspiration of the Grenadier role.\
[Guus](https://github.com/OhMyGuus) - For support for the old Among Us versions (v2021.11.9.5 and v2021.12.15).\
[MyDragonBreath](https://github.com/MyDragonBreath) - For Submerged Compatibility, the Trapper and Aurial roles, the Aftermath modifier and support for the new Among Us versions (v2022.6.21 & v2023.6.13).\
[ItsTheNumberH](https://github.com/itsTheNumberH/Town-Of-H) - For the code used for Blind, Bait, Poisoner and partially for Tracker, as well as other bug fixes.\
[Ruiner](https://github.com/ruiner189/Town-Of-Us-Redux) - For lovers changed into a modifier and Task Tracking.\
[Term](https://www.twitch.tv/termboii) - For creating Transporter, Medium, Blackmailer, Plaguebearer, Sleuth, Multitasker and porting v2.5.0 to the new Among Us version (v2021.12.15).\
[BryBry16](https://github.com/Brybry16/BetterPolus) - For the code used for Better Polus.\
[Alexejhero](https://github.com/SubmergedAmongUs/Submerged) - For the Submerged map.

[Essentials](https://github.com/DorCoMaNdO/Reactor-Essentials) - For created custom game options.\
v1.0.3 uses [Essentials](https://github.com/DorCoMaNdO/Reactor-Essentials) directly.\
v1.1.0 uses a modified version of Essentials that can be found [here](https://github.com/slushiegoose/Reactor-Essentials).\
v1.2.0 has Essentials embedded and can be found [here](https://github.com/slushiegoose/Town-Of-Us/tree/master/source/Patches/CustomOption).

#
<p align="center">This mod is not affiliated with Among Us or Innersloth LLC, and the content contained therein is not endorsed or otherwise sponsored by Innersloth LLC. Portions of the materials contained herein are property of Innersloth LLC.</p>
<p align="center">© Innersloth LLC.</p>
