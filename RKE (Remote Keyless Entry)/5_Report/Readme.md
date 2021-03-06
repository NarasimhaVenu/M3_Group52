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

![image](https://user-images.githubusercontent.com/98816218/157891624-6a04ca08-4fac-49fe-a946-012e8bfacefd.png)

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

## SWOT Analysis:
* Strenghts: By using the buttons on the remote we can control various functions of the car.

* Weakness: Limited Range 

* Oppurtunities: Can implement more features like knowing the status of the car etc 

* Threats: Need to always carry the Key to lock/unlock the car, if lost may lead to theft.

## 4W's & 1H:
* Who: Can be used by anyone who owns an automobile
* What: This system can be used in Locking or unlocking the cars
* When: Used when person want to use the car
* Where: it can be used when the user is within the frequency range 
* How: By using buttons on the remote.

## Block Diagram
![image](https://user-images.githubusercontent.com/98816218/157863332-1ef24884-a647-4754-825c-174b4cd38e96.png)
## Flow Chart
![image](https://user-images.githubusercontent.com/98816218/157863445-e305ef42-9e66-463d-a972-25ac120fb19a.png)
![image](https://user-images.githubusercontent.com/98816218/157891715-f84d24fd-261d-4009-a49d-f80fed924372.png)
![image](https://user-images.githubusercontent.com/98816218/157891812-330183a4-539d-44c6-8055-7ba46bcf2471.png)

## Functional Diagram
![image](https://user-images.githubusercontent.com/98816218/157863526-332a7966-1d23-4402-bbe1-c0b054eb0c5c.png)


## Test Plan

# High Level Test Plan
|  Test ID  |  Description  |  Expected Input  |  Expected Output  |  Status  |
| ------  | ------  | ------ | ------ | ------ |
|  HL01  |  Locking the Car  |  Press the blue button once  |  Print Lock  |  Implemented  |
|  HL02  |  Unlocking the Car  |  Press the blue button twice  |  Print Unlock  |  Implemented  |
|  HL03  |  Alarm Actiation/Deactivation |  Press the blue button thrice  |  Print Activation/Deactivation  |  Implemented  |
|  HL04  |  Approachin lights for the car  |  Press the blue button four times  |  Print Approach lights  |  Implemented  |
# Low Level Test Plan
|  Test ID  |  Description  |  Expected Input  |  Expected Output  |  Status  |
| ------  | ------  | ------ | ------ | ------ |
|  LL01  |  All Leds will on at the same time  |  Press the blue button once  |  Print Lock  |  Implemented  |
|  LL02  |  All Leds will off at the same time  |  Press the blue button twice  |  Print UnLock  |  Implemented  |
|  LL31  |  All Leds will blink in Clockwise manner  |  Press the blue button thrice  |  Print Activation/Deactivation  |  Implemented  |



# Output



## Output Image


![1click](https://user-images.githubusercontent.com/98834933/158001512-83391399-a6f4-484e-bfef-f7039a45d486.JPG)



## Simulation Video

https://user-images.githubusercontent.com/98834933/158001210-c5c1c998-50e3-4d84-b04d-13793468cc11.mp4
