# 1.Remote Keyless Entry
 # 1.1 Problem Statement
  * Remote keyless Entry system is used for easy controlling of vehicle and for security reasons. The previous systems of keys had many problems with security and lack of features. This system has sorted out the problems of previous systems and has many features.
  # 1.2 Description
  * The project Remote Keyless Entry (RKE) system is designed to remotely lock, unlock  and to access the vehicle. It consists of two major working components i.e. Transmitter and receiver. This system is third generations of keys, the first gen was  physical keys to access the vehicle and the second gen is keyless entry which uses  similar components but with less features and lower security level. The RKE allows the key holders to remotely lock and unlock car doors, turn on and off alarms and  can access few other features.
  # 1.3 5W'S and 1H
  ![Beige and Emerald Simple Modern SWOT Research Graph (3)](https://user-images.githubusercontent.com/98879001/157755465-bba66aeb-cda4-484b-9b15-bef040721d48.png)

  # 1.4 SWOT Analysis
  ![Beige and Emerald Simple Modern SWOT Research Graph (2)](https://user-images.githubusercontent.com/98879001/157751157-9ee77acc-d9e1-4cdc-93f3-15eb9c2715b9.png)

# 2.Requirements
# 2.1 High Level Requirements
 | HLR ID | Description|
 |--------| -----------|
 |  HLR1  | This system shall allow the user to enter the car keyless |
 |  HLR2  | The Transmitter in the remote shall transmit the signal to the receiver in the car|
 |  HLR3  | This system shall allows the user to operate the vehicle without entering the vehicle (i.e.controlling windows and sunproof)|.
 |  HLR4  | This system shall alerts the user if someone breaks into the car|
 
# 2.2 Low Level Requirement
 | LLR ID | HLR ID | Description |
 |--------|--------|-------------|
 | LLR1 | HLR2 | The Receiver shall receives the signal and sends to the controller|
 | LLR2 | HLR3 | The Command module commands the sensors to act according to the data given in the controller|
 | LLR3 | HLR4 | The Controller will send all the processed data to the sensors to perform the specified operations|
# 3.Block Diagram
 # 3.1 High Level Diagram
   ![Add a subheading (1)](https://user-images.githubusercontent.com/98879001/157820195-379bfaa6-09aa-4807-a116-d96b9d6fcebe.png)

# 3.2 Low Level Diagram
   ![PUSH BUTTON](https://user-images.githubusercontent.com/98879001/157829376-62b52161-abbe-4109-808e-36b5b10d2b7d.png)
# 4.Test plan  
# 4.1 High Level Test Plan
|Test ID | Description| Expected Output | Type of Test |
|--------|------------|-----------------|--------------|
|HLT1| Receiver receives the signal |Receives  |Requirement Based|
|HLT2| Controller commands the sensor | Controlling the system |Scenario based|
|HLT3| Vehicle unlocks |Unlocking Vehicle |Boundary based|
___
# 4.2 Low Level Test Plan
|Test ID | Description| Expected output | Type of Test |
|--------|------------|-----------------|--------------|
|LLT1|Identify the signal from transmitter| Sensed| Requirement Based|
|LLT2| Opening windows| Processing | Scenario Based|
|LLT3 |Vehicle locks | Locked| Boundary Based|
# 5.Application
 * The keyless entry is designed to make life easier, its growing popularity bhas brought a huge range of options and things to consider.
 * For more security applications,its vital to have an access control system that can handle the specific needs of the building and its user.
 * Anti tamper lockout to restrict access after a certain number of failed attempts.
 * This system allows the user to enter into the vehicle without the keys.
 * This system avoids the necessity of using a physical key to open the car.
 * This system allows the user to operate the vehicle without getting into the vehicle.
 * With this system the user can start the vehicle with just the Remote Key.
 * This system has higher security functions when compared to keyless entry systems.
# 6.Survey
 * [Remote Keyless Entry refernce survey](https://www.sciencedirect.com/topics/engineering/keyless-entry-system)
 * [Remote keyless Entry Security survey ](https://illmatics.com/remote%20attack%20surfaces.pdf)
 * [Future scope of RKE ](https://www.globenewswire.com/news-release/2021/07/02/2256984/0/en/Automotive-Keyless-Entry-Systems-Market-Size-2021-Is-Projected-to-Reach-USD-3-061-4-million-by-2028-Exhibiting-a-CAGR-of-12-2.html)



   

     


