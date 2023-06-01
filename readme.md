<h1 align="center">999 Engine</h1>

- Recompiled [Cheat Engine](https://github.com/cheat-engine) to run along **Forza Horizon 5**, but will also work as the normal cheatengine

- A good thing to note is that it most likely wont work on any of the kernel anticheats (wasnt tested and wont be)

<h2 align="center">Table of Contents</h2>

* [Planned And The Features](#planned-and-the-features)
* [Virus Total](#virustotal)
* [Setup / Compile yourself](#compiling-yourself)
* [Screenshots](#screenshots)
* [Contact](#contact)


<h2 align="center">Planned And The Features</h2>

### Features:

[- Cars](https://forzamods.github.io/website/cars999)

[- Credits](https://forzamods.github.io/website/credits999)

[- XP](https://forzamods.github.io/website/xp999)

Any many more if you find out how yourself

### Planned:
- Remake the current [skilltree guide](https://forzamods.github.io/website/skilltree)
- Find out how to get free cars

<h2 align="center">VirusTotal</h2>

### Themida Packed Files:

[999 Engine x64](https://www.virustotal.com/gui/file/48aa85535b1db7d26608c56e72afcf77bad4fb1dd2d436fb143063a96b0f50a9) | **4/67**

[999 Engine x64 O4 AVX2](https://www.virustotal.com/gui/file/391461366fe0c454179c4a2d4e0473583f57c780d0bcccb11b738f5b04e7e446) | **3/70**

### Non Themida Packed Files:

[999 Engine x64](https://www.virustotal.com/gui/file/fe5572fb4e298321bcce309fa5b0b74ea03372d5a8535cf96349cb50a66f3f8e?nocache=1) | **1/70**

[999 Engine x64 O4 AVX2](https://www.virustotal.com/gui/file/8ce1b2457490a695b8289b267265ecafbcd4ce4f3720b3d978965a9a8f159a58?nocache=1) | **1/71**

<h2 align="center">Compiling yourself</h2>

### Required:

[- Lazarus](https://sourceforge.net/projects/lazarus/files/Lazarus%20Windows%2064%20bits/Lazarus%202.2.2/) (Firstly install the **_win64_** one, then the **_cross-i386_**)

[- Themida](https://www.upload.ee/files/13313536/Themida_x32_x64_v3.0.4.0_Repacked.zip.html)

 Downloaded source of this project

### Optional:

[- HXD](https://mh-nexus.de/en/downloads.php?product=HxD20) (For [CE Strings](#optional-ce-string-editing) editing)

---

### Guides:

<details>
<summary><h4>Compiling</h4></summary>

When you already installed lazarus, go to the extracted project folder 

Look for a file called `cheatengine.lpi` then open it

Now click on `Run > Compile Many Nodes`, select `Release 64-bit` and `Release 64-bit O4 AVX2`

<details>
<summary><h4>If failed / Pascal error</h4></summary>

Go to `Project > Project Options > Compiler Options > Build Nodes` and set it to `Release 64-bit`

Then `Run > Build`

</details>

<details>
<summary><h4>(OPTIONAL) If you want to change the version info, icon or something else</h4></summary>

Simply go to the `Project > Project options` and setup things however you want


</details>

<details> 
<summary><h4>(OPTIONAL) The change my custom window title</h4></summary>

In the project folder, look for a file called `MainUnit2.pas` and open it

What youre intrested in is, line `33` and line `44`

Change the `strCheatEngine` to whatever you want, and to remove the `| 999 Engine` part, simply delete the 

`+' | 999 Engine'` part in the 44th line

</details>

<details>
<summary><h4>(OPTIONAL) Compiling the launcher</h4></summary>

Open the project foler, go to the `launcher` folder, and open the `cheatengine.lpi`

If you want to change the version info, icon or something else, simply go to the `Project > Project options` and setup things however you want

---

**IMPORTANT THING TO NOTE**

Please match the `basename` to the prefix of your exename, thanks

</details>
</details>

---

<details>
<summary><h4>Themida</h4></summary>

Download and open [Themida](https://www.upload.ee/files/13313536/Themida_x32_x64_v3.0.4.0_Repacked.zip.html) (Run the `Themida64.exe` version)

#### Here are my settings:

<details>
<summary><h4>Protection Options</h4></summary>

![Protection Options](/Images/protectionoptions.png)

</details>

<details>
<summary><h4>Extra Options</h4></summary>

![Extra Options](/Images/extraoptions.png)

</details>

<details>
<summary><h4>Advanced Options</h4></summary>

In this tab, you need to add `Themida Keys` one by one.

Here they are:

`OPTION_ADVANCED_HEURISTIC_PRETTY_NAMES=YES`

`OPTION_ADVANCED_HEURISTIC_FAKE_RESOURCES=YES`

`OPTION_ADVANCED_HEURISTIC_ENTRY_FIRST_SECTION=YES`

<details>
<summary><h4>Click here to view the image of how it should look</h4></summary>

![Advanced Options](/Images/advancedoptions.png)

</details>

</details>

</details>

---

<details>
<summary><h4>(OPTIONAL) CE String Editing</h4></summary>

**If youre recompiling for forza, this isnt really required. But if you want so then go ahead**

Drag and drop your recompiled CE exe onto [HXD](https://mh-nexus.de/en/downloads.php?product=HxD20) 

Now replace these strings, remember to turn on `Case sensitive`

(`YourName` needs to be something that contains 5 characters for example: `Sunny`)

**With Editor Encoding**

`Cheat Engine` to `YourName Engine`

`cheat engine` to `YourName engine`

`CheatEngine` to `YourNameEngine`

`cheatengine` to `YourNameengine`


**With Unicode Encoding**

`Cheat Engine` to `YourName Engine`

`CheatEngine` to `YourNameEngine`

</details>

<h2 align="center">Authors</h2>

- [Dark Byte](https://github.com/cheat-engine)

<h2 align="center">Screenshots</h2>

![Running With Forza](/Images/workingalongforza.png)
![Funne CR](/Images/funnecr.png)
![Funne XP](/Images/funnexp.png)
![Cool stuff you can do](https://cdn.discordapp.com/attachments/1022453919496011776/1092082817162301530/image.png)

<h2 align="center">Contact</h2>

For any help go on the [Forza Mods Discord Server](https://discord.gg/forzamods).

If you think I made any mistakes while writing this, or forgot something please make a pull request

I will be more than happy to take a look