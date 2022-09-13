# DevTools
#Setup

# Set Powershell to default profile

Remove powershell startup text
Add "-nologo" to powershell path

![image](https://user-images.githubusercontent.com/6838752/189899279-3075d37c-2a8b-4590-979a-a47b8cb27685.png)




#Install font

#Caskaydia Cove Nerd Font Complete
https://github.com/ryanoasis/nerd-fonts/releases/download/v2.1.0/CascadiaCode.zip?WT.mc_id=-blog-scottha

# Set WindowsTerminal To use Caskaydia Cove Nerd Font

# Install OhMyPosh
winget install JanDeDobbeleer.OhMyPosh
# restart shell to reload PATH


#Install modul in powershell
Install-Module -Name Terminal-Icons -Repository PSGallery
Install-Module PSReadLine -AllowPrerelease -Force


#Add to powershell profile
# Use custom oh my posh template
oh-my-posh init pwsh --config https://raw.githubusercontent.com/vindelbo/public/main/WindowsTerminal/oh-my-posh.json | Invoke-Expression


# Add nice icons to ls/dir
Import-Module -Name Terminal-Icons

# Add typeahed 
Import-Module PSReadLine
Set-PSReadLineOption -PredictionSource History
Set-PSReadLineOption -PredictionViewStyle ListView
Set-PSReadLineOption -EditMode Windows
