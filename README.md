# Win10 gaming debloat script V1
An all in one script to optimize windows after a fresh install.

This project could not exist without the great work of Chris Titus (and others), go check his work: https://github.com/ChrisTitusTech/win10script/tree/master

NOTE: This tweak may cause Enterprise edition to stop receiving Windows updates.
Windows Update control panel will then show message "Your device is at risk because it's out of date and missing important security and quality updates. Let's get you back on track so Windows can run more securely. Select this button to get going".
In such case, enable telemetry, run Windows update and then disable telemetry again. See also https://github.com/Disassembler0/Win10-Initial-Setup-Script/issues/57



## What does it do?

The script will remove every microsoft invasive programs and telemetry, reinstalling the important ones, but debloated. After running the script you will also find dark mode enabled (you can change it if you want). 

It will also install Chocolatey, a package manager. Through this package manager it will install every programs that you need for gaming and for everyday use.

**Common programs:**
- Acrobat Reader 
- WhatsApp Messanger 
- Telegram
- Discord
- Java
- 7zip
- Notepad++
- Media Player Classic (VLC Alternative)
- Firefox
- Chrome
- qBittorrent
- Rufus

**Gaming programs:**

- EpicGames Launcher
- Steam
- Origin
- uPlay

**Hardware testing programs:**

- OCCT
- Cinebench
- AIDA64
- HWiNFO
- Afterburner
- CPU-Z


## How to use it

You just need to launch PowerShell as administrator and paste this:

    powershell -nop -c "iex(New-Object Net.WebClient).DownloadString('https://git.io/JJoho')"

Restart your PC, and you are done. 
