# Automotive-Can-Logs
A collection of CAN bus logs for reverse engineering. If you have CAN bus logs of any vehicle, feel free to commit them here.
The logs can be used to further refine the OpenDBC collection: https://github.com/commaai/opendbc.

The folder structure is intended as <Brand>/<Network_Name>/<Vehicle>

Any contribution should have a info.txt with the following context (example):


```
Hardware Interface: usbTin
Log Software: CanHacker

Vehicle: Gen 5 Camaro LS3 TR6060 Manual

Driving Scenarios: 

SomeLog.trc: 			Cold start, revving in standstill
SomeLog2.trc: 			Driving in busy traffic


```