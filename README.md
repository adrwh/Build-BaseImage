# Build-BaseImage
PowerShell tool to build a Windows Server 2012R2 VHDX

1. Setup a working directory eg C:\Build on your work horse.
1. CD into it `cd c:\build`
1. Get a copy of [Convert-WindowsImage.ps1](https://gallery.technet.microsoft.com/scriptcenter/Convert-WindowsImageps1-0fe23a8f) and save it into `c:\build`.
1. Open up your Windows Server 2012R2 ISO and copy out the \sources\install.wim file into `c:\build\install.wim`.
1. Save a copy of `Build-BaseImage.ps1` into `c:\build`.
