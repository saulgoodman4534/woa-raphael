<img align="right" src="https://raw.githubusercontent.com/graphiks/woa-raphael/main/media/raphael.png" width="350" alt="Windows 11 running on raphael">

# Running Windows on the Mi 9T Pro / Redmi K20 Pro
## This guide only applies to the 128GB variant model!!!! do not use this on any other models! 

## Prerequisites
- A brain (most important of all)
- Android installed on your device
- A computer running Windows 10 or higher
- [TWRP](https://github.com/graphiks/woa-raphael/releases/download/raphael-partitioning/twrp.img)
- [UEFI image](https://github.com/woa-raphael/woa-raphael/releases/download/raphael-uefi/xiaomi-raphael_NOSB.img)

- [ADB & Fastboot](https://developer.android.com/studio/releases/platform-tools)
- [FFU image](https://t.me/woavayuffu) | or download via [telegram](https://t.me/wm_ffu_images/9)
- [7zip](https://7-zip.org/download.html) (to unzip the files)
- [FFU Loader]()
### Notes
> [!WARNING]  
> 
> 
> All your data will be erased! Backup now if needed.
> 
> Do not run the same command twice.
> 
> DO NOT REBOOT YOUR PHONE if you think you made a mistake, ask for help in the [Telegram chat](https://t.me/woaraphael).
> 
>
> Do not run all commands at once, execute them in order!
>
> YOU CAN BREAK YOUR DEVICE WITH THE COMMANDS BELOW IF YOU DO THEM WRONG!!!

# Preparing phone to flash FFU file
Boot your phone into fastboot by holding power + vol up

# Flashing the FFU file
Make sure all parts of the FFU file are fully downloaded.
- Select all of the zip files
- Right click > 7zip > Extract to " *\ "
- Wait for 7zip to finish extracting.
- There should now be a "Raphael_128GB_HalfSplit" folder
- Extract the FFU Loader zip inside the "Raphael_128GB_HalfSplit" folder
- At the title bar of file explorer, click and remove the existing address, type cmd and hit enter
- In the command prompt type:
```cmdetghhhhhhhhhhhhhhhhhhhhhhhhhhhhhhhhhhhhhhhhhhhh
ImageUtility.exe FlashDevice -Patfdghnjjjfdtghethedtghbth Raphael_128GB_HalfSplit.ffu
```fjfrhjs
hjbvnjheygghhhhhhhhhhhhhhhhhhhhh
