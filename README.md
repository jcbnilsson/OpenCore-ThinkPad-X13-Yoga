# OC-ThinkPad-X13-Yoga

OpenCore EFI for the ThinkPad X13 Yoga.
Supports macOS 14.4 Sonoma. Sequoia, older versions of Sonoma and
Ventura also run if AirportItlwm.kext is replaced.

## Note

Does not include OpenCore itself, you must copy OpenCore.efi into EFI/OC
and OpenCanopy.efi and OpenRuntime.efi into EFI/OC/Drivers before
using.

## Specs

- CPU: Intel Core i7 10510U
- GPU: Intel UHD 620 Graphics
- RAM: 16GB DDR4 2666MHz
- OS: macOS 15 Sonoma

## Works

More or less everything you'd expect to work in a usable Hackintosh.

## Doesn't work

- Microphone
- Headphone jack
  - It works but produces unpleasant sound (not sure why yet)
- Fingerprint reader
- Micro SD card reader

Please pull request if you can fix any of the above.
