# FPGA Chat System with Serial Communication and PS/2 Keyboard Interface

## Overview
This project implements a real-time chat system between two FPGA boards using a custom serial communication protocol. The system integrates a PS/2 keyboard interface for user input, and messages are displayed directly on the FPGA boards. The project is built using Nios-II assembly language, ensuring efficient and accurate data transmission.

## Features
- **Serial Communication Protocol:**  
  Designed and implemented a reliable serial communication protocol between two FPGA boards to facilitate real-time message exchange.
  
- **PS/2 Keyboard Integration:**  
  Integrated a PS/2 keyboard interface, allowing users to type and send chat messages to the other FPGA in real-time.

- **Message Display System:**  
  Developed a system to display received messages on the FPGA board. This includes smooth handling of keyboard inputs and real-time updates on the display.

- **Efficient Data Transmission:**  
  Programmed efficient data transmission and reception routines, ensuring timely and accurate message delivery between the FPGA boards.

## How it Works
1. **Keyboard Input:** Users type messages using a PS/2 keyboard connected to the FPGA board.
2. **Message Transmission:** The typed message is transmitted via the custom serial communication protocol to the other F
