---
description: A Windows Forensics Toolkit and Environment Builder
---

# WIN-FOR

![](.gitbook/assets/FingerPrint.png)

## About WIN-FOR

The design behind this is to use a barebones Windows 10 VM (preferably 1909 and higher to support WSLv2). Once configured, and activated (to support customization features), then you can use the install.ps1 file to install all of the packages.

The install requires either that the `Set-ExecutionPolicy` feature be set to allow the PowerShell script to run at least twice depending on your choices, or simply to run the winfor-cli.exe from command line.

Additionally, a new tool is coming soon (Win-FOR Customizer) which is a GUI interface to allow you to choose the tool(s) you want in your environment.  

This is best left to you to decide what is acceptable in your organization.

For more details, check out the [Using the Installer](installation/using-the-installer.md) section.

For a listing of tools, check out the sub-sections from the menu on the left.

