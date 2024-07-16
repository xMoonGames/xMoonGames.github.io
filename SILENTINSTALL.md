# Silent Install
## Commands for silent installation of common programs

| Executable    | Command Parameters | Installer Technology | 
| - | - | - |
| C++ 2005 x86 x64 - [Download](https://www.techpowerup.com/download/visual-c-redistributable-runtime-package-all-in-one/) | /q | - |
| C++ 2008 x86 x64 - [Download](https://www.techpowerup.com/download/visual-c-redistributable-runtime-package-all-in-one/) | /qb | - |
| C++ 2010 or superior x86 x64 - [Download](https://www.techpowerup.com/download/visual-c-redistributable-runtime-package-all-in-one/) | /q /norestart | - |
| Google Chrome (offline version) [Download](https://www.google.com/intl/en/chrome/?standalone=1) | /silent | Inno Setup ([more](https://jrsoftware.org/isinfo.php)) |
| VSCode - [Download](https://code.visualstudio.com/) | /VERYSILENT /NORESTART /MERGETASKS="!runcode,desktopicon" /LOG="%WINDIR%\Temp\VSCode64-Install.log" | Inno Setup ([more](https://jrsoftware.org/isinfo.php))  |
| CoreTemp - [Download](https://www.alcpu.com/CoreTemp/) | /VERYSILENT /NORESTART /TASKS="desktopicon | Inno Setup ([more](https://jrsoftware.org/isinfo.php)) |
| Discord - [Download](https://discord.com/download) | -s | - |
