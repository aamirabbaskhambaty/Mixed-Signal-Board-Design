# Mixed-Signal-Board-Design
## Mixed Signal Board Design on Altium (4 layer, 2 Sided Assembly)
### **General Description**
The following project is a 4 layer 2 sided assembly mixed signal Printed Circuit Board(PCB) designed on Altium. Its details are as follows:
1. ARM® Cortex®-M4 STM32F407VGT6 32bit Microcontroller with 1 MB Flash in an LQFP Package.
2. ARM® Cortex®-M3 STM32F103C8T6 32 bit Microcontroller with 64 Kb Flash in an LQFP Package used as a debugger(SWD).
3. CH340C USB to UART Converter.
4. DP83826IRHBR Ethernet PHY using MII(10/100) along with RJ-45 Connector with inbuilt Magnetics & external ESD Protection.
5. ADS122C04IPW 24 Bit Analog to Digital Converter using I2C Protocol.
6. CS43L22-CNZ Low Power Stereo DAC with Class D Speaker Driver using I2S Protocol.
7. IMP34DT05TR MEMS MIC.
8. 2x DRV8701ERGET Bi-directional Motor Drivers with DMHT6016LFJ-13 N-Channel FET Array.36 Watts Motor power.
9. TPS62933DRLR Buck Converter set to 3.3V @ 1.6A.
10. LD1117S18TR 1.8V 0.8A fixed LDO.
11. External UART
12. External CAN Interface

Project Files have been uploaded to the repository.
    
**Schematic Block Diagram**


![Screenshot 2024-04-20 155449](https://github.com/aamirabbaskhambaty/Mixed-Signal-Board-Design/assets/114267693/a7f257f4-bfe0-4880-9a89-33abeca4a05d)
### **PCB Layout and 3D Views**
**Top Layer**

![Top pcb](https://github.com/aamirabbaskhambaty/Mixed-Signal-Board-Design/assets/114267693/eb395783-029e-4d8e-8bf7-da3354ef80a0)

**Bottom Layer**


![Bottom](https://github.com/aamirabbaskhambaty/Mixed-Signal-Board-Design/assets/114267693/2d86e8a2-6f39-49ce-ac25-f39c98c8fb32)

**3D Views**


![3d top side](https://github.com/aamirabbaskhambaty/Mixed-Signal-Board-Design/assets/114267693/bd4fbf07-29f1-48f9-ba73-51c23b696a46)


![3d bottom](https://github.com/aamirabbaskhambaty/Mixed-Signal-Board-Design/assets/114267693/197f4a16-fa4d-4e31-b198-6a6bbf058fb0)


![3d iso](https://github.com/aamirabbaskhambaty/Mixed-Signal-Board-Design/assets/114267693/fdf8dc2e-17ed-420f-9cc0-9d5ac606234a)

### **Individual Schematics**
  #### **Ethernet Schemactic(DP83826IRHBR):**


  ![ethernet phy](https://github.com/aamirabbaskhambaty/Mixed-Signal-Board-Design/assets/114267693/657ceb7c-70a2-4bce-84bb-fb668229579b)




#### **STM32F103C8T6 Debugger Schemactic:**




![1713647174527-4486e688-5e0e-4607-b28f-8b519f514e56_9](https://github.com/aamirabbaskhambaty/Mixed-Signal-Board-Design/assets/114267693/7afb58aa-27a6-4d3e-8182-f441d6e9bc75)



#### **ADS122C04IPW 24 Bit Analog to Digital Converter Schemactic:**




![adc](https://github.com/aamirabbaskhambaty/Mixed-Signal-Board-Design/assets/114267693/30e200a9-5846-4c65-ade0-9dbbab738af1)



#### **CS43L22-CNZ Low Power Stereo DAC + IMP34DT05TR MEMS MIC Schemactic:**





![dac mic](https://github.com/aamirabbaskhambaty/Mixed-Signal-Board-Design/assets/114267693/f60bcb6f-0b8a-434b-b1db-139be44e302c)


#### **DRV8701ERGET Bi-directional Motor Drivers with DMHT6016LFJ-13 N-Channel FET Array Schematic:**





![motor](https://github.com/aamirabbaskhambaty/Mixed-Signal-Board-Design/assets/114267693/afaa8909-3faa-446e-8780-43b4a4835eb6)


#### **ARM® Cortex®-M4 STM32F407VGT6 32bit Microcontroller Schematic:**





![master mcu](https://github.com/aamirabbaskhambaty/Mixed-Signal-Board-Design/assets/114267693/fd90f34d-0a06-40d4-ba3f-87de1e2b8615)



#### **CH340C USB TO UART Converter Schematic:**




![CH340](https://github.com/aamirabbaskhambaty/Mixed-Signal-Board-Design/assets/114267693/0c2bade2-50ee-4477-beeb-7225833aa0cb)


#### **Power Management Schematic:**





![power](https://github.com/aamirabbaskhambaty/Mixed-Signal-Board-Design/assets/114267693/a445a72c-7148-454c-a190-7d13acb4cc11)
