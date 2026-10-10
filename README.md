# Japanese-Yasuke
Model changes of Yasuke to be as he should have been.

Step into Assassin’s Creed Shadows as Kurogane Yasuke, a Japanese samurai, and experience feudal Japan through new eyes. Travel its countryside, challenge its enemies and carve your path through a world at war.
All of Yasuke’s gameplay features remain fully functional, including combat abilities, weapons, armour and equipment. Lip sync, facial animation and motion capture work with the new character in real-time cutscenes.
Prerecorded cutscenes retain the original character, as his appearance is part of the video itself.
Assassin’s Creed Shadows on Windows PC.
The game must be closed during installation or removal.

Install all six mod files together and keep their original names. Other mods that change the same character may conflict.



Save your game and close Assassin’s Creed Shadows.
Extract the download somewhere
Locate your game installation—the folder containing ACShadows.exe
Open PowerShell inside the extracted mod folder.
Run the following command, replacing <GAME_FOLDER> with your installation folder and keeping the quotation marks:
.\Manage-Mod.ps1 -Action Check -GameDirectory "<GAME_FOLDER>"
6. Once the compatibility check passes, install the mod via powershell:
.\Manage-Mod.ps1 -Action Install -GameDirectory "<GAME_FOLDER>"
7. Launch the game normally and load a save where Yasuke is playable.
Your new character is ready for the adventure.

The compatibility check reads approximately 43 GB of existing game files, so allow a few minutes. It does not download or duplicate those files. The installer checks compatibility again before installation and never overwrites existing files.
If PowerShell prevents the script from running, use the manual instructions below. You do not need to change your system’s security settings.


Close the game.
Extract the mod download outside your game folder.
Check your game folder for existing boot patches. A compatible installation without this mod should contain patches 01 and 02. If patch 03 or higher is already present, resolve that mod or version conflict before proceeding.
Copy these six files from the download’s Files folder directly into the folder containing ACShadows.exe:  Copy the six files themselves
DataPC_boot_patch_03.forge
DataPC_boot_patch_04.forge
DataPC_boot_patch_05.forge
DataPC_boot_patch_06.forge
DataPC_boot_patch_07.forge
DataPC_boot_patch_08.forge
Launch the game normally.

If Windows asks to replace an existing file, cancel. Do not overwrite another mod or rename these files to different patch numbers.


Close the game, open PowerShell in the extracted mod folder, and run:
.\Manage-Mod.ps1 -Action Uninstall -GameDirectory "<GAME_FOLDER>"
Replace <GAME_FOLDER> with your game installation folder.
The manager verifies the installed files and moves this mod’s matching files into a dated folder under 'Removed'. Your original game files remain in place.
