# Project
# RKE (Remote Keyless Entry)
## Description:
* Remote keyless entry (RKE) system is a system designed to remotely lock or unlock access to automobiles. 
* Remote keyless systems consist of a key fob transmitter and a receiver inside the vehicle. This radio frequency signal, or RF for short, is sent as an encrypted data stream directly to the car.
* Transmitter - RKE key fob, other ID device with RKE integrated 
* Receiver - Body Control ECU, other ECU with integrated RKE 
* This system operates by broadcasting radio waves on a particular frequency unidirectionally
* The system implement encryption and rolling.
## Functions of Remote Keyless Entry
* Locking or Unlocking the door
* Alarm activation or deactivation
* For turning on/off Approaching lights
## Objective:
* To implement a RKE System to lock or unlock access automobiles.
## Requirements:
* High Level Requirements:

|  ID  |  Function  |  Description  |
| ------  | -------  |  -------  |
|  HLR1  |  Lock  |  All leds will on at the same time  | 
|  HLR2  |  Unlock  |  All leds will off at the same time  |
|  HLR3  |  Alarm activation/deactivation  |  All leds will blink in clockwise manner  |
|  HLR4  |  Approach light  |  All leds will blink in anti-clockwise manner  | 

* Low Level Requirements:

|  ID  |  Description  |  Function  |
|  ------  |  ------  |  ------  |
|  LLR1  |  Press Blue switch once  |  Print Lock  | 
|  LLR2  |  Press Blue switch twice  |  Print Unlock  |
|  LLR3  |  Press Blue switch thrice  |  Activate/Deactivate Alarm  |
