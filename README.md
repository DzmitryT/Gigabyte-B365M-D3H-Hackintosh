# Gigabyte B365M D3H based Hackintosh (macOS 11.2.2 Big Sur)


## Specification

|             |                                                                                        |
| :---------: | :------------------------------------------------------------------------------------: |
|     CPU     |                                     Intel i5-9600K                                     |
| Motherboard |                               Gigabyte B365M D3H                                       |
|   Graphics   |                                 Intel UHD Graphics 630                                 |
|   Memory    | Kingston Fury HyperX DDR4 1x32Gb                                             |
|   Storage   |                                     Samsung 840PRO 512Gb  SATA SSD                                   |
|    Audio    |                                     Realtek ALC892                                     |
|  Ethernet   |    Intel I219V2 |
|  Wireless   |    BCM94360CS2 |
|   Monitor   |                             2 x  AOC 2269WM (21.5")                            |

## Limitations

* Sleep/WakeUP issues
* HDMI issues
* 4k resolution is not supported
* VoodoPS2 kext is required for PS/2 input devices

## Bootloader requirements
* [OpenCore 0.6.9](https://github.com/acidanthera/OpenCorePkg/releases/tag/0.6.9)

## Display connection
DP and DVI are highly recommeded to use for single/dual monitor setup because of framebuffer id used for override (07009B3E). HDMI works normally only if display connected/switched on after macOS boots.

