---
description: A Windows Forensics Toolkit and Environment Builder
---

# WIN-FOR

![](.gitbook/assets/FingerPrint.png)

## About WIN-FOR 

![Latest Win-FOR Release](https://img.shields.io/github/v/release/digitalsleuth/win-for?style=flat&label=Latest%20Win-FOR%20Release)

The design behind this is to use a barebones Windows 10 VM or a Windows machine (preferably 1909 and higher to support WSLv2).
Once configured, and activated (to support customization features), then you can use one of the installers to
install all of the packages.

The installer is a graphical interface to click and choose which items you want, and to enter the settings you need

Check out the [Releases](https://github.com/digitalsleuth/WIN-FOR/releases) section for the most up-to-date installers.

## Win-FOR Customizer

**FIRST OFF - Requires .NET 6.0 Desktop Runtime**
**If you do not have it, you will be prompted to install at execution**

Why a GUI? Who doesn't like a good GUI!?
Not everyone enjoys Windows command line or PowerShell, especially when just starting out in Digital Forensics.
This makes it much easier to get your environment set up without having to worry about CMD or PS!

The customizer tool gives you the following features:

- Point and click to choose which tools you want installed in your distro (instead of just choosing them all)
- Checkboxes to choose if you want the WSLv2 with SIFT and REMnux installed during the process, or click `WSL Only` to install it at a later date
- Save your current selections in a custom SaltStack State file for your own purposes or record
- Identify the current version of the Win-FOR environment with a single click
- Check for updates to the Customizer
- Graphically enter any settings you need!

![screenshot-v8 4 0](https://github.com/digitalsleuth/WIN-FOR/raw/main/images/screenshot-v8.4.0.png)

![screenshot-options-v8 4 0](https://github.com/digitalsleuth/WIN-FOR/raw/main/images/screenshot-options-v8.4.0.png)


## PowerShell or CLI

The PowerShell script and standalone CLI executable have been deprecated in favour of the Win-FOR Customizer.
However, if there is need for a command-line version of the Customizer, it can be done. Until such time, the Customizer is your best choice!

## Issues

All issues should be raised [here](https://github.com/digitalsleuth/WIN-FOR/Issues)

The design behind this is to use a barebones Windows 10 VM (preferably 1909 and higher to support WSLv2). Once configured, and activated (to support customization features), then you can use the install.ps1 file to install all of the packages.

The install requires either that the `Set-ExecutionPolicy` feature be set to allow the PowerShell script to run at least twice depending on your choices, or simply to run the winfor-cli.exe from command line.

Additionally, a new tool is coming soon (Win-FOR Customizer) which is a GUI interface to allow you to choose the tool(s) you want in your environment.  

This is best left to you to decide what is acceptable in your organization.

For more details, check out the [Using the Installer](installation/using-the-installer.md) section.

For a listing of tools, check out the sub-sections from the menu on the left.

