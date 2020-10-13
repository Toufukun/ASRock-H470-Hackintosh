# ASRock H470 Hackintosh

An OC configuration for my Hackintosh desktop.

## FAQ

- Why Hackintosh?  
  To express my dissatisfaction with macOS 11.0 Big Sur and Apple Inc.

- Why Hackintosh at this time?  
  Because I'm lazy and I met lots of trouble. This plan was started after WWDC 2020. It has been proceeding for months.

## Hardware Specs

- CPU: Intel Core i5-10400
- Motherboard: ASRock H470
- RAM: Crucial 16GB DDR4 3200 ×2
- Graphics Card: Intel UHD Graphics 630
- Storage: WD Black SN750 NVMe SSD 500GB
- Wi-Fi & Bluetooth: BCM943602CS + PCI-E adapter

## Software Versions

- OpenCore 0.6.2
- macOS Catalina 10.15.6 (I really want to install an older version!)

## What is working

- iGPU acceleration
- HDMI (which cost me the most of time) (including HDMI audio), multi-monitor (DP + HDMI)
- Sound (see the next section)
- Wi-Fi and Bluetooth
- Sleep and wake-up
- All USB ports
- AirDrop, Continuity, etc.

## What is not working

I'm also seeking help for these problems.

- Automatic headphones/speakers switching
- DisplayPort audio (when use a DP monitor only, no HDMI monitor)

## What I don't know

- Facetime and iMessage
- Ethernet
- DRM

## What else you need

- OpenCore's `Resources`
- UEFI settings (WIP)
- Replace debug version .efi's and .kext's with release versions
