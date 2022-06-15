# 2dsxlusbc

This is an adapter PCB designed to put an USB Type C port as the charging port of a Nintendo 2ds XL.  

![Finished Mod](https://github.com/Refuhr/2dsxlusbc/blob/main/images/port-in-shell.jpg)

# Features

This PCB allows your 2ds XL to be charged via USB Type C with an USB A to USB C cable. Additionally, if you use two 5.1k 0402 resistors it enables USB Type C Host charging, which means that your 2ds should now be compatible with any USB PD Charger.

# What you'll need

-the PCB, available from [oshpark](https://oshpark.com/shared_projects/KSdF5ITT) ($0.60 shipped in the US, about 0.70€ shipped in the EU), [gerbers](https://github.com/Refuhr/2dsxlusbc/blob/main/Gerber_PCB_2dsxlusbc_V4.zip)  
-the USB Type C port: [Ebay](https://www.ebay.com/itm/153460023680) or [Aliexpress](https://www.aliexpress.com/item/4000857925361.html) 10X $2-3 (search for: usb type c 6 pin)  
-optional (required for USB C Host charging): two 5.1K 0402 resistors (available at [local electronics store in Germany](https://www.conrad.de/de/p/tru-components-tc-0402wgf5101tce203-dickschicht-widerstand-5-1-k-smd-0402-0-063-w-1-100-ppm-c-1-st-tape-cut-1585197.html) 10X 0.20€ or Ebay/Aliexpress/Digikey/etc.)  
-soldering iron with solder  
-heat gun for removing the original charging port (can be done without an heat gun, I personally wouldn't recommend it)  
-desoldering braid/desoldering pump  
-flux  

# Installation

Instructions for assembly/installation can be found in [INSTALLATION.md](https://github.com/Refuhr/2dsxlusbc/blob/main/INSTALLATION.md)  

# PCB

By measuring the pads of the old charging port, I was able to design a [custom footprint](https://easyeda.com/component/d013406ddfa94d40b684a1f854966128) for the charging port of the 2ds xl in easyeda. The PCB with the USB Type C port is held down with solder at the original pads. It seems to be quite strong, but superglue wouldn't hurt to help with the rigidity of the port.  

Feel free to make changes to the design, design files (easyeda) can be found [here](https://github.com/Refuhr/2dsxlusbc/tree/main/design%20files).

Top layer:
![Top layer](https://github.com/Refuhr/2dsxlusbc/blob/main/images/top.png)
Bottom layer:
![Bottom layer](https://github.com/Refuhr/2dsxlusbc/blob/main/images/bottom.png)

# Thanks

Thank you to [rorosaurus](https://github.com/rorosaurus/3ds-xl-usb-c) and [makho](https://github.com/makhowastaken/3DS_C) for the inspiration of this PCB!
