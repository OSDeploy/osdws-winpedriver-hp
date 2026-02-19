AMD GPIO Controller Driver
===================================
Version 2.2.0.134



Description
-------------------------
This driver supports GPIO controller in AMD Ryzen based Mobile and Desktop chipsets.

### Operating System Supported:

* Microsoft Windows® 10 (64 bit)
* Microsoft Windows® 11 (64 bit)

### Known Issues:

* N\A

Revision History
-----------------
2.2.0.134 08/20/2024
* BSOD 0x133 fix
* Updated linker settings to include /CETCOMPAT.
* Updated build script.
* Updated Copyright Information.

2.2.0.132 12/11/2023
* Windows Next support added

2.2.0.131 11/03/2020
* Added check for the no of bank supported in new DID.

2.2.0.130 2020-03-11
* Added new Device ID AMDI0031

2.2.0.129 2020-03-07
Removed Extension inf Support

2.2.0.125 2020-01-13
Cz/Bristol/Stoney have 3 GPIO banks only, RV and later...

2.2.0.120 2019-09-19
Added support for pin 60-63 in queryinterrupt

2.2.0.118 2019-09-15
Enabled the print in READ/Write function

2.2.0.112 2018-09-24
* Updated the wakests flag for modernstandby support.

2.2.0.111 06/21/2018
* Add Zeppelin support

2.1.1.0051 11/02/2015
* Add Device Guard support

2.1.00.0049 03/30/2015
* Add 32-bit OS support

2.00.00.0046  02/24/2015
* Fixed EPR 408533 [QA][CZ] Unsigned driver warnings during installation in WinBlue

2.00.00.0041  09/30/2014
* Add more log for debugging

2.00.00.0032  05/7/2014
* Add support for Carrizo/KernCZ

2.00.00.0027  04/23/2014
* Add power management support to save/restore the register modified.

2.00.00.0023  12/24/2013
* Add emulate debouncing and query enabled interrupts.
* Add log through DbgPrintEx
* Remove Win8(32-bit & 64-bit), Win8.1 (32-bit) support

2.00.00.0016  10/24/2013
* Add more debounce setting for GEvent 0

2.00.00.0015  09/17/2013
* Fixed Emulate Active Both problem

2.00.00.0014  09/02/2013
* Code change according to SPEC update.

2.00.00.0013  08/12/2013
* Fixed that installation may fail.

2.00.00.0009 07/10/2013
* Initial release



Installation Instructions
-------------------------

**NOTE**:  As with all driver installations on Windows, you need to login as Administrator or have administrator rights for your domain login.

To install the driver, copy the installation files to a temporary directory, then use the "Device Manager" to perform an "Update Driver" operation as follows.  

1. Select "Control Panel" from Start Menu.
2. Select "Classic View" from the left pane.
3. Invoke Device Manager. 
4. There should be a device in the section named "Other Devices" with name "Unknown Device", with Hardware Id as *GPIO0010/AMD003x/AMDI003x(x is 0, 1, 2, etc.).*.
5. Right-click on "Unknown Device", and click on "Update Driver".
6. Select "Browse my computer for driver software".
7. Click "Browse" to choose the installation files and click "OK".
8. A box will appear: "The wizard has finished installing the software", click "Finish" to complete the installation.
 
Update Instructions
---------------------------

**NOTE**:  As with all driver installations on Windows, you need to login as Administrator or have administrator rights for your domain login.

To install the driver, copy the installation files to a temporary directory, then use the "Device Manager" to perform an "Update Driver" operation as follows.  

1. Select "Control Panel" from Start Menu.
2. Select "Classic View" from the left pane.
3. Invoke Device Manager. 
4. There should be a device section named "AMD GPIO Controller"
5. Right-click on AMD GPIO Controller, and click on "Update Driver".
6. Select "Browse my computer for driver software".
7. Click "Browse" to choose the installation files and click "OK".
8. A box will appear: "The wizard has finished installing the software", click "Finish" to complete the installation.




Copyright
---------------------------
(c) Copyright 2014~2024 Advanced Micro Devices, Inc.  All rights reserved.

LIMITATION OF LIABILITY:  THE MATERIALS ARE PROVIDED AS IS WITHOUT ANY EXPRESS OR IMPLIED WARRANTY OF ANY KIND INCLUDING WARRANTIES OF MERCHANTABILITY, NONINFRINGEMENT OF THIRD-PARTY INTELLECTUAL PROPERTY, OR FITNESS FOR ANY PARTICULAR PURPOSE. IN NO EVENT SHALL AMD OR ITS SUPPLIERS BE LIABLE FOR ANY DAMAGES WHATSOEVER (INCLUDING, WITHOUT LIMITATION, DAMAGES FOR LOSS OF PROFITS, BUSINESS INTERRUPTION, LOSS OF INFORMATION) ARISING OUT OF THE USE OF OR INABILITY TO USE THE MATERIALS, EVEN IF AMD HAS BEEN ADVISED OF THE POSSIBILITY OF SUCH DAMAGES. BECAUSE SOME JURISDICTIONS PROHIBIT THE EXCLUSION OR LIMITATION OF LIABILITY FOR
CONSEQUENTIAL OR INCIDENTAL DAMAGES, THE ABOVE LIMITATION MAY NOT APPLY TO YOU.

AMD does not assume any responsibility for any errors which may appear in the 
Materials nor any responsibility to support or update the Materials.  AMD
retains the right to make changes to its test specifications at any time, 
without notice.  NO SUPPORT OBLIGATION: AMD is not obligated to furnish, support, or make any further information, software, technical information, know-how, or 
show-how available to you. 

U.S. GOVERNMENT RESTRICTED RIGHTS: The Materials and documentation are provided with RESTRICTED RIGHTS.  Use, duplication or disclosure by the Government is subject to restrictions as set forth in FAR52.227014 and DFAR252.227-7013, et seq., or its successor.  Use of the Materials by the Government constitutes acknowledgment of AMD's proprietary rights in them.








