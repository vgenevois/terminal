# Windows Terminal Settings

## Installation
### [Oh-My-Posh](https://github.com/JanDeDobbeleer/oh-my-posh)
Install the following lines in PowerShell ( Use it as administrator ) :
```sh
Install-Module posh-git -Scope CurrentUser
Install-Module oh-my-posh -Scope CurrentUser
```
```sh
Install-Module -Name PSReadLine -AllowPrerelease -Scope CurrentUser -Force -SkipPublisherCheck
```
To enable the PowerShell profile :
```sh
notepad $PROFILE
```
And append the following to your profile :
```sh
Import-Module posh-git
Import-Module oh-my-posh
Set-Theme Paradox
```

