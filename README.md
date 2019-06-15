# tts-dominion

### Host Quick-Start Guide
1. On GitHub, click "Clone or download" > Download ZIP
2. Unzip, and copy the /save directory's contents into your TTS save file directory, except for SaveFileInfos.json
3. Open the SaveFileInfos.json file in notepad, and put in your Windows username
4. Each set of curly braces contain a save file definition. Copy the save file definition you just changed into your existing TTS' SaveFileInfos.json. If its the last entry, don't forget to put a comma before it
5. Load the save and enjoy!

### Developer Guide
1. Download the [Atom](https://atom.io/) text editor, and install + enable the tabletopsimulator-lua package
2. Open the package's settings, and find the "base path for files you wish to #include" setting
3. Change the path to be the /src directory of this repository
4. Open Tabletop Simulator, and load the included save file (not in this repo yet)
5. Once the game is loaded, press ctrl+shift+L
6. Copy this repo's /src directory into the Tabletop Simulator Lua directory and press ctrl+shift+S

<b>NOTE</b>: To test your changes in TTS, just press ctrl+shift+S in Atom

<b>ALSO</b>: If you make changes to Global.-1.ttslua in the Tabletop Simulator Lua directory, please remember to change the repo's copy too
