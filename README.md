# winboet


<a href="url"><img src="https://github.com/hacker41d4n/winboet/blob/main/resources/winboetlogo.png" align="left" height="315" width="315" ></a>
## What is winboet?
Winboet is a chocolaty script to install all my windows applications i use on a daily base.
Winboet is made to for simplicity and easy to install.

## Prerequisite:

- Windows 10 or 11
- Administrator Rights
- Internet Access



## Getting Started:

Open PowerShell as Adminstrator.

Run the following commands

```
Get-ExecutionPolicy
```
If it returns "Restricted"
Then run
```
Set-ExecutionPolicy AllSigned
```
## Installing Chocolaty:
In a admin Powershell run
```
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
```
