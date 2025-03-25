# ENE331 LAB CHALLENGE STM32
The ENE331 Lab Challenge is an experiment involving the use of the STM32 Microcontroller, focusing on system clock configuration, LED control, user input handling, and timer usage. All tasks are accomplished through register-level programming to control various functions, such as blinking an LED at a specific interval, generating accurate timing signals, and verifying the results using an oscilloscope to ensure correct operation.
# Members
1. 65070502455 Sasiwimol Prommin
2. 65070502485 Panisara Thongthep
3. 65070502488 Pichatpong Wiriyaboorana
# system schematic
The system schematic shows how components like the STM32 microcontroller, LEDs, user input (PA0), and Timer2 are connected. It illustrates the flow of signals and how the microcontroller controls the LEDs and responds to user input, with Timer2 generating a 20 µs signal on PB10.

![image](https://github.com/user-attachments/assets/cdf22c61-a5ea-4745-abda-04aad9c6cde1)
# Block Diagram
The Block Diagram outlines the main components of the system and their interactions. It shows the STM32 microcontroller at the center, connected to various blocks like the clock input (25 MHz oscillator), GPIO pins controlling LEDs, user input (PA0), and Timer2 for generating precise time signals (20 µs) on PB10. It simplifies the system’s architecture and data flow.

![image](https://github.com/user-attachments/assets/c1ba8bc3-cd10-4708-8f1d-5df1c1c531c8)
# Result
STM32 Circuit

![image](https://github.com/user-attachments/assets/44ae7f62-5702-4024-8646-7fb11c002624)
![image](https://github.com/user-attachments/assets/96e8b987-177b-4c4e-a7d8-e29468167977)

# Calculation
- Frequncy
  
![image](https://github.com/user-attachments/assets/f3c041aa-ac42-42a6-8e72-2cdd1682014f)
- Prescaler
  
![image](https://github.com/user-attachments/assets/2d04546e-da81-4fd9-8ed8-dd0137334a07)
- Tricks
  
![image](https://github.com/user-attachments/assets/770239a6-a351-4b94-b9ab-7e45a1bb3026)
