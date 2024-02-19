# Dell-7572-Hackintosh
## Configuration SONOMA

| Specifications | Detail                                                  |
| ------------------- | ------------------------------------------- |
| Computer model      | Dell Inspiron 7572 15.6"   (MX150)         |
| Processor           | Intel Core i7-8550U Processor              |
| Memory              | 8GB/16GB Samsung DDR4 2400MHz              |
| Hard Disk           | LiteOn CA3-8D256-Q11/CA3-8D512-Q11 PCIe NVMe SSD    |
| Integrated Graphics | Intel UHD Graphics 620                     |
| Sound Card          | Realtek ALC256                             |
| Nertwork            | Realtek RTL8111
| Wireless Card       | Intel AX210/AX211/AX411 160Mhz Wi-Fi 6     |


Note: 
I use a customized Wifi card, if you use another card, open the config.plist with ProperTree, remove the kexts: `AirportItlwm.kext`, `BlueToolFixup.kext`, `IntelBluetoothFirmware.kext` and `IntelBTPatcher.kext`, from the kexts folder and generate a new OC Clean Snapshot with ProperTree.