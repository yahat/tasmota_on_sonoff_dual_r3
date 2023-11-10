# Tasmota on Sonoff Dual R3

References
* https://templates.blakadder.com/sonoff_DUALR3.html

Steps
1. flash with https://tasmota.github.io/install/
2. configuration -> config other

normal 

```{"NAME":"Sonoff Dual R3","GPIO":[32,0,0,0,0,0,0,0,0,576,225,0,0,0,0,0,0,0,0,0,0,7296,7328,224,0,0,0,0,160,161,0,0,0,0,0,0],"FLAG":0,"BASE":1}```


zero cross 

```{"NAME":"Sonoff Dual R3 (ZCD)","GPIO":[32,0,0,0,7552,0,0,0,0,576,225,0,0,0,0,0,0,0,0,0,0,7296,7328,224,0,0,0,0,160,161,0,0,0,0,0,0],"FLAG":0,"BASE":1}```


4. menu->console then
5. ```PowerOnState 0``` to set default off on power on
6. ```SwitchMode<x> 3``` to set switches to temporarry push buttons where <x>=1/2/3
