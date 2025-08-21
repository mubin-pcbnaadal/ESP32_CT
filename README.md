CT_ESP32 Hardware Design

This repository contains the hardware design files and schematics for the CT_ESP32 board. The design is based on the ESP32-S3-WROOM-1 module and integrates motor drivers, current sensing, CAN bus, and power management for robotics and embedded control applications.

Features

Point 1: Main controller is ESP32-S3-WROOM-1 with dual-core Xtensa LX7 processor, Wi-Fi, and Bluetooth 5.0 support.

Point 2: Motor control through BTS7960B H-bridge driver, capable of handling high current for DC motors.

Point 3: Current sensing provided by INA240A bi-directional current sense amplifier for accurate monitoring.

Point 4: Position sensing via AS5047P magnetic rotary encoder connected through SPI interface.

Point 5: High-speed CAN communication using TCAN3413 transceiver for robust networking in automotive or industrial systems.

Point 6: Power management includes AP63357DV buck converter for 5V supply and AMS1117 LDO for 3.3V regulation.

Point 7: USB Type-C connector for programming, debugging, and powering the board.

Point 8: GPIO expansion headers with access to SPI, UART, and I2C interfaces.

Point 9: Indicator LEDs for power status and system diagnostics.

Repository Contents

Point 1: CT_ESP32.pdf – complete schematic diagram of the hardware.
Point 2: Netlist and component reference designators for assembly and debugging.
Point 3: Integrated bill of materials (BOM) available within the schematic.

Applications

Point 1: Robotics and automation systems requiring motor control with feedback.
Point 2: Industrial CAN bus networks and distributed embedded systems.
Point 3: Smart controllers with wireless connectivity and real-time current sensing.
Point 4: Educational and research projects involving motor drivers and position sensing.
