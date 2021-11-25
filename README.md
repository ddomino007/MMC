# MMC
# MacOS Friendly edits POC (WIP)
## Current Version: 0.2
MatroSka Mod Compiler for .ts4script files  
![MMC Logo](/mmc_icon_small.png)

## Requirements
* Have Python 3.7 installed and set as default.
* for Python on OSX, you of course need to have xcode cli tools installed. run "xcode-select --install" in terminal and follow the prompts to install them
### Running from Source
```
pip install virtualenv colorama 
python mmc.py
```

### Running from Binary
```
pip install virtualenv
mmc.exe
```

## Please Note
* The script file is pretty dirty and still needs A LOT of cleanup work.

*I am aware that the binary has false flags from multiple AntiVirusses.  
(This is a pyinstaller thing, and I can't change that unfortunately)*
