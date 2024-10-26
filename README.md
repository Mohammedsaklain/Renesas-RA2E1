# Renesas-RA2E1
This repo consist of programs related to Renesas FPB-RA2E1 Microcontroller.
Developing embedded systems applications using Flexible Software Package (FSP) and the e2 studio IDE.

<img width="400" alt="image" src="https://github.com/user-attachments/assets/e9f9956b-f9d2-4bed-887a-9600d287bfaa">

• R7FA2E1A93CFM MCU\
• 48 MHz, Arm® Cortex®-M23 core\
• 128 KB Code Flash, 4 KB Data Flash, 16 KB SRAM

## Top side & Bottom Side of FPB - RA2E1

<img width="385" alt="image" src="https://github.com/user-attachments/assets/837f93e9-dfd9-4f68-b3bd-9647f1904c6a"> <img width="395" alt="image" src="https://github.com/user-attachments/assets/cb32de56-2bc4-485c-b336-067b4a044742">


## Initial Settings:
### 1. Jumper settings
|Pins  | CN-1 Debug Jumper settings                               | CN-3 Debug Jumper settings ( Optional ) |
|------|----------------------------------------------------------|-----------------------------------------|
| 1-2  | Debugger enabled                                         | Normal debug operation                  |
| 2-3  | Debugger held in reset (RA2E1 MCU free-running operation)| Puts the RA2E1 MCU into SCI Boot Mode   |


### 2. Debugger Settings in e2 studio 

| Setting | Actions |  
|---|---|
|Debug hardware| Select - E2 Lite (ARM)     | 
|Power Target From The Emulator| Select - No|  
|Target Device | Select - R7FA2E1A9         |    
<img width="450" alt="image" src="https://github.com/user-attachments/assets/65f9e962-eb02-47ab-81fc-0b0c59c4126b">





 
 
