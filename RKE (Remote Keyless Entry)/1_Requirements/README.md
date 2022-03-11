# 1.RKE (Remote Keyless Entry)
 # 1.1 Description
  * The project Remote Keyless Entry (RKE) system is designed to remotely lock, unlock  and to access the vehicle. It consists of two major working components i.e. Transmitter and receiver. This system is third generations of keys, the first gen was  physical keys to access the vehicle and the second gen is keyless entry which uses  similar components but with less features and lower security level. The RKE allows the key holders to remotely lock and unlock car doors, turn on and off alarms and  can access few other features.
 # 1.2 Problem Statement
  * Remote keyless Entry system is used for easy controlling of vehicle and for security reasons. The previous systems of keys had many problems with security and lack of features. This system has sorted out the problems of previous systems and has many features.

# 2.Requirements
# 2.1 High Level Requirements
 | HLR ID | Description|
 |--------| -----------|
 |  HLR1  | This system will allow the user to enter the car keyless |
 |  HLR2  | The Transmitter in the remote will transmit the signal to the receiver in the car|
 |  HLR3  | This system allows the user to operate the car without entering the car (i.e.controlling windows and sunroof)|
 |  HLR4  | This system alerts the user if someone breaks into the car|
 
# 2.2 Low Level Requirement
 | LLR ID | HLR ID | Description |
 |--------|--------|-------------|
 | LLR1 | HLR2 | The Receiver receives the signal and sends to the controller|
 | LLR2 | HLR3 | The Command module commands the sensors to act according to the data given in the controller|
 | LLR3 | HLR4 | The Controller will send all the processed data to the sensors to perform the specified operations|
 # Survey
 * [Remote Keyless Entry refernce survey](https://www.sciencedirect.com/topics/engineering/keyless-entry-system)
 * [Remote keyless Entry Security survey ](https://illmatics.com/remote%20attack%20surfaces.pdf)
 * [Future scope of RKE ](https://www.globenewswire.com/news-release/2021/07/02/2256984/0/en/Automotive-Keyless-Entry-Systems-Market-Size-2021-Is-Projected-to-Reach-USD-3-061-4-million-by-2028-Exhibiting-a-CAGR-of-12-2.html)



 
