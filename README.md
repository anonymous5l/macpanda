# macpanda

## About

Lattepanda Alpha 864s CPU Model M3-8100y Hackintosh Big Sur bootloader fully function work just get and use it

* Airdrop not supported
* Wireless and bluetooth work 
* All USBPort fix
* CPU frequency 1.1Ghz-3.4Ghz
* SMBIOS infomation use OpenCore Configuare fix model. better select MacBookPro13,1 or you can generate on you own

### BIOS

* Disable CSM

### OS Version

* Big Sur (Not test on other system version)

### Bootloader

* OpenCore = 0.6.8

### Kext

* Lilu = 1.5.2
* AppleALC = 1.5.9 (WARNING: on install disable it)
* CPUFriend = 1.2.3
* IntelBluetoothFirmware = 1.1.2
* RealtekRTL8111 = 2.2.1
* VitrualSMC = 1.2.2
* WhateverGreen = 1.4.9
* AirportItlwm = 1.2.0

### After Install

Before we get in too deep, we'll want to first ready our system. More detail [Reference](https://dortania.github.io/OpenCore-Post-Install/universal/sleep.html#preparations)

```bash
sudo pmset autopoweroff 0
sudo pmset powernap 0
sudo pmset standby 0
sudo pmset proximitywake 0
sudo pmset tcpkeepalive 0
```

Reboot
