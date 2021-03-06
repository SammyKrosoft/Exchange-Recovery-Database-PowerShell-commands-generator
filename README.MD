# PowerShell command line generator for Exchange (2010,2013, 2016) Recovery Database creation and make it use existing database and log files

## Description
This program is a Graphical User Interface that will help you generating Exchange Management Shell command lines to:

1. Create a Recovery Database using temporary path for the database and its corresponding LOG files set
2. Point that newly created Recovery Database to an existing database file and its corresponding LOG files set
3. Displays the newly created Recovery Database and its paths just modified
4. Mount the Recovery Database using the existing database file and corresponding LOG files set
4bis - Displaying the status and file paths of that database again (just to confirm)

![Fig.1](/Screenshots/ExchangeRecoveryDatabasePowerShellCmdGenerator.png)

## Launching it

Just type ```.\Launch-RecoveryDatabaseCreateGUI.ps1``` or "Run with Powershell" from Windows Explorer:

![Fig.2](/Screenshots/RunWithPowerShell.png)

Once you have the desired values for your Server name, your EDB file and LOG paths, etc..., Clicking on the [Copy to Clipboard] button will copy the command list to the Clipboard.

=> that way, you will be able to paste your commands in a PowerShell script, or in a NOTEPAD, or directly in an Exchange Management Shell for immediate execution !

![Fig.3](/Screenshots/CopiedToClipboard.png)


> Note: In order to see the "Run with Powershell" context menu on Windows Explorer, you need to set "Notepad" as the default "open with" program for .PS1 files -> see the "Miscellaneous" section below if you don't have your "Run with PowerShell" menu and if you with to get it back.

> Note2: if you reset the ".PS1" file association with NOTEPAD, you'll lose any previous association you made with ".PS1" files...

## Miscellaneous : How to retrieve your "Run with Powershell" menu from Windows Explorer

If you don't find your "Run with PowerShell" menu anymore when right-clicking a PS1 file, you just have to reset the default program to open .PS1 to be the basic Windows "Notepad". Here's how to do it :

1. Right-click to any .PS1 file, and click "Open with":

![Fig.3](/Screenshots/SetDefaultNotepadForPS1-1of2.png)

2. Choose Notepad, and ensure the ```[x] Always use this app to open .ps1 files``` is checked :

![Fig.4](/Screenshots/SetDefaultNotepadForPS1-2of2.png)

3. You're done ! From now on, and until you change the default editor for .ps1 files, you'll see the "Run with PowerShell" context menu when you right-click a .PS1 file:

![Fig.5](/Screenshots/SetDefaultNotepadForPS1-Conclusion.png)

# Links
My TechNet Blog article about it :
[Technet Link](https://blogs.technet.microsoft.com/samdrey/2018/06/05/powershell-command-line-generator-for-exchange-20102013-2016-recovery-database-creation-and-make-it-use-existing-database-and-log-files/ "Technet Blog Article about this tool")

And the TechNet Gallery link :
[Technet Gallery](https://gallery.technet.microsoft.com/Exchange-2010-2013-2016-bcd61dc7 "The latest release is also available on the TechNet Gallery")


