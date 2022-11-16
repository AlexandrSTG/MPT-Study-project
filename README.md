# MPT-Study-project
This code is written for microcontroller based on stm32 on C, C++ language. 
Code contains seperate parts: main, ini, USART, code_for_display.

ADC_ini (Analog-To-Digital Converter) is about initialisation ADC. It samples the analog input whenever you trigger it to start conversion. And it performs a process called quantization so as to decide on the voltage level and its binary code that gets pushed in the output register.

USART (Universal asynchronous receiver-transmitter) is a type of peripheral communications hardware device that allows a computer to communicate synchronously and asynchronously with serially connected devices by wifi or bluetooth.

code_for_display part is contain code for 7 segment display.

main initializate ADC_ini, USART, code_for_display and start the cycle of recieve information, displaying it, sending it to the other device, repeat. 
