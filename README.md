# SxG.OhMyPosh-Setup

## Windows Terminal
Install Windows Terminal from the store of use the link below:
```
https://www.microsoft.com/en-us/p/windows-terminal/9n0dx20hk701?activetab=pivot:overviewtab
```

## Git for Windows
Install Git for Windows:
```
https://gitforwindows.org/
```

## Posh-Git and Oh-My-Posh
Install Posh-Git:
```
Install-Module posh-git -Scope CurrentUser
```

Install Oh-My-Posh:
```
Install-Module oh-my-posh -Scope CurrentUser
```

## Modify ```$PROFILE```
With VS Code installed:
```
Code $PROFILE
```

Otherwise:
```
Notepad PROFILE
```

Add below statements to the file:

```
Import-Module posh-git
Import-Module oh-my-posh
Set-PoshPrompt -Theme plague
```

Note: ```plague``` can be replaced with any other theme you like. They can be found here:
```
https://ohmyposh.dev/docs/themes
```
TO CHECK: For local (custom) themes, supply the path to the theme.

## Font

Install the ```Meslo``` fonts bundled in this repository.

1. In Terminal press ctrl + , to open settings.
2. Go to powershell profile.
3. Open appearance tab.
4. Select a font.
