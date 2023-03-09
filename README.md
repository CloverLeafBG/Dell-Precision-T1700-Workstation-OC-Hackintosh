# Dell-Precision-T1700-Workstation-OC-Hackintosh


OpenCore based EFI for Dell Precision T1700 Workstation


![T1700](https://user-images.githubusercontent.com/93620854/224148087-bf267f69-d0ff-44f1-8c85-dc762a7a1744.png)




## Tested macOS Version

- macOS Catalina 10.15.7
- macOS BigSur 11.7.3


## System Configuration


- Motherboard: Dell's OEM C226 Chipset
- CPU: Intel Xeon E3-1226 V3 (no iGPU)
- Socket: LGA1150
- RAM: 2x8GB DDR3 @ 1600 Mhz
- GPU: NVIDIA Quadro 410
- SSD: 250 GB Crucial MX500
- Audio: ALC280


### BIOS Version

A28

 
### Bootloader

OpenCore 0.9.0


### SMBIOS

iMac14,4


## What's working

 - [x] Sleep, Restart, Shutdown
 
 - [x] CPU - Speedstep and power management

 - [x] dGPU - Fully working
 
 - [x] USB2.0 , USB3.0
 
 - [x] Audio - ALC280
 
 - [x] Ethernet
 


## What's not working

- So far everything is working great


## Not tested

- iGPU - my CPU doesn't have iGPU so I am not able to test it



## Additional Notes


- Don't forget to generate your own SMBIOS with https://github.com/corpnewt/GenSMBIOS. 
 
## ENJOY!
