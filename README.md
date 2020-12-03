# HP-250-G6-BigSur-OpenCore-EFI


<p align="center">
 OpenCore 0.6.3 EFI folder for macOS BigSur Hackintosh (i3 6006u variant) 250 G6 HP Laptop
<img src="https://i.imgur.com/C5WJG3W.png" alt="look">
</p>

## What Works:
```
Proper SMBIOS
Audio
Touchpad(Scrolling and Swiping max 2 fingers due to hardware limitation)/Keyboard
Brightness
Battery Indicator
USB ports including the SD Card Reader
Video Accelariton (1536 Mb Vram)
VGA Output Port (TESTED)
HDMI (Sound broken) (TESTED)

```
## What doesn't work:
```
Ethernet
Sleep (Machine goes to sleep but when woken up it has just backlit on no output or input)
Intel Wifi (Search on github for a alt kext for intel wifi cards https://github.com/OpenIntelWireless/itlwm/releases)

```

## TO DO:
```
*fix Sleep
*Remove DSDT.aml
lots more 
```

## Thanks to:
```
*Apple for their proprietery OS
*OpenCore devs and OpenCore Guides
*itlwm for the Wifi Intel driver port from Linux
*me Stefan
*@aidasaidas75 for fixing some issues
*others too :P
```
