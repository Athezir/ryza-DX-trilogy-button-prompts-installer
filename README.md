# Ryza Button Prompts Installer

One small installer for all the **More Button Prompts** mods by **Athezir**: the Atelier Ryza trilogy (DX versions).
Pick your button style (PlayStation 5, PlayStation 4 or Nintendo Switch) and your language(s) by typing numbers.

There is **one installer for every game**. The **data file** you download from Nexus Mods holds the textures and tells the installer which game and mod it is.

## How to install

1. **Download the installer (the same one for every game):** [RyzaButtonPromptsInstaller.exe](../../releases/latest/download/RyzaButtonPromptsInstaller.exe)
2. **Download the data file (`.dat`) for your game** from its Nexus Mods page:

   | Game | Data file |
   |---|---|
   | Atelier Ryza: Ever Darkness & the Secret Hideout DX | [Nexus page](https://www.nexusmods.com/atelierryza1/mods/8) |
   | Atelier Ryza 2: Lost Legends & the Secret Fairy DX | [Nexus page](https://www.nexusmods.com/atelierryza2lostlegendsthesecretfairydx/mods/4)|
   | Atelier Ryza 3: Alchemist of the End & the Secret Key DX | [Nexus page](https://www.nexusmods.com/atelierryza3/mods/7)|

3. Put **both files** in your game folder, the one that contains the game's `.exe` (`Atelier_Ryza_DX.exe`, `Atelier_Ryza_2_DX.exe` or `Atelier_Ryza_3_DX.exe`).
4. Run the installer. The menu shows which game and mod it found.
5. Press the number for your button version, then the number(s) for your language(s), and confirm. The window closes by itself.

The shared textures (`PACK00_01`) are always installed. You can install several languages at once, or press Enter to install all of them.

## How to uninstall

Run the installer again and choose **Restore original files**. It keeps a backup of every game file it changes (`.pak.bak`), so the originals come back exactly as they were. Steam's *Verify integrity of game files* also works.

## Notes

- Close the game before installing.
- This is a self-contained installer with no external dependencies. It performs local file operations only.

## Credits

- PAK file format knowledge from [gust_tools](https://github.com/VitaSmith/gust_tools) by VitaSmith
- Atelier Ryza is a game by Gust / Koei Tecmo. This is an unofficial fan mod and is not affiliated with them.
