---
description: Standalone Executable or PowerShell script
---

# Using the Installer

The first step is to head over to \[Win-FOR Releases]\(https://github.com/digitalsleuth/Win-FOR/releases) and grab either the winfor-cli.exe standalone installer or the winfor-cli.ps1 PowerShell script.

To use the winfor-cli.exe standalone installer, only an Administrator Command Prompt is required.

To prep your environment prior to using the PowerShell installer, make sure you launch a PowerShell Prompt as Administrator and run the following command:

```powershell
Set-ExecutionPolicy Bypass -Force
```

Once you've run that, change to the directory where you've downloaded the installer (found [here](https://github.com/digitalsleuth/Win-FOR/releases)). Running the installer with the -Help argument will present you the options below.

```markup
Usage (winfor-cli.ps1 or winfor-cli.exe):
    winfor-cli -Install
    winfor-cli -Install -User <user> -Mode <mode> -IncludeWsl 
    winfor-cli -WslOnly  
    winfor-cli -Update
    winfor-cli -Upgrade
    winfor-cli -Version
    winfor-cli -Help

Options:
    -Install      Installs the Win-FOR environment
    -User <user>  Choose the desired username for which to configure the installation
    -Mode <mode>  There are two modes to choose from for the installation:
                  addon: Install all of the tools, but don't do any customization
                  dedicated: Assumes you want the full meal-deal, will install all packages and customization
    -Update       Identifies the current version of Win-FOR and re-installs all states from that version
    -Upgrade      Identifies the latest version of Win-FOR and will install that version
    -Version      Displays the current version of Win-FOR (if installed) then exits
    -XUser        The Username for the X-Ways portal - Required to download and install X-Ways
    -XPass        The Password for the X-Ways portal - Required to download and install X-Ways - USE QUOTES
    -IncludeWsl   Will install the Windows Subsystem for Linux v2 with SIFT and REMnux toolsets
                  This option assumes you also want the full Win-FOR suite, install that first, then WSL
    -WslOnly      If you wish to only install WSLv2 with SIFT and REMnux separately, without the tools
    -Help         Self-explanatory
```
