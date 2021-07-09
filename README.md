# HP-250-G6-BigSur-OpenCore-EFI


<p align="center">
 OpenCore 0.7.1 EFI folder for macOS BigSur Hackintosh (i3 6006u variant) 250 G6 HP Laptop
<img src="https://i.imgur.com/C5WJG3W.png" alt="look">
</p>

<img src="https://raw.githubusercontent.com/snajdovski/HP-250-G6-OpenCore/71d79d0458238543caae6bf4cd674af452af5f1a/ss.png" alt="screenshot">

## Warning 
This EFI is not the most perfect one, so dont blame me if something doesn't work, opencore community hates sharing EFI folders but I did it because I know how hard can it be to start hackintoshing, so keep in mind this is not a perfect EFI and I have probably tons of mistakes into my config. 
Its stable on my laptop but that doesnt mean its stable on the same model even if you have the same CPU, the keyboard is probably not the same, you get the idea, so please keep in mind before opening issue and crying, thank you and you are welcome to suggestions if I have any mistake.


## DO NOT UPDATE:
 Realtek Ethernet kext (breaks Ethernet)
 VoodooPS2 kext (breaks hardware keys)
 AppleALC?
 
 
## What Works:
```
Battery Indicator
USB ports (mapped out but I still inject 3 kexts UsbMap,UsbInjectAll,Usb , needs to be refactored)
Video Accelariton (1536 Mb Vram)
Intel Wifi (not up to date)
Sleep
Audio (Apple ALC 13), Headphones, USB keybard
VGA
Brighness Keys (f2 and f3 without fn)
Volume Keys (f6 - f7)
Camera (Built-in)
EGPU disabled (AMD mobile not supported)
```
## What doesn't work:
```
HDMI Audio 
Sometimes Caddy HDD doesn't load after reboot.
You tell me
```

## TO DO:
```
More patching
```

## Thanks to:
```
*Apple for their proprietery OS
*OpenCore devs and OpenCore Guides
*itlwm for the Wifi Intel driver port from Linux
*me Stefan
*others too :P
```
