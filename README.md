## Electra 11.2 - 11.4.1 + Unc0ver 11.0 - 12.1.2 support
Delectra can be used to fix/re-jailbreak your device as reported [here](https://github.com/KirovAir/delectra/issues/12).
I'm not sure all leftover files are removed as of yet so I can not guarantee a clean state. I'll look into the current Electra release ASAP.

# delectra + Dec0ver = DeUnc0ver
An uninstaller script For [Electra](https://github.com/coolstar/electra/) iOS 11.0 - 11.4.1 jailbreak
Also for [Unc0ver](https://github.com/pwn20wndstuff/Undecimus/)

Please read everything in this readme before you do anything!

[Dowload link](https://codeload.github.com/MarwanAlshhei/DeUnc0ver/zip/master)
or
[Download raw file](https://raw.githubusercontent.com/MarwanAlshhei/DeUnc0ver/master/DeUnc0ver.sh)

## What is this?
It is a Bourne shell script.

Using this to remove all jailbreak files

!! DO NOT USE THIS IF YOU DON'T KNOW WHAT YOU ARE DOING !!
This is not recommended by Coolstar or Pwn20wnd.

## How to use?
1. Uninstall ALL __user__ installed packages and tweaks. You can use SemiRestore11-lite for this now!
2. Put DeUnc0ver.sh on your phone. I'd recommend putting it in / (root) so it will be removed by itself
3. Reboot your device and rejailbreak _without_ tweaks enabled. (This should make the process more stable)
4. SSH into your phone as __root__ and run DeUnc0ver.sh from this repo:
```
cd /
sh DeUnc0ver.sh
```
5. Wait until the device reboots and then reboot again.

## User reports
Soon

## Troubleshooting
#### My tweaks are not working on the betas anymore?
This was an issue when you used an older version of this script. This is fixed now.
1. SSH into your phone as __root__ and run:
```
mkdir /Library/Frameworks/
```
2. Reboot and re-jailbreak with a beta electra version and it should be fixed.

#### Thanks to KirovAir!!
