# Pre-configured Sophia Scripts for Windows 11 (Powershell 5.1 only)

## How to
* The files here replace the original Sophia.ps1 from https://github.com/farag2/Sophia-Script-for-Windows
* Please check 'sophia_script_version.txt' to make sure it's compatible with your Sophia script, or try to diff the files to Sophia.ps1

## For Power Users (disabling most features which aren't necessary + performance focus)
Russia settings were disabled, most options which disable services are enabled,
Aero settings, wallpaper size, etc, are given the best performance settings(NOT the best quality),

NOTE: Restore point disabled, power users will create their own

`sophia_pwsh51_poweruser.ps1` for Powershell 5.1  

## For Regular Users
`sophia_pwsh51_regular.ps1` for Powershell 5.1  

## For Laptops, disable the following settings
PowerPlan -High
NetworkAdaptersSavePower -Disable
Hibernation -Disable
