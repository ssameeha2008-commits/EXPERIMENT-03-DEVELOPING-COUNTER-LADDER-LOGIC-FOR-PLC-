# EXPERIMENT-03-DEVELOPING-COUNTER-LADDER-LOGIC-FOR-PLC-
## NAME:SAMEEHA S
## REGISTER NUMBER:212225230243
## DEPARTMENT:AIDS
## YEAR:2nd
## DATE:03/08/2026

### Aim:
To understand and implement various counter operations in Programmable Logic Controller (PLC) ladder logic.

### Apparatus Required:
Programmable Logic Controller (PLC): A PLC that supports counter functions.
PLC Programming Software: Software such as RSLogix, TIA Portal, or CX-Programmer.
Computer System: For programming and simulating the PLC ladder logic.
Input Devices: Push buttons or switches to trigger the counter operations.
Output Devices: LEDs or other indicators to visualize the counter outputs.
Wires and Connectors: For interfacing input/output devices with the PLC.
Power Supply: Appropriate power supply for the PLC and peripherals.

### Theory:
Counters in PLCs are used to count events or occurrences, such as the number of items passing on a conveyor belt, the number of cycles a machine runs, or how many times a process has started or stopped. Counters are commonly used in automation to perform tasks like stopping a machine after a set number of products or signaling a notification when a count reaches a specific value.

### Types of Counters:
Up Counter (CTU) Functionality:

The up counter counts every time the input condition becomes TRUE (ON). When the accumulated value reaches the preset value, the counter output becomes TRUE. If the reset input is triggered, the counter resets to zero.
Down Counter (CTD) Functionality:

The down counter decreases the count every time the input condition becomes TRUE (ON). When the count reaches zero, the counter output becomes TRUE. The counter can be reset by a reset input to the preset value.
Up/Down Counter (CTUD) Functionality:

The up/down counter can increment or decrement the count based on two different inputs. One input increments the count, while the other decrements it. When the count reaches the preset value or zero, the respective outputs become TRUE. The counter can be reset as required.


### Procedure:
Setup the PLC Programming Environment:
Connect the PLC to the computer and launch the PLC programming software.
Ensure all input and output devices are connected to the PLC’s I/O modules.
Create Ladder Logic for Counters:
Up Counter (CTU):

Create a rung with an input (e.g., a push button) linked to a CTU instruction.
Set the preset value (e.g., 10 counts). Assign an output to indicate when the preset value is reached.
Down Counter (CTD):

Create a rung with an input linked to a CTD instruction.
Set the preset value (e.g., 5 counts). Assign an output to indicate when the counter reaches zero.
Up/Down Counter (CTUD):

Create a rung with separate inputs for counting up and counting down.
Set the preset value (e.g., 8 counts). Assign outputs for when the count reaches the preset value or zero.
Simulate the Ladder Logic:
Up Counter (CTU):

Run the simulation in the PLC software. Press the input button repeatedly and observe the counter increment until the preset value is reached, at which point the output activates.
Down Counter (CTD):

Run the simulation, press the input button repeatedly, and observe the counter decrement. When the counter reaches zero, the output activates.
Up/Down Counter (CTUD):

Simulate both the up and down counting inputs. Observe how the counter increments or decrements and how the output is activated when the count reaches the preset value or zero.
Download and Execute:
Download the ladder logic program to the PLC if available and run it.
Test the counters with the physical push buttons and observe the LEDs or other output devices.
### Outputs:

### Simulation Screenshots:

### COUNTER
<img width="1222" height="647" alt="image" src="https://github.com/user-attachments/assets/41047a06-d7c6-45a9-8cc8-313e678eae0c" />
<img width="1919" height="1023" alt="image" src="https://github.com/user-attachments/assets/d4e5ea63-5b00-4404-91e5-e90f20b86872" />
<img width="1919" height="1018" alt="image" src="https://github.com/user-attachments/assets/b02fd5c1-2489-434a-b018-286eb5605ecb" />
<img width="1919" height="1018" alt="image" src="https://github.com/user-attachments/assets/ac3a2d43-8160-4f57-adbe-1915d426f983" />
<img width="1907" height="1018" alt="image" src="https://github.com/user-attachments/assets/3ecc43a7-58ec-4035-be60-06c1199c27b9" />
<img width="1919" height="1017" alt="image" src="https://github.com/user-attachments/assets/7d4e9b00-f4c8-4429-bd8d-0f64fc5f458f" />

### UP COUNTER
<img width="1037" height="552" alt="image" src="https://github.com/user-attachments/assets/488d2aa7-9cfd-4d98-a9b6-3d9ed55e8891" />
<img width="1036" height="555" alt="image" src="https://github.com/user-attachments/assets/a7e9eaf3-3efd-49fa-8932-c994fe234fd5" />
<img width="1037" height="546" alt="image" src="https://github.com/user-attachments/assets/846847b9-c119-47a4-9500-bb39988f7421" />

### DOWN COUNTER
<img width="1042" height="542" alt="image" src="https://github.com/user-attachments/assets/e5cdf574-15a5-41ae-ab83-3ec79af891bf" />
<img width="1917" height="1002" alt="image" src="https://github.com/user-attachments/assets/a9b1ebed-c147-4de0-92a6-70e8e1b352a2" />
<img width="1917" height="1017" alt="image" src="https://github.com/user-attachments/assets/a777c118-e5ed-460f-94c5-0f701f22a8d0" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/e19500d6-0c3f-4a77-8e28-1a2bc0e80118" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/daccd4f4-4152-4570-a221-29462c3a4596" />


### UP/DOWN COUNTER 
<img width="1173" height="622" alt="image" src="https://github.com/user-attachments/assets/762d048a-abf1-4f78-b70f-9f6222b900a8" />
<img width="1171" height="618" alt="image" src="https://github.com/user-attachments/assets/4a6c26aa-c117-49d9-9eaa-228dc6d06f71" />
<img width="1167" height="626" alt="image" src="https://github.com/user-attachments/assets/0d082d8b-c9d0-478e-8fc3-314b202c57b3" />
<img width="1172" height="622" alt="image" src="https://github.com/user-attachments/assets/e039b915-f7d1-4eba-bfb7-a4fcc35b9a6f" />
<img width="1167" height="623" alt="image" src="https://github.com/user-attachments/assets/e28c7192-3656-4f4e-8178-80b2a9893733" />
<img width="1172" height="625" alt="image" src="https://github.com/user-attachments/assets/baea87b8-a225-4ba5-852c-dc391c964c44" />
<img width="1171" height="622" alt="image" src="https://github.com/user-attachments/assets/012fd4d5-40e6-47fd-afb5-819fd67c6b1a" />
<img width="1172" height="620" alt="image" src="https://github.com/user-attachments/assets/83925873-5749-4757-a214-8cd474a28589" />


### Results:
The ladder logic programs for Up Counter (CTU), Down Counter (CTD), and Up/Down Counter (CTUD) were successfully implemented and tested. The outputs behaved as expected, indicating correct counting operations. The experiment demonstrated how counters are essential in automation for counting events and managing process sequences.
