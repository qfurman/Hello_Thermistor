# PSoC 6 MCU: Hello Thermistor

This code example demonstrates simple UART communication by printing the temperature as a "+25.4" message on a terminal with an interval and blinks an LED using a Timer resource using PSoC® 6 MCU.
As the name suggests, this project is derived from the hello world project. 

## Terminal can be used to send commands:
stop - stop measurement

start - start periodic measurement

period s - to change the measurement period in the range s = 1..5 sec.

Each command has an acknowledge:

stop - measurement paused

start - measurement started

period - new period s sec.