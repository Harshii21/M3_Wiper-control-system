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
 Low Budget
 
Reputation is Good


#  ENGINE ON STATE
![engine start](https://user-images.githubusercontent.com/74193913/168195223-4ffe543a-e10e-4558-8f71-7fb72f42b8bf.png)
# WIPER SPEED IS LOW
![LOW](https://user-images.githubusercontent.com/74193913/168207426-c329cffd-af87-42a0-bc8b-d875a0c1e922.png)
# WIPER SPEED IS MODERATE
![wiper start](https://user-images.githubusercontent.com/74193913/168195256-babaf133-6f22-4961-be93-fd78d63f2ae4.png)
# WIPER SPEED IS HIGH
![HIGH](https://user-images.githubusercontent.com/74193913/168426068-a835f8a7-460b-4e64-b2c1-6bf446e055a7.png)
# OFF STATE
![off state](https://user-images.githubusercontent.com/74193913/168195291-cc56a05a-6c2d-46f8-842a-e36059586f07.png)


