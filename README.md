# SPI-Protocol-Implementation
SPI stands for Serial Peripheral Interface. It is a protocol that is synchronous serial communication. It is used to communicate between the peripheral devices i.e. input and output devices and microcontrollers. SPI can transfer the data and receive data from one device to another device at a time.
Common applications:  communicate with the sensors like temperature sensors, accelerometers, gyroscopes, actuators like motors and servos, memory devices like EEPROMs and flash memory, and displays like LCDs and OLEDs, etc.
The master is the controlling device (usually a microcontroller), while the slave (usually a sensor, display, or memory chip) takes instruction from the master. The simplest configuration of SPI is a single master, single slave system, but one master can control more than one slave.

MOSI (Master Output/Slave Input) – Line for the master to send data to the slave.
MISO (Master Input/Slave Output) – Line for the slave to send data to the master.
SCLK (Clock) – Line for the clock signal.
SS/CS (Slave Select/Chip Select) – Line for the master to select which slave to send data to.
