# 1.RKE (Remote Keyless Entry)
 # 1.1 Description
   * The project Remote Keyless Entry system is designed to remotely lock or unlock access to automobile. It is shortly known as RKE. It consists of two components mainly named as Transmitter and receiver.In Traditional method of opening car doors by inserting physical keys. The RKE allow key holders to remotely lock and unlock car doors,turn on and off alarms.The functions of Remote Keyless Entry are all the led should on at the same time when blue switch on once ,when the blue switch is pressed two times all led should go off at the same time,similarly when the press counts three all led on in anticlockwise manner,and when the press is four times all led on in anticlockwise manner. It works u8sing radio signals emitted from the car and a key fob that searches for those signals.
  # 1.2 5W'S and 1H
    ![Beige and Emerald Simple Modern SWOT Research Graph (3)](https://user-images.githubusercontent.com/98879001/157755096-de5b5189-c050-49c9-923a-5960b901e59f.png)

  # 1.3 SWOT Analysis
  ![Beige and Emerald Simple Modern SWOT Research Graph (2)](https://user-images.githubusercontent.com/98879001/157751157-9ee77acc-d9e1-4cdc-93f3-15eb9c2715b9.png)

# 2.Requirements
# 2.1 High Level Requirements
 | HLR ID | Description|
 |--------| -----------|
 |  HLR1  | This system shall allow the user to enter the car keyless |
 |  HLR2  | The Transmitter in the car shall transmit the signal to the receiver in the car|
 |  HLR3  | This system shall allows the user to operate the car without entering the car (i.e.controlling windows and sunproof).
 |  HLR4  | This system shall alerts the user if someone breaks into the car|
 
# 2.2 Low Level Requirement
 | LLR ID | HLR ID | Description |
 |--------|--------|-------------|
 | LLR1 | HLR2 | The Receiver shall receives the signal and sends to the controller|
 | LLR2 | HLR3 | The Command module commands the sensors to act according to the data given in the controller|
 | LLR3 | HLR4 | The Controller will send all the processed data to the sensors|
