# windows11-autounattend.xml
WIndows 11 22H2 autounattend.xml
This is for ISO on Virutal machines

# WARNING  THIS WILL FORMAT AND INSTALL

# WARNING THIS WILL DESTORY ALL DATA ON DISK\MEMORY


## Notes
Will destory all data and auto install.  No clicks.

This will bypass all windows 11 checks.

## Settings

Hide Chat/Teams

Hide Widgets


## Installs

Winget,VSCode,Chrome,VLC


To Do:

Customize start menu remove tictok

Disable Microsoft Phone Link -did not work
reg add HKLM\SOFTWARE\Policies\Microsoft\Windows\System /v EnableMmx /t reg_dword /d 0x00000000

Trying this
Get-AppxPackage Microsoft.YourPhone -AllUsers | Remove-AppxPackage

more to add

Remove-Item $env:USERPROFILE\AppData\Local\Microsoft\WindowsApps\python*.exe





