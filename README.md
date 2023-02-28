# Host-Port-Scanner-for-Windows-Hosts-POWERSHELL-SCRIPT
This is a PowerShell script made for scanning hosts &amp; ports that are connected to a Windows host, the scripts ask you for the input of an IP that are discovered doing ipconfig /all and then starts the scan of hosts, and if a host is discovered then starts a port scan.

<h3>Before running the script you have to set the ExecutionPolicy of the target machine to unrestricted:</h3>

```
powershell.exe

Set-ExecutionPolicy -ExecutionPolicy Unrestricted -Scope CurrentUser
```
