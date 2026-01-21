# Pre-configured Sophia Scripts for Windows 11 (Powershell 5.1 only)

## How to
* The files here replace the original Sophia.ps1 from https://github.com/farag2/Sophia-Script-for-Windows
* Please check 'sophia_script_version.txt' to make sure it's compatible with your Sophia script, or try to diff the files to Sophia.ps1
* I've commented the original file with notes to higlight options to each category: casual user, power user and some users
  ** Power Users - Usually want to have the best performance, features and advanced options
  ** Casual Users - The "Vanilla" experience, avoding hidden files and other problematic settings for casuals, but with privacy and other good options which are invisible to them
  ** Some Users - Any comment containing this is a personal choice, like dark theme icons, behavior, etc
  ** Laptop Users - Options which WILL affect your laptop, the most important ones are also specified at the bottom of this readme

NOTE: REMEMBER! The comments I've added are relative to the default file, there's no point in commenting the already commented original Sophia script

You can search for these comments:
  
```
NOTE: Power users may want to ...
NOTE: Casual users may want to ...
NOTE: Some users may want to ...
NOTE: Laptop users may want to ...
```

## For Power Users (disabling most features which aren't necessary + performance focus)
Russia settings were disabled, most options which disable services are enabled,
Aero settings, wallpaper size, etc, are given the best performance settings(NOT the best quality),

NOTE: Restore point disabled, power users will create their own

`sophia_pwsh51_poweruser.ps1` for Powershell 5.1  

## For Casual Users
`sophia_pwsh51_casual.ps1` for Powershell 5.1  

## For Laptops, disable the following settings
PowerPlan -High
NetworkAdaptersSavePower -Disable
Hibernation -Disable
