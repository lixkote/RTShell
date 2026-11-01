# RTShell

## Port of Windows RT Update 3 to "normal" Windows 8.1 x64 bit

Features:
- Real port/reimplementation, not a crappy WPF recreation like DirectStart was
- All Windows RT Update 3 features(Start menu, rounded user profile pictures, auto-colorization)

For all changes see:
https://betawiki.net/wiki/Windows_8.1_build_9600.18009

## Requirements:
- Windows 8.1 x64 
- KB3138602, KB3184143, KB4054519 updates installed
- Twinui.dll version 6.3.9600.18819 and explorer.exe version 6.3.9600.18460

## Installation:
1. Download and unzip the file from releases. 
2. You need to obtain Windows 10 Beta 9785 iso and Windows RT Update 3 KB3033055 .msu file
   (Search on google for them)
3. Run ``rtshell-setup.exe`` and follow the wizard

### FAQ:

**Q: How does it differ from DirectStart?**
A: Its not a WPF-based recreation like DirectStart was, it is the real deal being made to run on 8.1, so less bugs than DirectStart, more features and behaves exactly like the Windows 10 Beta's Start Menu.

**Q: Does it support metro and live tiles now?**
A: YES. Its 1:1 exactly as functional as the real Windows RT Update 3/w10 beta's start menu.

## Credits:
- reprety
- allieistyping
- [amrsatrio](https://github.com/Amrsatrio)

 for the original windhawk start menu port code the start menu module was based upon, and for help with other things :)

- microsoft for windows RT update 3
