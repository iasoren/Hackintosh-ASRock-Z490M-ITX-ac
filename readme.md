ASRock Z490M-ITX/ac
===================
My Hardware:
CPU: Intel i5-10400 (with UHD630)
Motherboard: ASRock Z490m-ITX/ax
GPU: AMD RX 580 8GB
WiFi: BCM94352Z
SSD: Sabrent RocketQ NVMe

OpenCore 0.6.5

What Works - Software:
- Metal (fully)
- iServices (Facetime, iMessage, Apple Store, etc)
- Sleep/Wake (mostly)
- DRM (Broken in Big Sur)
- Bootpicker (verbose off)
- Handoff/Continuity/SideCar
- Big Sur (11.1)

What Works - Hardware:
- Ethernet (intel 1219v)
- Sound - Headphones (front), Internal Speaker (rear), Microphone (rear)  (via FakePCIID patch kext).
- WiFi and Bluetooth (BCM94352Z)
- CPU/GPU identified correctly in System Properties
- HWMonitor (CPU and HDD/SSD, GPU is WIP)
- Hardware Acceleration (with UHD630 set as frameless)

What doesn't yet
- Ethernet (2.5Gb)



This should be an almost working drop in for anyone with the same config. You'll need to update serials and that good stuff, but this should be most everything to get a system up and running near flawlessly.
