# Smart Home Project

This project was developed as the graduation project for our Embedded Systems diploma. As a team, we designed and implemented a **Smart Home system** using the ATMEGA32A microcontroller. The project integrates various modules to demonstrate a modern, automated home setup.

## Table of Contents
- [About](#about)
- [Features](#features)
- [Tools and Components](#tools-and-components)
- [Installation](#installation)
- [Usage](#usage)
- [Team](#team)
- [Demo](#demo)
- [Contact](#contact)

## About

The **Smart Home Project** utilizes the ATMEGA32A microcontroller to create a system capable of automating home appliances and monitoring environmental conditions. The system integrates various modules for input, output, and communication to offer a comprehensive solution for smart home control.

## Features

- **Two Modes**: Admin mode and User mode, with secure login functionality.
- **Temperature Monitoring**: Using an LM35 temperature sensor.
- **Lighting Control**: Includes LEDs and a dimmer circuit.
- **Device Control**: Operates devices via relay, servo motor, and DC motor.
- **User Interface**: Controlled via 16x2 LCD and 4x4 Keypad.
- **Bluetooth Connectivity**: Enables remote control of the system.

## Tools and Components

- **ATmega Evaluation KIT System**:
  - General Input/Output Module
  - SPI Programmer Module
  - I2C EEPROM Module
  - A/D Converter Module
  - Triple Pushbuttons Module
  - 16x2 Character LCD Module
  - Two-Digit Display Module
  - 3-Bit LED Module
  - Buzzer Module
  - Relay Module
- **External Components**:
  - LCD 16x2
  - 4x4 Keypad
  - Bluetooth Module
  - Dimmer Circuit
  - LEDs (x5)
  - Servo Motor
  - DC Motor
  - LM35 Temperature Sensor

## Installation
**Schematic**:

![Screenshot ](https://github.com/NourGalal7/Smart_Home_Project/blob/main/smart_home.png?raw=true)

1. Assemble the hardware according to the past schematic.  
2. Flash the firmware to the ATMEGA32A microcontroller using an SPI programmer.  
3. Power on the system and follow the usage instructions.  

## Usage


1. **Login**:  
   - The system requires a secure login via the **4x4 Keypad**.  
   - Admins access additional privileges compared to users.  

2. **Modes**:  
   - **User Mode**:  
     - View room temperature using the LM35 sensor.  
     - Control the AC power.  
     - Toggle house lamps ON/OFF.  
     - Adjust lighting levels with the dimmer circuit.  
   - **Admin Mode**:  
     - Access all User Mode features.  
     - Additional privileges, such as controlling the door via the servo motor.  

3. **Bluetooth Control**:  
   - Once logged in, use the Bluetooth Module to interact with components remotely.  

## Team

The following team members developed this project:
1. Ali sherif gaafar beltagy - alisherif8848@gmail.com
2. Abdelrahman Galal El said Ibrahim -  alisherif8848@gmail.com
3. Hadeel Wael Salah Abdulrahman - hadeelwael2004@gmail.com 
4. Nour Eldin Mahmoud Galal  - noorabugalal@gmail.com 
5. Salma Tarek Ahmed  - salmamonairy70@gmail.com
6. Tarek Ahmed Elkfoury - tarek.ahmed4a@gmail.com

## Demo

🎥 A video demonstration of the Smart Home system will be uploaded soon. Stay tuned!
