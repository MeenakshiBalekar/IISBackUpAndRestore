# IISBackUpAndRestore
How to take IIS backup and restore via Command prompt 

## To take backup of IIS 7 or Higher:

- Open cmd.exe as Administrator.
- Navigate to location %windir%\system32\inetsrv\.
- Execute following command to take an IIS back up :

| appcmd.exe add backup <backupname> | 



The backup will be stored at %windir%\system32\inetsrv\backup directory.

## To restore backup up IIS 7 or Higher:

- Open the folder %windir%\system32\inetsrv\backup directory.

- Execute following command to back up configuration:

| appcmd.exe restore backup <backupname> | 
