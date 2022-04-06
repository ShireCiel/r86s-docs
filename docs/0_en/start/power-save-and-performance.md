## How to reduce power consumption

### Why a separate chapter

Duty to BIOS/JasperLake CPU defect. It will cause performance loss when reduce power consumption.

Perfermance of 2.5G NIC out R86S. 2.35Gbps->2.1Gbps performance drop.

Although we have reported to Intel, there is currently no solution. Only turned off the automatic CPU frequency adjustment. No power saving to guarantee performance. We will be closely monitoring changes to this bug in the future.

The factory BIOS has turned off the CPU automatic frequency adjustment by default. If the user wants lower power consumption and temperature. Some performance can be sacrificed. In exchange for better power consumption.


### How to turn on CPU automatic frequency adjustment

DEL Button to Enter BIOS -> Advanced -> Power & Performance -> CPU - Power Management Control -> C states -> Enabled

|Step number|Options|
|  ----  | ----  |
|1|DEL Button to Enter BIOS|
|2|Advanced|
|3|Power & Performance|
|4|CPU - Power Management Control|
|5|C states -> Enabled|

### Turning on ASPM can save more power
Whether enabling the ASPM function has an impact on performance has not been verified for a long time.


Turn on this feature. It can reduce the standby power consumption of up to 1W. without compromising performance

|Step number|Options|
|  ----  | ----  |
|1|DEL Button to Enter BIOS|
|2|Chipset|
|3|PCH-IO Configuration|
|4|PCI Express Configuration|
|5|DMI Link ASPM Control -> Auto|
|6|Every PCI Express Root Port (1/2/3/4)|
|7|ASPM -> Auto|
