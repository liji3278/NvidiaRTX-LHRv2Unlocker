# Nvidia RTX LHR v2 Unlocker
The first fully automated BIOS modifier for RTX cards with LHR v2 lock. Using it is simple, intuitive and requires no advanced knowledge.

It enables the modification of previously read BIOS files (using HiveOs or other mining OS) and reading the BIOS from the graphics card installed in the system, then automatic backup, file modification and flash memory using the modified BIOS.

In addition, it also modifies files in RTX Axxxx series cards, increasing their performance. At the moment, no integration with more modern Nvidia graphics cards is planned.

<b>Planned release: 02/26/2022 this will be the Early Access version.</b>

# Disclaimer
I, the creator am not responsible for anything you do with this software. Using the software is free. I forbid the sale of BIOS files modified with this program. I do not agree to copying and reselling the modified version of the drivers.

# Requirements
Modifying the BIOS is not enough to fully hashrate your graphics card. You also need graphics drivers modified by me. They are downloaded and installed automatically in Windows when the program is installed. If you are using another OS such as HiveOs etc. then you need to install the drivers manually according to the instructions found in the DRIVER_INSTALATION.txt file in the application installation folder.

Due to the size, I placed the driver file on a private server.

# Supported RTX LHR models and their performance
- RTX 3060 LHR V2 - up to 49 MH/s
- RTX 3060 Ti LHR - up to 61 MH/s
- RTX 3070 LHR - up to 57 MH/s
- RTX 3070 Ti - up to 69 MH/s
- RTX 3080 LHR - up to 100 MH/s
- RTX 3080 Ti - up to 115 MH/s

# Supported RTX A series models and their performance
- RTX A2000 - up to 46 MH/s
- RTX A4000 - up to 67 MH/s
- RTX A4500 - not measured
- RTX A5000 - up to 110 MH/s

# Examples
Screenshots from Minerstat Dashboard - mining ETH on 2miners mining pool with LOLMINER v1.45. I tested all cards individually, on the same motherboard, plugged directly into the PCI-e x16 slot without risers.

Thanks to Markus, Tomas and Robert for helping me get graphics cards for testing, for believing it would work.

<b>RTX 30XX Series</b>

![alt text](https://github.com/BySergeyDev/NvidiaRTX-LHRv2Unlocker/blob/main/Images/Hashrate/RTX_3060_LHRV2.jpg?raw=true)
![alt text](https://github.com/BySergeyDev/NvidiaRTX-LHRv2Unlocker/blob/main/Images/Hashrate/RTX_3060_Ti_LHR.jpg?raw=true)
![alt text](https://github.com/BySergeyDev/NvidiaRTX-LHRv2Unlocker/blob/main/Images/Hashrate/RTX_3070_LHR.jpg?raw=true)
![alt text](https://github.com/BySergeyDev/NvidiaRTX-LHRv2Unlocker/blob/main/Images/Hashrate/RTX_3070_Ti.jpg?raw=true)
![alt text](https://github.com/BySergeyDev/NvidiaRTX-LHRv2Unlocker/blob/main/Images/Hashrate/RTX_3080_LHR.jpg?raw=true)
![alt text](https://github.com/BySergeyDev/NvidiaRTX-LHRv2Unlocker/blob/main/Images/Hashrate/RTX_3080_Ti.jpg?raw=true)

<b>RTX AXXXX Series</b>

![alt text](https://github.com/BySergeyDev/NvidiaRTX-LHRv2Unlocker/blob/main/Images/Hashrate/RTX_A2000.jpg?raw=true)
![alt text](https://github.com/BySergeyDev/NvidiaRTX-LHRv2Unlocker/blob/main/Images/Hashrate/RTX_A4000.jpg?raw=true)
![alt text](https://github.com/BySergeyDev/NvidiaRTX-LHRv2Unlocker/blob/main/Images/Hashrate/RTX_A5000.jpg?raw=true)

# Installation & how to use it
Download the RAR archive, run the installation package inside. After the installation is complete, run the program from the icon on the desktop.

<b>Modification of the card installed in the system</b>

1. Select "Read, modify and write BIOS from GPU"

![alt text](https://github.com/BySergeyDev/NvidiaRTX-LHRv2Unlocker/blob/main/Images/Screen/MOD1/1.jpg?raw=true)

2. Select the graphics card whose BIOS you want to modify from the list. Then select the first option from the list of tasks. You can also change the folder where the original BIOS file will be saved.

![alt text](https://github.com/BySergeyDev/NvidiaRTX-LHRv2Unlocker/blob/main/Images/Screen/MOD1/2.jpg?raw=true)

3. Wait for all stages to be completed.

![alt text](https://github.com/BySergeyDev/NvidiaRTX-LHRv2Unlocker/blob/main/Images/Screen/MOD1/3.jpg?raw=true)

4. That's it, you can start a miner.

![alt text](https://github.com/BySergeyDev/NvidiaRTX-LHRv2Unlocker/blob/main/Images/Screen/MOD1/4.jpg?raw=true)

<i>Remember! To remove the LHR lock, you need a BIOS modification and modified drivers. They are downloaded and installed automatically in Windows when the program is installed. If you are using another OS such as HiveOs etc. then you need to install the drivers manually according to the instructions found in the DRIVER_INSTALATION.txt file in the application installation folder.</i>


<b>BIOS modification only</b>

If your cards are mounted in mining rigs with Linux based OS like HiveOs, you can edit the BIOS from a file.

1. Select "Modifying the BIOS file"

![alt text](https://github.com/BySergeyDev/NvidiaRTX-LHRv2Unlocker/blob/main/Images/Screen/MOD1/1.jpg?raw=true)

2. Select the BIOS file you want to modify. You can also change the folder where the original BIOS file will be saved.

![alt text](https://github.com/BySergeyDev/NvidiaRTX-LHRv2Unlocker/blob/main/Images/Screen/MOD2/1.jpg?raw=true)

3. Wait for all stages to be completed.

![alt text](https://github.com/BySergeyDev/NvidiaRTX-LHRv2Unlocker/blob/main/Images/Screen/MOD2/2.jpg?raw=true)

4. That's it, you can start a miner.

![alt text](https://github.com/BySergeyDev/NvidiaRTX-LHRv2Unlocker/blob/main/Images/Screen/MOD1/4.jpg?raw=true)

<i>Remember! To remove the LHR lock, you need a BIOS modification and modified drivers. They are downloaded and installed automatically in Windows when the program is installed. If you are using another OS such as HiveOs etc. then you need to install the drivers manually according to the instructions found in the DRIVER_INSTALATION.txt file in the application installation folder.</i>

# FAQ

<b>What is the price?</b>

Using the software is free. I forbid the sale of BIOS files modified with this program. I do not agree to copying and reselling the modified version of the drivers.
If you feel I deserve it, you can donate me.

<b>Will it work with HiveOS?</b>

Yes, but you must modify the BIOS on a Windows computer. You can find the instructions above.

<b>Is it safe?</b>

Yes, you can always revert to the original drivers and BIOS.

<b>Isn't that SCAM?</b>

I provide it for free, the use of this program is the decision of the user. I don't see a SCAM opportunity here. If you decide that it doesn't work for you, you don't need to use it.

# Contact
Developer telegram: https://t.me/LHRUnlocker

Project channel: https://t.me/LHRUnlockerChannel
