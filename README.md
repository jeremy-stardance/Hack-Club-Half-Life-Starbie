# Hack-Club-Half-Life-Starbie
My files for Half-Life week 1.

![image alt](https://github.com/jeremy-stardance/Hack-Club-Half-Life-Starbie/blob/main/Images/Screenshot%202026-10-22%20104034.png)
This is my pcb design for the tamagochi-esque project. It should read temperature and movement to create responses, which can be interacted with using buttons.

## Schematic

I seem to have lost the actual schematic file, but here is the full screenshot of the schematic, which I see no reason doesn't work to prove I made one.

![image alt](https://github.com/jeremy-stardance/Hack-Club-Half-Life-Starbie/blob/main/Images/Schematic.png)

Here is the schematic screenshot. The DHT11 and MPU6050 are my sensors, and the nets are labelled rather than connected by visual wires.

## Bill of Materials

| Component | Quantity | Cost ($) |
|---|---:|---:|
| OLED Display 0.96 inch | 1 | 6.10 |
| ESP32-C3 Supermini | 1 | 4.40 |
| 10k Resistor | 1 | 1.42 |
| MX Buttons | 1 | 5.15 |
| DHT11 | 1 | 2.30 |
| PCB Developement Board | 1 | 6.59 |
| MPU6050 | 1 | 3.29 |
| Shipping | 1 | 3.74 |

This is my Bill of Materials in $USD. I am using the ESP32 as my 'brain' for the code.

## Explaining the Project

I made this project to fullfill the PCB week of Hack Club Half-Life, and I thought it was interesting.

The code should be able to use the DHT11 and MPU6050 sensors to detect movement, tilt, and environmental factors, creating a reaction which demands an input on the player end, using one or both of the buttons. It will operate like a tamagochi. 

The items in my BOM are pretty self-explainitory, and OLED display to display a pixel character, the ESP32-C3 Supermini as the 'brain' which holds the code (as presviusly stated), a 10k resistor to provide resistance for the DHT11 so that the curcuit doesn't short. MX buttons for input. The PCB dev board is because I couln't afford a PCB shipped custom (I live in the UK, so will solder.

## What I Have Learnt

Literally everything. I had a basic understanding of electronics, resistance, ect. from GCSE Physics, but Kicad, Arduino, and even Github were basically new to me before this. 
