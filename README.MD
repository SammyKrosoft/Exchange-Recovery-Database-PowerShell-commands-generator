# PowerShell command line generator for Exchange (2010,2013, 2016) Recovery Database creation and make it use existing database and log files

## Description
This program is a Graphical User Interfice that will help you generating Exchange Management Shell command lines to:

1. Create a Recovery Database using temporary path for the database and its corresponding LOG files set
2. Point that newly created Recovery Database to an existing database file and its corresponding LOG files set
3. Displays the newly created Recovery Database and its paths just modified
4. Mount the Recovery Database using the existing database file and corresponding LOG files set
4bis - Displaying the status and file paths of that database again (just to confirm)

![Fig.1](/Screenshots/ExchangeRecoveryDatabasePowerShellCmdGenerator.png)

## Launching it

Just type ```.\Launch-RecoveryDatabaseCreateGUI.ps1``` or "Run with Powershell" from Windows Explorer:

![Fig.2](/Screenshots/RunWithPowerShell.png)

> Note: In order to see the "Run with Powershell" context menu on Windows Explorer, you need to set "Notepad" as the default "open with" program for .PS1 files

## Miscellaneous : How to retrieve your "Run with Powershell" menu from Windows Explorer

If you don't find your "Run with PowerShell" menu anymore when right-clicking a PS1 file, you just have to reset the default program to open .PS1 to be the basic Windows "Notepad". Here's how to do it :

1. Right-click to any .PS1 file, and click "Open with":

![Fig.3](/Screenshots/SetDefaultNotepadForPS1-1of2.png)

2. Choose Notepad, and ensure the ``` [x] Always use this app to open .ps1 files``` is checked

![Fig.4](/Screenshots/SetDefaultNotepadForPS1-2of2.png)
