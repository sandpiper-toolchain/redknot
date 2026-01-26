# redknot
motion control and data acquisition program using Beckhoff platform

project was created using Beckhoff TwinCat3 version 4026.18

the relevant Beckhoff hardware is:
CX5340-0195 PLC
EL7062 stepper/servo motor terminals
EL30xx -> analog input 12 bit resolution
EL3174-0090 -> analog input 16 bit resolution v/I -> minimum cycle time 500us
EL36xx -> analog input 24 bit resolution

the project currently contains a lightweight integral interface to create and run scripts and control DAQ.
future work on the project will implement an interface in python to communicate over the MQTT protocol.
ongoing work is detailed in the commissioning document which is continuously updated
