# Dell G3 3579

## High-Sierra 10.13.6

- i5-8300U
- Intel UHD 630
- Nvidia GTX1050Ti (Not Working)
- Intel Wireless AC9462 (Not Working)
- ALC236
- BC501 NVMe SK hynix 128GB


## Doesn't Work / Issues

- Sleep
- GTX1050Ti
- HDMI output (it's directly attached - internally - to 1050Ti)
- Wifi and BT
- Card reader (haven't tested, though)
- Fingerprint sensor
- 1 out of 7 reboots, sound doesn't work.

## Notes

- Headphone jack works but there is _very slight_ background hiss (i don't mind it)
- Nvidia _should be_ disabled by boot flag and SSDT (can't detect it with SystemProfiler or System Information)
- TouchID.kext disables fingerprint sensor and prevents lag on login/sudo prompt
- Touchpad works with gestures (2/3 finger swipes)
- Brightness control works by using Fn+S (-) and Fn+B (+); You can remap these (https://github.com/RehabMan/OS-X-Voodoo-PS2-Controller/wiki/How-to-Use-Custom-Keyboard-Mapping)
- Battery indicator is off by ~3-4%; use HWMonitor for accurate reading
