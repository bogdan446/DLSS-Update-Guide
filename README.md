# DLSS-Update-Guide

> [!NOTE] 
> RTX series graphics cards only

 


## A small guide on how to make DLSS4 used by default at driver level in all games where there is at least DLSS3/DLSS2.

### 1. Installing a new driver
- For everything to work it is recommended to update to the latest driver. Install from wherever you want. Somewhere it is recommended to do a clean install, in any case you can try without it.
> [!NOTE]
> At the time of editing this guide now the latest version is **572.16**

 


### 2. Download the latest dlls
- Go to the [TechPowerUp](https://www.techpowerup.com/download/drivers/) website and find the dlls you need.
  
 

![Example](https://i.imgur.com/yFhhheU.png)

 

- Download latest version of dll.

 

![Example](https://i.imgur.com/9cCFn3r.png)

 
- Unzip the dll to any location.

 


### 3. Create a script - [link to original](https://gist.github.com/emoose/11271bbb3b42fb3b1b0e1c83eef47c05)
- press the Raw button on the right side, select all contents with CTRL+A, copy with CTRL+C (don't download as file as PS won't allow execution)
- paste contents into notepad, save as UpdateDLSS.ps1
- find the saved script, right click -> "Run with PowerShell"
- when asked for DLL path, drag+drop an nvngx_dlss file into the window, and press enter
- if Run with PowerShell option doesn't appear, you can also run through command prompt or powershell: "powershell C:\Users\emoose\Downloads\UpdateDLSS.ps1"
