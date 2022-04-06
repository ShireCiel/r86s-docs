## Factory System

### Introduction

Factory system only have basic funciton of openwrt

### Interface (IN OPENWRT)
All Product:

|ETH0|ETH1|ETH2|
|  ----  | ----  | ----  |
|1G(WAN)|2.5G(LAN)|2.5G(LAN)|

10G NIC Product:

|SFP+|SFP+|
|  ----  | ----  |
|10G SFP+(unsigned)|10G SFP+(unsigned)|

### Login Information(SSH/WEB)
|Item|Info|
|  ----  | ----  |
|LAN Admin IP|192.168.86.1|
|LAN Admin Username|root|
|LAN Admin Password|password|
### Maintenance Command
Base on

https://github.com/R86S/R86S-QuickInstaller

|Item|Info|
|  ----  | ----  |
|r86s-clean-emmc.sh|Clean all data on emmc|
|r86s-write-this-to-emmc.sh|Write this system to emmc|