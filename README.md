# STM32F103 SSD1306 OLED Display with Button Input and ADC

## Description
This project demonstrates the usage of an SSD1306 OLED display interfaced with an STM32F103 microcontroller. It includes button input and ADC reading functionality. The system is designed using multiple RTOS threads to handle various tasks such as reading button inputs, fetching ADC values, and displaying data on both the OLED display and UART console.

## Features
- **SSD1306 OLED Display:** Displays messages and ADC values.
- **Button Input:** Handles input from two buttons with debouncing functionality.
- **UART Interface:** Allows communication over UART, providing menu options and displaying ADC values.
- **RTOS (CMSIS-OS2):** Utilizes FreeRTOS for multi-tasking, managing threads and system tasks.
- **ADC Reading:** Captures voltage levels via the STM32's ADC and displays them on the OLED and UART.

## Hardware Required
- STM32F103 microcontroller (or compatible STM32 microcontroller)
- SSD1306 I2C OLED Display
- Buttons connected to GPIO
- UART-to-USB interface for serial communication

  [Hardware](https://drive.google.com/uc?export=view&id=1ClM6-yfTX0s4hKgUrnlFBUfKFo-VXfCr)

## Node/Task Diagram
- **SSD1306 OLED Display:** Displays messages and ADC values.
- **Button Input:** Detects button presses and handles debouncing.
- **UART Interface:** Communicates via UART for menu display and ADC values.
- **RTOS Threads:** Manages tasks for ADC reading, button input handling, and UART display.
- **ADC Reading:** Reads voltage levels through the STM32's ADC and displays them.

[Diagram task](https://drive.google.com/uc?export=view&id=1EqkuRLFuo2aQudnx5blB0JFDaCvHuCCu)

## Video
[Video Demo](https://drive.google.com/file/d/12W8rBGFNa61qh74dkdPl1ldZqX-xp7_A/view?usp=sharing)

![](https://github.com/QonitaTKB/first-RTOS-Program-task/blob/master/96s21x.gif)


