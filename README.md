# Overview 
This repository contains two separate sub-projects. One is for writing 100 alphabets from PC to the EEPROM via I2C. The other is for reading data from the EEPROM and transmitting it back to the PC via UART.
# Hardware 
- Chip: STM32F103C8T6 (Blue Pill)
- AT24C256 I2C Interface EEPROM Module
- USB-to-RS232 converter cable, RS232 To UART TTL converter module
# Tools:
- IDE: STM32CubeIDE
- Configuration: STM32CubeMX

# Pinout 
- USART1: PA10 (RX), PA9 (TX)
- I2C1: PB7 (SDA), PB6 (SCL)
