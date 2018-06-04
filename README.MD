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

Just type ```.\Launch-RecoveryDatabaseCreateGUI.ps1``` or "Run with Powershell" from Windows:

![Fig.2](/Screenshots/RunWithPowerShell.png)

