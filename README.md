# OpenBook-e-book-reader

![image](https://github.com/user-attachments/assets/9bbbaf0a-def0-4646-a5ea-911b73e33ba6)

# Project Structure
```
OpenBook E-Reader
├── Hardware
│ ├── E-Reader.sch
│ └── E-Reader.brd
├── Manufacturing
│ ├── gerbers.zip
│ ├── bom.csv
│ └── pap.csv
├── Mechanical
│ ├── E-Reader.zip # STEP model archive
│ ├── E-Reader.f3z
│ └── OpenBook Enclosure.f3d # Enclosure model
├── Images
│ ├── 3d.png
│ ├── Schematic.png
│ ├── Board.png
│ └── Board_in_box.png
├── LICENSE # Apache 2.0
└── README.md
```

# Bill of Materials

## Component List

| Name                          | Description                                                                                           | Value        | Quantity | Link to buy| Datasheet |
|-------------------------------|----------------------------------------------------------------------------|--------------|----------|------|------------------|
| 744043680                     | IND_4828-WE-TPC_WRE                                              | 68uH         | 1        | https://mou.sr/42yVhMe     | https://www.we-online.com/components/products/datasheet/744043680.pdf |
| 112A-TAAR-RO3_ATTEND          | Micro SD Card Socket, Push-Push Type, Top Mount, SMT, H = 1.83mm | 10u          | 1        | https://www.attend.com.tw/en/product.php?act=view&id=253# | https://www.attend.com.tw/data/download/file/112A-TAAR-R03_Spec.pdf |
| BD5229G-TR                    | Voltage Detector with Adjustable Delay Time (CMOS)               |              | 1        | https://mou.sr/421TSO9     | https://fscdn.rohm.com/en/products/databook/datasheet/ic/power/voltage_detector/bd52xxg-e.pdf |
| BUTTON_CUSYOMV1               | Momentary Switch (Pushbutton) – SPST – SMD, 4.6 x 2.8mm          |              | 3        | https://mou.sr/41Yc6zX     | https://4donline.ihs.com/images/VipMasterIC/IC/PANA/PANA-S-A0000771493/PANA-S-A0000771493-1.pdf? hkey=CECEF36DEECDED6468708AAF2E19C0C6 |
| CPH3225A                      | Capacitor 0.011F 3.3V 1210 Flat                                  |              | 1        | https://mou.sr/42aoXOc     | https://ro.mouser.com/datasheet/2/360/Seiko_Instruments_MicroBattery_E_20230330_2024Jan_-3561061.pdf |
| DS3231SN#                     | Real Time Clock Serial 16-Pin SOIC W T/R                         |              | 1        | https://mou.sr/4ll9PXb     | https://ro.mouser.com/datasheet/2/609/DS3231-3421123.pdf |
| EAGLE-LTSPICE_CC0402         | Capacitor                                                         | 100nF        | 8        | https://mou.sr/42aprE0     | https://www.mouser.com/catalog/specsheets/Kemet_2-4-2024_KEM_F3140_R41D_Y2_300%20(draft3)%20(3).pdf?_gl=1*1rt35nv*_gcl_au*OTQ1MTI5Nzc4LjE3NDM5NjUwNTA.*_ga*MTkwMDk4MTgwMy4xNzQzOTY1MDUx*_ga_15W4STQT4T*MTc0NDc3OTk1NS4zLjEuMTc0NDc4MTkwNi4xOS4wLjA. |
| EAGLE-LTSPICE_CC0402         | Capacitor                                                         | 4.7uF        | 5        | https://mou.sr/44lcHNw     | https://ro.mouser.com/datasheet/2/40/AutoMLCCKAM-3216307.pdf |
| EAGLE-LTSPICE_CC0402         | Capacitor                                                         | 10uF         | 1        | https://mou.sr/3G8LNhS     | https://ro.mouser.com/datasheet/2/40/cx5r_KGM-3223198.pdf |
| EAGLE-LTSPICE_CC0402         | Capacitor                                                         | 1uF/50V      | 9        | https://mou.sr/3YwHHGK     | https://ro.mouser.com/datasheet/2/447/upy_gphc_x5r_4v_to_50v-3461255.pdf |
| EAGLE-LTSPICE_CC0402         | Capacitor                                                         | 0.1uF/50V    | 1        | https://mou.sr/3RC3wkl     | https://product.tdk.com/system/files/dam/doc/product/capacitor/ceramic/mlcc/catalog/mlcc_commercial_midvoltage_en.pdf |
| EAGLE-LTSPICE_CC0402         | Capacitor                                                         | 1nF          | 1        | https://mou.sr/3YwHHGK     | https://ro.mouser.com/datasheet/2/447/upy_gphc_x5r_4v_to_50v-3461255.pdf |
| ESP32_WROVER_BME680_BME680   | Integrated Environmental Unit (BME680)                            |              | 1        | https://mou.sr/42kgEzJ     | https://ro.mouser.com/datasheet/2/783/BST_BME680_DS001-1509608.pdf |
| ESP32_WROVER_AVX---          | Schotty Barrier Rectifier Diode                                   |              | 1        |                            |
| ESP32_WROVER_RR0402          | Resistor                                                          | 10k          | 15       | https://mou.sr/4i5Vvim     | https://www.vishay.com/docs/53046/pfrr.pdf |
| ESP32_WROVER_RR0402          | Resistor                                                          | 2.2          | 1        | https://mou.sr/4i9Xsun     | https://www.vishay.com/docs/53046/pfrr.pdf |
| ESP32_WROVER_RR0402          | Resistor                                                          | 0.47         | 1        | https://mou.sr/4i9XAKn     | https://www.vishay.com/docs/53046/pfrr.pdf |
| ESP32_WROVER_RR0402          | Resistor                                                          | 200          | 1        | https://mou.sr/4i9XAKn     | https://www.vishay.com/docs/53046/pfrr.pdf |
| ESP32_WROVER_RR0402          | Resistor                                                          | 2k           | 1        | https://mou.sr/4jeq8Do     | https://www.vishay.com/docs/53046/pfrr.pdf |
| ESP32_WROVER_RR0402          | Resistor                                                          | 15           | 1        | https://mou.sr/4i5Vvim     | https://www.vishay.com/docs/53046/pfrr.pdf |
| ESP32_WROVER_RR0402          | Resistor                                                          | 5k1          | 2        | https://mou.sr/4jeq8Do     | https://www.vishay.com/docs/53046/pfrr.pdf |
| ESP32_WROVER_RR0402          | Resistor                                                          | 100k         | 1        | https://mou.sr/4jeq8Do     | https://www.vishay.com/docs/53046/pfrr.pdf |
| ESP32_WROVER_SPARKFUN-       | P-channel MOSFETs                                                 |              | 2        | https://mou.sr/42jyNxv     | https://ro.mouser.com/datasheet/2/268/MCP73831_Family_Data_Sheet_DS20001984H-3441711.pdf |
| ESP32_WROVER_SPARKFUN-IC-    | MCP73831T Li-Ion, Li-Pol Controller                               |              | 1        | https://mou.sr/42jyNxv     | https://ro.mouser.com/datasheet/2/268/MCP73831_Family_Data_Sheet_DS20001984H-3441711.pdf |
| ESP32C6_VARISTORCN1812       | Varistor                                                          |              | 1        | https://mou.sr/3RnbVYV     | https://www.tdk-electronics.tdk.com/inf/75/db/CTVS_14/Surge_protection_series.pdf |
| ESP32-C6-WROOM-1-N8          |                                                                   |              | 1        | https://mou.sr/42swLfH     | https://ro.mouser.com/datasheet/2/891/Espressif_ESP32_C6_WROOM_1__Datasheet_V0_1_PRELIMI-3239987.pdf |
| FH34SRJ-24S-0.5SH_99_        | 24-pos FFC/FPC Connector, Right Angle                             |              | 1        |  https://mou.sr/43Cr53R    | https://ro.mouser.com/datasheet/2/185/FH34SRJ_24S_0_5SH_99__CL0580_1255_6_99_2DDrawing_0-1615044.pdf |
| MAX17048G+T10                | Fuel Gauge                                                        |              | 1        | https://mou.sr/3FWR5wY     | https://ro.mouser.com/datasheet/2/609/MAX17048_MAX17049-3469099.pdf |
| MBR0530                       | Diode, Schottky, 0.5A, 30V, SOD-123                              |              | 2        | https://mou.sr/4jmza1b     | https://www.onsemi.com/download/data-sheet/pdf/mbr0530t1-d.pdf |
| PGB1010603MR                  | ESD Suppressor                                                   |              | 6        | https://mou.sr/3Yg9sDe     | https://www.littelfuse.com/assetdocs/pulseguard-esd-suppressors-pgb1-datasheet?assetguid=8a337998-d54d-466b-be4e-dc5bcd1f9321 |
| QWIIC_CONNECTORJS-1MM        | I²C Standard Qwiic Connector                                      |              | 1        | https://www.sparkfun.com/qwiic-jst-connector-smd-4-pin-horizontal.html | https://cdn.sparkfun.com/assets/parts/1/2/2/8/9/Qwiic_Connector_Datasheet.pdf |
| RCL_CPOL-EUCT3528            | Polarized Capacitor (Tantalum)                                    | 100uF TANT   | 1        | https://mou.sr/42webCl     | https://www.mouser.com/catalog/specsheets/Panasonic_08082018_Capacitor%20Radial%20Leaded%20Lytic%20(EEU-FS)%20020118.pdf?_gl=1*1qqq4o9*_gcl_au*OTQ1MTI5Nzc4LjE3NDM5NjUwNTA.*_ga*MTkwMDk4MTgwMy4xNzQzOTY1MDUx*_ga_15W4STQT4T*MTc0NDc3OTk1NS4zLjEuMTc0NDc4MjQ0MS4zOC4wLjA. |
| SAMACSYS_USB4110-GF-A        | USB 2.0 Type-C Connector, Right Angle SMT                         |              | 1        | https://www.digikey.ro/en/products/detail/gct/USB4110-GF-A/10384547     | https://gct.co/files/specs/usb4110-spec.pdf?v=6b2a6292-70a5-4bd5-a7e5-0f3fe03e015f |
| SI1308EDL-T1-GE3              | MOSFET N-Ch 30V 1.5A Vishay TrenchFET                            |              | 1        | https://mou.sr/4lj7JXH     | https://www.vishay.com/docs/63399/si1308edl.pdf |
| SJ                            | SMD Solder Jumper                                                |              | 1        | https://mou.sr/42luaTB     | https://ro.mouser.com/datasheet/2/972/cjs-1827353.pdf |
| USBLC6-2SC6Y                 | ESD Protection Diode Array, 6-Pin SOT-23                          |              | 1        | https://mou.sr/42lyiTK     | https://ro.mouser.com/datasheet/2/389/usblc6_2sc6y-1852505.pdf |
| W25Q512JVEIQ                 | Flash Memory                                                      |              | 1        | https://mou.sr/42vsB6J     | https://ro.mouser.com/datasheet/2/949/Winbond_W25Q512JV_Datasheet-3240039.pdf |
| XC6220A331MR-G               | LDO Voltage Regulator                                             |              | 1        | https://mou.sr/4ieKgVa     | https://ro.mouser.com/ProductDetail/Torex-Semiconductor/XC6220A331MR-G?qs=AsjdqWjXhJ8ZSWznL1J0gg%3D%3D |

# ESP32 C6

| Pin        | Name | Label|  Function             | Connection to  |
|------------|-------|----------|----------------------|----------------|
| 1 | GND | - | Ground | Ground |
| 2 | 3V3 | - | Power | 3.3V |
| 3 | EN | RESET |Reset | Pull-up to 3.3v |
| 4 | IO4 | SS_SD | SD card chip select | SD Card |
| 5 | IO5 | EPD_DC | E-Paper Display Command | J4 |
| 6 | IO6 | SCK | SPI Clock | J3, J4 |
| 7 | IO7 | MOSI | Master Out Slave In | J3, J4 |
| 8 | IO0 | INT_RTC | RTC Interrupt | DS3231SN |
| 9 | IO1 | 32KHZ | 32 kHz output |
| 10 | IO8 | - | Power | 3.3V |
| 11 | IO10 | EPD_CS | E-Paper Display Chip Select | J3 |
| 12 | IO11 | FLASH_CS | Exernal NOR Flash Chip Select | J4 |
| 13 | IO12 | USB_D- | USB D- | J2 via D2 |
| 14 | IO13 | USB_D+ | USB D+ | J2 via D2 |
| 15 | IO9 | IO/BOOT | BOOT button | BOOT button
| 16 | IO18 | RTC_RST | RTC Module Reset | DS3231SN |
| 17 | IO19 | I2C_PW | Power | 3.3V |
| 18 | IO20 | EPD_3V3_C | E-Paper Display Power | 
| 19 | IO21 | SDA |
| 20 | IO22 | SCL |
| 21 | IO23 | EPD_RST | E-Paper Display Reset | J4
| 22 | NC | - | - | -
| 23 | IO15 | IO/CHANGE | Change button | Change Button
| 24 | RXD0/GPIO17 | RX | UART EX
| 25 | TXD0/GPIO16 | TX | UART TX
| 26 | IO3 | EPD_BUSY | E-Paper Display Busy signal | J4
| 27 | IO2 | MISO | Master In Slave Out | J3, J4

| IO3	RESET	SW2, IC5
IO5	GPIO	J4 (EPD_DC)
IO6	SPI SCK	J4 (EPD_SCK), J3 (SD_CLK)
IO7	SPI MOSI	J4 (EPD_DIN), J3 (SD_DI)
IO8	BOOT	SW1 (Buton Boot)
IO10	GPIO / SPI CS	J3 (SD_CS)
IO11	GPIO / SPI CS	J4 (EPD_CS)
IO13	USB D-	J2 (USB-C D-) via D2
IO14	USB D+	J2 (USB-C D+) via D2
IO19	I2C SDA	IC2 (RTC SDA), IC3 (BME SDA/SDO)
IO20	I2C SCL	IC2 (RTC SCL), IC3 (BME SCL/SCK)
IO21	GPIO	J4 (EPD_RST)
IO26	GPIO	J4 (EPD_BUSY)
IO27	SPI MISO	J4 (EPD_DOUT), J3 (SD_DO)
EN	Enable	Pull-up la 3.3V
VDD	Power	3.3V
GND	Ground	Ground
IO12	Neutilizat	-
IO24	Neutilizat	-
IO25	Neutilizat	-

### Battery Level
- IO21 (pin 19): SDA  
- IO22 (pin 20): SCL  

### BME688 Sensor
- IO19 (pin 17): I2C_PW  
- IO21 (pin 19): SD  
- IO22 (pin 20): SCL  

### Buttons  
- EN (pin 3): RESET  
- IO9 (pin 15): IO/BOOT  

### RTC Module DS3231SN  
- IO0 (pin 8): INT_RTC  
- IO1 (pin 9): 32KHZ  
- IO18 (pin 16): RTC_RST  
- IO21 (pin 19): SDA  
- IO22 (pin 20): SCL  

### SD Card  
- IO2 (pin 27): MISO  
- IO4 (pin 4): SS_SD  
- IO6 (pin 6): SCK  
- IO7 (pin 7): MOSI  

### USB-C Connector & ESD Protection  
- IO12 (pin 13): USB_D-  
- IO13 (pin 14): USB_D+

# Errors and warnings
During the design process in Autodesk Fusion, several warnings were flagged in both the schematic and PCB layouts. Below is a summary of the warnings I reviewed and explicitly approved based on the context of this project:

## Schematic (only warnings, no errors)
### "POWER pin X connected to Y" Warnings
- VBAT is supplied via a battery circuit
- 3V3 is regulated by a dedicated LDO
- I2C_PW and other power rails are driven by appropriate sources
- All GND connections are correctly tied to a common ground plane
- POWER pin U3 VBAT connected to VRTC is intentional, VRTC is your battery backup supply for the RTC
- POWER pin SENSOR2 VDDIO connected to I2C_PW / POWER pin SENSOR2 VDD connected to I2C_PW: these refer to the BME680 sensor (SENSOR2), which uses VDD for logic and VDDIO for I/O voltage levels
- POWER pin MCP73831 VIN connected to VBUS: the MCP73831 is a Li-Ion battery charger, and VIN is supposed to be connected to a power input, like USB VBUS
### "Part X has no value" Warnings
- Those parts are supposed not to have value (for example the frame)

## Board
- Smd-Hole, Board Outline-Clearance error (at USB C connector): ok to approved as per instructions given
- Copper width errors (1 data wire, 3 power wires): approved because I manually checked the wire and it has the desired width


_Disclaimer: This project was done using Fusion in browser._
