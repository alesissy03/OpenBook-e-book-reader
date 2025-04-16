# OpenBook-e-book-reader

![image](https://github.com/user-attachments/assets/9bbbaf0a-def0-4646-a5ea-911b73e33ba6)

# Bill of Materials

## Component List

Name / Part Number | Description | Value | Qty | Buy Link | Datasheet
744043680 | IND_4828-WE-TPC_WRE Inductor | 68µH | 1 | Mouser | —
112A-TAAR-RO3_ATTEND | Micro SD Card Socket, Push-Push, Top Mount, SMT | — | 1 | ATTEND | —
BD5229G-TR | Voltage Detector with Adjustable Delay Time (CMOS) | — | 1 | Mouser | —
BUTTON_CUSYOMV1 | Momentary Switch (Pushbutton) SPST, SMD, 4.6 x 2.8mm | — | 3 | Mouser | —
CPH3225A | Capacitor, 0.011F, 3.3V, 1210 Flat | 0.011F | 1 | Mouser | —
DS3231SN# | Real Time Clock, Serial, 16-Pin SOIC | — | 1 | Mouser | —
EAGLE-LTSPICE_CC0402 | Capacitor | 100nF | 8 | Mouser | —
 |  | 4.7µF | 5 | Mouser | —
 |  | 10µF | 1 | Mouser | —
 |  | 1µF / 50V | 9 | Mouser | —
 |  | 0.1µF / 50V | 1 | Mouser | —
 |  | 1nF | 1 | Mouser | —
ESP32_WROVER_BME680 | BME680 Integrated Environmental Sensor | — | 1 | Mouser | —
ESP32_WROVER_AVX--- | Schottky Barrier Rectifier Diode | — | 1 | — | —
ESP32_WROVER_RR0402 | Resistor | 10k | 15 | Mouser | —
 |  | 2.2 | 1 | Mouser | —
 |  | 0.47 | 1 | Mouser | —
 |  | 200 | 1 | Mouser | —
 |  | 2k | 1 | Mouser | —
 |  | 15 | 1 | Mouser | —
 |  | 5k1 | 2 | Mouser | —
 |  | 100k | 1 | Mouser | —
ESP32_WROVER_SPARKFUN- | P-Channel MOSFET | — | 2 | Mouser | —
ESP32_WROVER_SPARKFUN-IC- | MCP73831T Li-Ion / Li-Pol Battery Charger Controller | — | 1 | Mouser | —
ESP32C6_VARISTORCN1812 | Varistor | — | 1 | Mouser | —
ESP32-C6-WROOM-1-N8 | ESP32-C6 Wi-Fi MCU Module | — | 1 | Mouser | —
FH34SRJ-24S-0.5SH_99_ | 24-pos FFC/FPC Connector, Right Angle | — | 1 | Mouser | —
MAX17048G+T10 | Fuel Gauge IC | — | 1 | Mouser | —
MBR0530 | Schottky Diode, 0.5A, 30V, SOD-123 | — | 2 | Mouser | —
PGB1010603MR | ESD Suppressor | — | 6 | Mouser | —
QWIIC_CONNECTORJS-1MM | I²C Qwiic JST Connector, 4-pin Horizontal | — | 1 | SparkFun | —
RCL_CPOL-EUCT3528 | Polarized Capacitor (Tantalum) | 100µF | 1 | Mouser | —
SAMACSYS_USB4110-GF-A | USB 2.0 Type-C Connector, SMT, Right Angle | — | 1 | Digi-Key | —
SI1308EDL-T1-GE3 | N-Channel MOSFET, 30V, 1.5A | — | 1 | Mouser | —
SJ | SMD Solder Jumper | — | 1 | Mouser | —
USBLC6-2SC6Y | ESD Protection Diode Array, 6-Pin SOT-23 | — | 1 | Mouser | —
W25Q512JVEIQ | 512Mbit SPI NOR Flash Memory | — | 1 | Mouser | —
XC6220A331MR-G | LDO Voltage Regulator, 3.3V | — | 1 | Mouser | —
# ESP32 C6

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

_Disclaimer: This project was done using Fusion in browser._

_I was not able to import DRC (.dru) file._
![image](https://github.com/user-attachments/assets/61e9edff-73e2-4e78-9cfa-8bb1c05a8d7e)

