# Miniature Temperature Sensor - BH1900NUX Breakout Board
*KiCad project files for a breakout board using the Rohm Semiconductor BH1900NUX temperature sensor.*

## Overview
The breakout board simplifies integration of the **BH1900NUX temperature sensor** into your projects.  
The main goal of this PCB is to fit into stainless steel sleeve of around 5mm diameter.  

### Features
-  **A1 pin** Supported (solder jumper on the back)
- **A2 pin** Supported (solder jumper on the back)
- **A3 pin** Supported (solder jumper on the back)
- **ALERT pin** NOT supported (Pin is not exposed on the PCB)
- **Compact design** of less than 18mm² (0,028 square inch)

### JST SH connector pinout

| Pin # | Function |
|-------|----------|
| 1     | GND      |
| 2     | 3.3V     |
| 3     | SDA      |
| 4     | SCL      |

The pinout layout is widely used across different vendors of breakout boards with JST SH connector, allowing to use multiple different sensors on one bus more easily. Although the pin layout is (often) the same, each vendor uses their own brand names (e.g: Qwiic/STEMMA, μŠup, easyC)

> [!CAUTION]
> The design is not 5V compliant and 5V will destroy the sensor.  
> **Use 3.3V only.** 

---
# 3D Render images

![BH1900NUX Breakout Board Front](/docs/BH1900NUX-pcb-01-top.png)
*Figure: BH1900NUX sensor breakout board top view (Rohm Semiconductor)*

![BH1900NUX Breakout Board Front](/docs/BH1900NUX-pcb-02-top.png)
*Figure: BH1900NUX sensor breakout board top view (Rohm Semiconductor)*

![BH1900NUX Breakout Board Front](/docs/BH1900NUX-pcb-01-back.png)
*Figure: BH1900NUX sensor breakout board back view (Rohm Semiconductor)*

![BH1900NUX Breakout Board Front](/docs/BH1900NUX-pcb-01-bottom.png)
*Figure: BH1900NUX sensor breakout board bottom view (Rohm Semiconductor)*

# Manufacturing
## BOM
| ID / Ref.| Designator                           | Quantity                           | Description
|----------|--------------------------------------|------------------------------------|---------------------------------|
| R1,R4,R5 | R_0201_0603Metric                    | 3                                  | Resistor, 10k Ohm, SMD          |
| R3,R2    | R_0201_0603Metric                    | 2                                  | Resistor, 3.3k Ohm, SMD         |
| J1       | JST_SH_SM04B-SRSS-TB_1x04           | 1                                  | 01x04 JS SH 1.0mm Horizontal    |
| U1       | VSON008X2030_ROM                     | 1                                  | Rohm BH1900NUX-TR IC            |
| C1       | C_0201_0603Metric                    | 1                                  | Capacistor, Ceramic 100nF       |


# Project Supporter
![BH1900NUX Breakout Board Front](/docs/pcbway-logo.png)

PCBWay was so kind to help me to realize this project by sponsoring it.
Overall I am very statisfied with the quality of the PCB.  
If you plan to produce and assembly the board I can recommend using PCBWay.
The board looks high-quality, the corners and edges are cleanly cut, and there are no rough breaks, as is often the case with other boards.
There are no visible residues of flux, which is important not only for aesthetic reasons, but also because flux residues can be corrosive.
  
Moreover my service contact during the order process was very patient with me and helped me to fix two issues I had with my design.  
Have a look on you own below:

![BH1900NUX PCB](/docs/PCB-01.jpg)   
![BH1900NUX PCB](/docs/PCB-02.jpg)


# Additional resources
[Official BH1900NUX Product Page (ROHM Website)](https://www.rohm.com/products/sensors-mems/temperature-sensor-ics/bh1900nux-product)