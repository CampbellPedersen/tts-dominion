# tts-dominion

### Host Quick-Start Guide
1. On GitHub, click "Clone or download" > Download ZIP
2. Unzip, and copy the /save directory's contents into your TTS save file directory, except for SaveFileInfos.json
3. Open the SaveFileInfos.json file in notepad, and put in your Windows username
4. Each set of curly braces contain a save file definition. Copy the save file definition you just changed into your existing TTS' SaveFileInfos.json. If its the last entry, don't forget to put a comma before it
5. Open TTS, and load the save you just put in

### Developer Guide
1. Download the [Atom](https://atom.io/) text editor, and install + enable the tabletopsimulator-lua package
2. Open the package's settings, and find the "base path for files you wish to #include" setting
3. Change the path to be the /src directory of this repository
4. Open TTS and load the included save file
5. Once the game is loaded, press ctrl+shift+L

#### Developer tips
- To test your changes in TTS, just press ctrl+shift+S in Atom
- To make changes to TTS's object scripts, you must change them in the Tabletop Simulator Lua directory.
- If you make changes to any global/object scripts in the Tabletop Simulator Lua directory, please remember to change the repo's copy too
