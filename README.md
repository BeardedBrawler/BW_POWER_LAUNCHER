# BW_POWER_LAUNCHER
Bourbon Warfare powershell based Arma Launcher

The .ps1 file can be placed anywhere on your PC and run with regular user permissions.
The .ps1 file looks in the conf directory for a the BW_Launcher_conf.xml file to get information on mods and servers.

You'll probably have to start powershell as admin and execute the following

Set-ExecutionPolicy RemoteSigned

Say Yes to everything
EXIT YOUR ADMIN POWERSHELL SESSION, CLOSE IT OUT

right-click on Bourbon Warfare Private Client Launcher GUI.ps1 and choose RUN with Powershell

Choose your MODSET From the dropdown
Choose your server from the dropdown
Click KICKOFF!!
Grab beer
Play

If you want a single icon to double-click and run then create a shortcut to the ps1 file and place it where you'd like (i.e. Desktop). Right-click on the shortcut and update the TARGET to include the invoking of powerhell.exe 

Example:
C:\Windows\System32\WindowsPowerShell\v1.0\powershell.exe -file "C:\Program Files\BW_POWER_LAUNCHER\Bourbon Warfare Private Client Launcher GUI.ps1"

The path to the ps1 file will be different based on where you'd like to place it. You can also choose to change the icon to the little BW icon I've included in this repo. 

This has only been tested with the standard mods so far, I'm sure there's pleanty missing but it can be added in the XML
config file at a later date. Future Plans include adding an auto update feature where the config file will be distributed with mod updates and the power launcher will update it's own configuration, but that's future plans.

CHANGELOG

- BETA -
Changed some of the file structure. I'v been using this launcher for a while now on my own, it's time to allow others to check it out.
There is now no longer one configuration file. There is a main configuration file and supplimental configs. The main config has the standard BW modset defined and the information on what servers can be connected to with that standard modset. Each supplimental config defines at least one additional modset and what server(s) that can be connected to with that modset.

- ALPHA -
Added to the XML configuration DEV launch options that are active when the Mission Maker checkbox is selected
Noticed some issues with the MODSET for OPTRE that would cause mods to not be discovered properly, updated
Added a question mark to the GUI to pop up a little box showig the version being run
Added PresentationFramework assembly to allow pop up messages while running outside of the ISE

- INITIAL VERSION - 
First working copy for standard modset

