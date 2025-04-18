## Bluetooth Communication with HC-06 and STM32F4

This project establishes seamless communication between the **STM32F4 Discovery** board and the **HC-06 Bluetooth module** using the **USART protocol**. 
The STM32F4 board sends data to a smartphone via Bluetooth, and the data is displayed in a terminal app like **Serial Bluetooth Terminal**.

# Components Used:
- **STM32F4 Discovery Board**
- **HC-06 Bluetooth Module**
- **Smartphone** with **Serial Bluetooth Terminal** app

# How It Works:
1. **USART Setup on STM32F4**: The STM32F4 board communicates with the **HC-06 Bluetooth module** using the **USART protocol** over its TX and RX pins.
2. **HC-06 Bluetooth Module**: The HC-06 module communicates with the STM32F4 board and transmits the data to a paired smartphone via Bluetooth.
3. **Serial Bluetooth Terminal App**: A smartphone app like **Serial Bluetooth Terminal** listens for data and displays it in real-time.

# Features:
- **Wireless Communication** between the STM32F4 board and the smartphone.
- **Real-Time Data Transmission**: Distance and other values are displayed in the Bluetooth terminal app.
- **Extensibility**: The communication can be extended to receive commands from the smartphone.

