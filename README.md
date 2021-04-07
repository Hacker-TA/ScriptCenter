# ScriptCenter
Script data for the Splash project.

# Script reading structure.
The setup looks like this:
```ini
[Settings]
scripts=N
```
Where N is the number of scripts to be displayed.
#
The setting for display looks like this:
```ini
[ScriptN']
title=Name N' Script
description=Description of the N 'script.
scriptlink=RAW Link where the script is located N'.
img=Link to the image that will display N'.
```

# Templete:
Let's say we want to add 10 script.
```ini
[Settings]
scripts=10

... 

[Script10]
title=SplashHub
description=ScriptHub for Roblox 10+ games.
scriptlink=https://raw.githubusercontent.com/iliasaw2/inject/main/Splash.lua
img=https://cdn.discordapp.com/attachments/764776537870172179/829292380011757618/1617789099058.jpg
```
![alt-текст](https://media.discordapp.net/attachments/764776538012647435/829311379353370624/unknown.png "This is how it looks in the Splash Script-Center project.")
