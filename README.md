# RFID-and-Keypad-Based-Door-lock-System-Using-Raspberry-PI
The RFID and Keypad Door Lock System is a secure and user-friendly access 
control device designed to enhance safety in homes, offices, and other facilities. 
By combining Radio Frequency Identification (RFID) technology with a 
numeric keypad, the system ensures dual-layer authentication, making it more 
reliable than traditional locking mechanisms. The system uses a microcontroller 
as its core to process user inputs and control a servo motor, which operates the 
locking mechanism.

This project focuses on creating a cost-effective and scalable solution that 
replaces conventional keys with modern access methods, reducing the risks of 
loss, duplication, and misuse. Here’s how the system works and the components 
used:
1.I2C LCD (16x2 LCD with I2C Adapter)
2.Servo Motor (e.g., SG90)
3.Numeric Keypad (4x4 Matrix Keypad)
4.RFID Reader Module (RC522)
5.Raspberry Pi Pico
6.Two LED's 
7.Buzzer

Connection of components with Rashberry PI:
1.I2C LCD
->SDA - Pin 4
->SCL - Pin 5
2.Servo Motor
->Signal Pin (Orange)- Pin 15
3.Keypad
->Row1 - Pin 0
->Row2 - Pin 1
->Row3 - Pin 2
->Row4 - Pin 3
->Col1 - Pin 6
->Col2 - Pin 7
->Col3 - Pin 8
4.RFID Reader
->SS - Pin 13
->SCK - Pin 18
->MOSI - Pin 19
->MISO - Pin 16
->RST - Pin 11
->IRQ - NOT CONNECTED TO ANY PIN
5.LED's
->Green LED - Pin 17
->Red LED - Pin 12
6.Buzzer
->GPIO Pin 20
