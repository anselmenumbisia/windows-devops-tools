# Windows Devops Tools

## Install Chocolatey

```powershell
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
```

## Install Packages

```powershell
iex ((New-Object System.Net.WebClient).DownloadString('https://raw.githubusercontent.com/fjudith/windows-devops-tools/main/chocolatey/install.ps1')
```
