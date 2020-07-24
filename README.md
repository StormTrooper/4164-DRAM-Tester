#4164 / 41256 DRAM Tester  using the Arduino Nano ATmega168


Original code from http://forum.defence-force.org/viewtopic.php?t=1699

Using DIO2 library for faster read/write to I/O ports.


- Flashing green LED shows test progress
- Solid red LED, chip has failed tests
- Solid green LED, chip passed tests

Progress and errors are written to the serial port at 115200. 

