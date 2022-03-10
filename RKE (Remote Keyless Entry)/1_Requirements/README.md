# RKE (Remote Keyless Entry)
# High Level Requirements
 | HLR ID | Description|
 |--------| -----------|
 |  HLR1  | This system shall allow the user to enter the car keyless |
 |  HLR2  | The Transmitter in the car shall transmit the signal to the receiver in the car|
 |  HLR3  | This system shall allows the user to operate the car without entering the car (i.e.controlling windows and sunproof).
 |  HLR4  | This system shall alerts the user if someone breaks into the car|
 
# Low Level Requirement
 | LLR ID | HLR ID | Description |
 |--------|--------|-------------|
 | LLR1 | HLR2 | The Receiver shall receives the signal and sends to the controller|
 | LLR2 | HLR3 | The Command module commands the sensors to act according to the data given in the controller|
 | LLR3 | HLR4 | The Controller will send all the processed data to the sensors|
