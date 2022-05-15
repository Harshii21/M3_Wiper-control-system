ABSTRACT
A wiper is a necessary component that cleans raindrops or any other liquid off the vehicle's windscreen. The prior system required manual wiper activation,
by changing the frequency As its results the operation of bringing up the wiper speed is varied . The project's goals are to improve ageing cars' systems 
by giving automated transmission.wiping system, to improve the system by incorporating a sensor and actuator, and to create a simple software that would
completely operate with the system.the framework This proposed wiper system's principle is comparable to those of other existing conventional wipers. 
Despite the fact that. This system will be upgraded to an automatic control system using a Peripheral Interface to remove water from the windscreen.

INTRODUCTION
The operational speed of a wiper is controlled by a wiper speed control system in accordance with frequencies. The pulse signal is digitally processed
to provide a control signal. A wiper driver circuit receives the control signal and adjusts the operational speed or timing in line with it.

SOFTWARE REQUIREMENTS
STM32 CUBE IDE

COMPONENTS
STM32F4O7VG MICROCONTROLLER BOARD

WORKING PRINCIPLE
Assume that the automobile is the microcontroller. If the button is hit, the first led (red) will turn on, Clicking again  the wiper will start,
and the second led (blue) will turn on for a desired rate. If the button is pressed again, the third led (green) will turn on, and the wiper's 
speed will be increased in comparison to the previous one. The fourth press will turn on the fourth led (orange), and the wiper speed will be 
increased in accordance with the previous one. The microcontroller (vehicle) is turned off after the fifth click.

# HIGHLEVEL REQUIREMENTS 

|High Level Requirements|Description|
|:------|:---------|
|1|Programming language(C language)|
|2|Arm based microcontroller(STM32F40VGT6)|
|3|operating system(Windows)|
|4|RAM(Min 4GB)|
|5|Hard Disk(Min 250GB)|

# LOWLEVEL REQUIREMENTS

|Low Level Reqiurements|Description|Status|
|:-----|:--------|:---|
|1|ON-Ignition key|Implemented|
|2|Press Multi-functional button|Implemented|
|3|4 Different Color Leds|Implemented|
|4|Timer|Implemented|
|5|OFF-Wiper button|Implemented| 

  ## SWOT ANALYSIS
 # STRENGTH
