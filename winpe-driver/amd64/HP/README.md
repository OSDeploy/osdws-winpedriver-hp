> [!NOTE]
> Vendor Published Drivers

---

# HP

---

| Released | Build | Version | Download |
|--|--|--|--|
| 2024.03.11 | sp151478 | 2.70 | https://ftp.ext.hp.com/pub/softpaq/sp151001-151500/sp151478.exe |

---

## Changelog
```
2025.01.05 - David Segura updated Drivers to the latest version.
```

---

## Notes
Drivers are imported into MDT (Microsoft Deployment Toolkit) to normalize the Driver folder structure and to validate the Driver content before adding to this Repository.

```
Download the latest DriverPack.
Execute the DriverPack to expand to C:\SWSetup\SPxxxxxx.
Copy any *.cva files from C:\SWSetup\SPxxxxxx to .\HP\*.cva.
Import Drivers into an empty MDT Deployment Share.
Save the MDT Import Drivers output as .\HP\ImportDrivers.txt.
Copy the MDT Drivers in "<Deployment Share>\Out-of-Box Drivers" to .\HP\MDT\*.*.
Copy "<Deployment Share>\Control\Drivers.xml" as .\HP\Drivers.xml.
In MDT Out-of-Box Drivers, run the Export List. Save the file as .\HP\ExportList.csv.
```
---

## Links
- HP Client Windows PE Driver Packs
  - https://ftp.ext.hp.com/pub/caps-softpaq/cmit/HP_WinPE_DriverPack.html

---

## HP Description:
This package contains the drivers necessary for appropriate Microsoft Windows operating system deployment for supported HP notebook and desktop models.
This package provides the drivers for the integrated and select add-in devices in an INF format.
This format is compatible with bare-metal Operating System deployment tools that require INF based drivers.

## HP Notes:
HP Business PCs - HP Client Windows PE 10 x64 Driver Packs are not supported in full Windows operating systems.
HP Client Windows PE 10 x64 Driver Packs are compatible only with the Windows PE operating system.
HP does not support using HP Client Windows PE 10 x64 Driver Packs when building a full Windows operating system image.
If you are running a different Windows operating system, the Windows PE drivers are not compatible, and might not function.
Select a link below to download an HP WinPE driver pack or its release notes.

## HP Installation Instructions:
Download the file by clicking Download or Obtain Software button and saving the file to a folder on your hard drive (make a note of the folder where the downloaded file is saved).
Double-click the downloaded file and follow the on-screen instructions to extract the contents of the SoftPaq.
Import the contents of the file into a content management tool that supports operating system deployment.

## Installation Notes:
TITLE:  HP Client WinPE 10.0 x64 Driver Pack
VERSION: 2.70
DESCRIPTION: 
This package contains the drivers necessary for Microsoft Windows PE 10 operating system deployment for supported HP notebook and desktop models. This package provides the drivers for the integrated and select add-in devices in an INF format. This format is compatible with bare-metal Operating System deployment tools that require INF based drivers.

    PURPOSE: Routine
    SoftPaq NUMBER: sp151478
    EFFECTIVE DATE:  02/21/2024
    CATEGORY:  Manageability - Driver Pack
    SSM SUPPORTED:  No
    DEVICES SUPPORTED: N/A
    PREREQUISITES: - If the system is running in the Microsoft SCCM environment, verify that all cumulative updates are installed. Issues may be encountered when the environment is not up to date.
    LANGUAGE(S): 
    English (US)
 

ENHANCEMENTS:
Includes following 64 bit drivers:

    00 - Intel Serial IO 30.100.1914.3
    00 - Intel Serial IO 30.100.2020.7
    00 - Intel Serial IO 30.100.2129.1
    00 - Intel Serial IO 30.100.2133.4
    00 - Intel Serial IO 30.100.2148.1
    05 - AMD_Chipset_4.04.12.1948
    05 - AMD_Chipset_5.08.14.509
    06 - AMD_USB4_1.0.0.21
    20 - RSTe_f6_iaStorS_win8_win10_64 4.5.0.1234
    21 - RST 14.8.2.1044
    22 - RSTe_f6_iaStorA_win8_win10_64 4.7.0.1068
    24 - RSTe_5.4.9.1005_F6_Win10_64
    25 - RST 17.9.0.1007
    27 - RST 18.36.2.1023
    28 - RSTVMD 19.5.0.1037
    30 - SmartPqi 63.32.0.64
    41 - BayHubTech 1.3.101.1033
    80 - AMD_RAID 7.2.0.00057
    85 - AMD_RAID_9.3.0.00206
    All Docks - Ethernet_Driver, version 2.0.0.1,A,1 
    Allied Telesis 1GbE LC Fiber Driver, version 214.0.0.1,E,1 
    Allied Telesis 1GbE LC Fiber Driver, version 3.8.4.0,H,1 
    Aquantia NIC Driver - Z2 G4 WKS, version 2.2.1.0,G,1  
    Broadcom NIC Drivers, version 214.0.0.0,A,1 
    Intel I219LM/V Gigabit Ethernet Driver, version 12.18.9.7,A,11 
    Intel NIC Driver, version 12.19.0.16,P,2 
    Intel NIC Driver, version 12.19.1.37,P,3 
    Intel NIC Driver, version 12.19.2.50,P,6
    Intel Network Card Drivers, version R26.4,C,1 
    Intel Network Card Drivers, version R27.2,A,1 
    Intel Network Connections Drivers, version R23.5_517476,A,2 
    Realtek Ethernet RTL8111EPH-CG Controller Drivers, version 10.23.1003.2017,A,1 
    Realtek Ethernet Driver, version 1166.14.613.2023 
    Realtek Local Area Network (LAN) Driver, version 10.31.828.2018,A,6 

HP Manageability website
http://www.hp.com/go/clientmanagement

HOW TO USE:
1. Download the file by clicking the Download or Obtain Software button and saving the file to a folder on your hard drive (make a note of the folder where the downloaded file is saved).
2. Double-click the downloaded file and follow the on-screen instructions to extract the contents of the file.
3. Import the contents of the file into a content management tool that supports operating system deployment.
NOTE: 
-It may be necessary to restart the system for some drivers to function properly.

Copyright (c) 2024 HP Development Company, L.P.
---