# BW_POWER_LAUNCHER
Bourbon Warfare powershell based Arma Launcher

Keep the .ps1 and .xml file in the same directory

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

This has only been tested with the standard mods so far, I'm sure there's pleanty missing but it can be added in the XML
config file at a later date.

CHANGELOG

- ALPHA -
Added to the XML configuration DEV launch options that are active when the Mission Maker checkbox is selected
Noticed some issues with the MODSET for OPTRE that would cause mods to not be discovered properly, updated
Added a question mark to the GUI to pop up a little box showig the version being run
Added PresentationFramework assembly to allow pop up messages while running outside of the ISE

- INITIAL VERSION - 
First working copy for standard modset

