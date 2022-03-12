# Project
# BiCom System
## Description: 
* Bi-com system ,is a system that is designed to remotely lock or unlock the automobiles, RKE operates by broadcasting radio waves on a particular frequency unidirectionally,RKE systems implement encryption algorithms to prevent car thieves from intercepting and spoofing the telegram.
* The term bi-com, is also called keyless entry or remote central locking, refers to a lock that uses an electronic remote control as a key which is activated by a handheld device or automatically by proximity. 
* Widely used in automobiles, an RKS performs the functions of a standard car key without physical contact. When within a few yards of the car, pressing a button on the remote can lock or unlock the doors, and may perform other functions.
## Features:
* A BiCom system is the extention of the unidirectional RKE to bidirectional RKE system
* Typical BiCom status information transmitted to the keyfob are: 
* Print window status (Blue switch on- All led on at the same time)
* Print alarm status - (Blue switch press two times- All led off at the same time
* Print car battery info – (Blue switch press three times- All led on in clockwise manner)
* Print Door status (Blue switch press four times- All led on in anti-clockwise manner)

## Objective:
* To implement BiCom system
## Requirements:
* High Level Requirements:

|  ID  |  Description  |  Status  |
| ------  | ------  |  ------  |
|  HLR1  |  The system should print window status when blue switch press once  |  Implemented  | 
|  HLR2  |  The system should print alarm status when blue switch press two times  |  Implemented  
|  HLR3  |  The system should print car battery info when blue switch press three times  |  Implemented  
|  HLR4  |  The system should print door status when blue switch press four times  |  Implemented  

* Low Level Requirements:

|  ID  |  Description  |  Function  |
|  ------  |  ------  |  ------  |
|  LLR1  |  Press Blue switch once  |  Print Lock  | 
|  LLR2  |  Press Blue switch twice  |  Print Unlock  |
|  LLR3  |  Press Blue switch thrice  |  Activate/Deactivate Alarm  |

# Behavioral Diagram

## Highlevel
![hldiagram](https://user-images.githubusercontent.com/99128901/158007360-4aa3977a-5c4f-4138-b96d-48ded774db2f.png)
![hlstructural](https://user-images.githubusercontent.com/99128901/158007362-b73d0e25-a9f3-45e7-97de-b6d1e4d0c8b8.jpeg)


## Low level Structural Diagram
![llstructural](https://user-images.githubusercontent.com/99128901/158007390-8143f73e-5423-4422-ad61-db9293ddab49.jpeg)



## SWOT Analysis:
* Strenghts: By using the buttons on the remote we can control various functions of the car.

* Weakness: Limited Range 

* Oppurtunities: Can implement more features like knowing the status of the car etc 

* Threats: Need to always carry the Key to lock/unlock the car, if lost may lead to theft.
![SWOT_BICOM](https://user-images.githubusercontent.com/99128901/158007319-494aa500-aecb-4e55-ae50-c09faee9eaf8.png)


## 4W's & 1H:
* Who: Can be used by anyone who owns an automobile
* What: This system can be used in Locking or unlocking the cars
* When: Used when person want to use the car
* Where: it can be used when the user is within the frequency range 
* How: By using buttons on the remote.
![Bicom5W1H](https://user-images.githubusercontent.com/99128901/158007336-b1972218-2ae2-4cd3-8a37-032189bdf4ac.jpeg)

# TEST PLAN

## HIGH LEVEL TEST PLAN 

|Test|	Description|	Input|	Expected output|	Actual Output|
|----|-------------|--------|-------------------|--------------|
|01	|Window Status	|switch pressed once	| shall print window status of the car|	shall print window status of the car|
|02|	Alarm Status|	switch pressed twice|	shall print alarm status of the car|shall print alarm status of the car|
|03	|Car Battery Info|	switch pressed three times|	shall print car battery information|	shall print car battery information|
|04	|Door status|	switch pressed four times|	shall door status of the car|	shall door status of the car|

## LOW LEVEL TEST PLAN

|Test|	Description|	Input|	Expected output|	Actual Output|
|----|-------------|--------|-------------------|--------------|
|01|	Window Status|	switch pressed once|	shall on all led's |shall on all led's	|
|02|	Alarm Status|	switch pressed twice	|shall off all led's| shall off all led's |
|03|	Car Battery Info| switch pressed three times	|shall on led's once clockwise|shall on led's once clockwise	|
|04|	Door status|	switch pressed four times	|shall on led's once anti-clockwise| shall on led's once anti-clockwise	|

# Output
![1click](https://user-images.githubusercontent.com/98834933/158001512-83391399-a6f4-484e-bfef-f7039a45d486.JPG)

