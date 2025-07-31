## Why This Repo?

Let’s be real: I’d rather not be stuck with Windows, but here we are! Tried my hand at Ubuntu and Kali, but ```everything comes with a cost```. I enjoy a little *fafo* now and then, but sometimes that costs me precious time. So for now, Windows it is! 

This repo is my backup plan for when Windows inevitably decides to throw a tantrum. Here’s a collection of my must-have software/tools, so I won’t have to scramble or rely on my memory in the future.

## Software List

Here's my lineup of lifesavers:

0. Chrome
1. VS Code (tailwind,hbs)
2. Dev C++
3. Telegram
4. Git
5. Android Studio
6. TreeSize
7. AOMEI
8. WPS Office
9. VLC Media Player
10. Hotspot Shield
11. WinRAR
12. Avast Antivirus
13. postman
14. PC MANAGER
15. Tyrrrz


## Commands set1
```powershell
Add-AppxPackage -RegisterByFamilyName -MainPackage Microsoft.DesktopAppInstaller_8wekyb3d8bbwe
```
or
```powershell
Invoke-WebRequest -Uri "https://aka.ms/getwinget" -OutFile "AppInstaller.msixbundle"
Add-AppxPackage "AppInstaller.msixbundle"
```
close 
```powershell
$env:PATH += ";$env:LOCALAPPDATA\Microsoft\WindowsApps"
```
```powershell
winget --version
```
```powershell
winget install --id OpenJS.NodeJS.LTS --exact
winget install --id Microsoft.OpenJDK.17 --exact
winget install --id Git.Git --exact
winget install --id Gyan.FFmpeg --exact
winget install --id Python.Python.3.12 --exact
winget install --id Microsoft.VisualStudioCode --exact
```
```powershell
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
```
close
```powershell
$env:Path = [System.Environment]::GetEnvironmentVariable("Path","Machine") + ";" + [System.Environment]::GetEnvironmentVariable("Path","User")
```
```powershell
node -v
npm -v
java --version
git --version
ffmpeg -version
python --version
```
```powershell
npm install -g npm@latest
```


## Commands set2
1. **Install Chocolatey** (the package manager we all need):
   ```powershell
   Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
2. **Install JDK and Node.js:**
    ```bash
    choco install -y nodejs-lts microsoft-openjdk17
3. **Update npm**
    ```javascript
    npm install -g npm
4. ```bash
     choco install ffmpeg

## in future I'd like to make it automatatic
```bash
@echo off
start https://www.google.com/search?q=ChromeDownload
start https://www.google.com/search?q=VSCode
start https://www.google.com/search?q=DevCppDownload
start https://www.google.com/search?q=TelegramDownload
start https://www.google.com/search?q=GitDownload
start https://www.google.com/search?q=AndroidStudio
start https://www.google.com/search?q=TreeSizeFree
start https://www.google.com/search?q=AOMEI
start https://www.google.com/search?q=WPSffice
start https://www.google.com/search?q=VLCMediaPlayer
start https://www.google.com/search?q=HotspotShield
start https://www.google.com/search?q=WinRAR
start https://www.google.com/search?q=AvastAntivirus
start https://www.google.com/search?q=Postman
start https://www.google.com/search?q=PCMANAGER
start https://www.google.com/search?q=Tyrrrz
```
```bash
@echo off
start https://www.google.com/search?q=stress+test+software
start https://www.google.com/search?q=MSI+Kombustor+download
start https://www.google.com/search?q=HeavyLoad+download
start https://www.google.com/search?q=Geekbench+download
start https://www.google.com/search?q=Cinebench+R23+download
start https://www.google.com/search?q=FurMark+download
start https://www.google.com/search?q=HWiNFO+download
start https://www.google.com/search?q=Unigine+Heaven+Benchmark+download
start https://www.google.com/search?q=OCCT+download
start https://www.google.com/search?q=Prime95+stress+test+download
start https://www.google.com/search?q=AIDA64+Extreme+download
start https://www.google.com/search?q=IntelBurnTest+download
start https://www.google.com/search?q=PassMark+PerformanceTest+download
```
