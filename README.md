# Remote 4x4 Car
Three different version 4x4 RC car with arduino.

# Last Update
Last PCB Shield design is [Gerber_Arduino Mega Shield V2_20200217124525.zip](https://github.com/Daniele-Venturin/RC-Car/blob/master/Docs/Altro/Gerber_Arduino%20Mega%20Shield%20V2_20200217124525.zip)
## V1.0 (IR) Relè & L298N
###### Components
- 1x RGB Led (Optional)
- 2x 1kohm resistors
- 2x 2 Relay
- 4x DC Motors
- 1x HC-SR04 (Ultrasonic Sensor)
- 1x 1838B (iR Receiver)
- 1x Arduino Nano or Arduino UNO
- 1x Buzzer (Optional)
- 2x Battery pack 7-12V

###### PinOut
LED Status
- D3 ➞ Red
- D4 ➞ Green

Signal Reciver
- D5 ➞ IR reciver

Ultrasonic Sensor
- D6 ➞ Echo 
- D7 ➞ Trig

Relay
- D8 ➞ SX1
- D9 ➞ SX2
- D10 ➞ DX1
- D11 ➞ DX2

Sound
- D12 ➞ Buzzer

## V2.0 (Bluetooth)
###### Components
- 1x Custom PCB Shield
- 1x L298N DC Motor driver
- 1x Buzzer (optional)
- 1x RGB Led (optional)
- 1x HC-05 (Bluetooth Module)
- 4x HC-SR04 (Ultrasonic Sensor)
- 4x DC Motors
- 1x Arduino MEGA 2560
- 1x Battery Pack (11,1V 2200 mAh)
- 1x BMS 3S 20C

###### PinOut
Digitali
LED Status
- D8 ➞ Green
- D9 ➞ Red

Sound
- D10 ➞ Buzzer
- D11 ➞ Fari Posteriori
- D12 ➞ Faro Anteriori

Sensori
- D22 ➞ Trig 1
- D23 ➞ Echo 1
- D24 ➞ Trig 2
- D25 ➞ Echo 2
- D26 ➞ Trig 3
- D27 ➞ Echo 3
- D28 ➞ Trig 4
- D29 ➞ Echo 4

Driver Motori
- D2 ➞ Enable 1
- D3 ➞ Input 1
- D4 ➞ Input 2
- D5 ➞ Input 3
- D6 ➞ Input 4
- D7 ➞ Enable 2

Analogici
- A0 ➞ Stop Button 
- A1 ➞ Fotoresistenza

## V3.0 (WI-FI)
###### Components
- 1x Custom Motherboard PCB
- 4x 1kohm resistors (R1-R2-R3-R4)
- 2x 33kohm resistors (R5-R6)
- 1x L298N DC Motor driver
- 1x Buzzer (Optional)
- 1x RGB Led (Optional)
- 1x ESP8266 (WI-FI Module)
- 4x HC-SR04 (Ultrasonic Sensor)
- 4x DC Motors
- 1x Arduino MEGA
- 1x Battery Pack (11,1V 2200 mAh)
- 1x BMS 3S 20C

###### PinOut
Digitali
LED Status
- D8 ➞ Green
- D9 ➞ Red

Sound
- D10 ➞ Buzzer
- D11 ➞ Fari Posteriori
- D12 ➞ Faro Anteriori

Sensori
- D22 ➞ Trig 1
- D23 ➞ Echo 1
- D24 ➞ Trig 2
- D25 ➞ Echo 2
- D26 ➞ Trig 3
- D27 ➞ Echo 3
- D28 ➞ Trig 4
- D29 ➞ Echo 4

Driver Motori
- D2 ➞ Enable 1
- D3 ➞ Input 1
- D4 ➞ Input 2
- D5 ➞ Input 3
- D6 ➞ Input 4
- D7 ➞ Enable 2

Analogici
- A0 ➞ Stop Button 
- A1 ➞ Fotoresistenza

## Docs

###### Wire diagram 

###### Gerber file PCB
Top view of PCB

![Top](https://i.imgur.com/vG5EBmy.png) 

Bottom view of PCB

![Bottom](https://i.imgur.com/CqWlIeZ.png)
