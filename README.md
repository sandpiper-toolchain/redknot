# redknot
motion control and data acquisition program using Beckhoff platform

project was created using Beckhoff TwinCat3 version 4026.18

the relevant Beckhoff hardware is:\
CX5340-0195 PLC\
2x EL7062 stepper/servo motor terminals\
EL3174-0090 -> analog input 16 bit resolution v/I -> minimum cycle time 500us\

the project currently contains a lightweight integral interface to create and run scripts and control DAQ.
future work on the project will implement an interface in python to communicate over the MQTT protocol.
ongoing work is detailed in the commissioning document which is continuously updated.

currently supports keyence LK-2000 laser displacement sensor,\
and massasonic pulstar ultrasonic sensor.\
work is being done to incorporate sonar based depth detection\
as well as a machine vision based 3d line scan solution.\
