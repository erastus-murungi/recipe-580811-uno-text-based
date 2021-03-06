This repository covers the following recipe from code.activestate.com:

[UNO (TEXT-BASED)
](https://code.activestate.com/recipes/580811/)

*Created by Brandon Martin on Sat, 15 Jul 2017*

A text based recreation of the classic card game featuring functional AIs to play with. Some rules have been modified. User interface is text based, non-curses, using only simple python commands to draw it.

## Usage

If you already have the [State Tool] installed you can simply run

```
state activate ActiveState-Recipes/recipe-580811-uno-text-based
```

If you do not have the [State Tool] installed you can use the following convenient one-liner.

Linux: 
```
sh <(curl -q https://platform.activestate.com/dl/cli/install.sh) -n -f && state activate --path $HOME/ActiveState-Recipes/recipe-580811-uno-text-based ActiveState-Recipes/recipe-580811-uno-text-based
```

Windows: 
```
powershell "Set-Item -Path Env:NOPROMPT_INSTALL -Value 'true'; IEX(New-Object Net.WebClient).downloadString('https://platform.activestate.com/dl/cli/install.ps1')" && state activate --path %APPDATA%/ActiveState-Recipes/recipe-580811-uno-text-based ActiveState-Recipes/recipe-580811-uno-text-based
```

macOS: not yet supported

[State Tool]: https://www.activestate.com/products/platform/state-tool/
