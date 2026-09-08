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
<img width="1919" height="1018" alt="image" src="https://github.com/user-attachments/assets/852e08a2-eba1-4798-b5a9-adc39c53bae9" />
<img width="1504" height="155" alt="image" src="https://github.com/user-attachments/assets/0a3071ea-e32b-4deb-9272-0c8bb92c14a5" />
<img width="1501" height="200" alt="image" src="https://github.com/user-attachments/assets/4364a4d7-7d12-472b-8eca-2b2616196b5f" />
<img width="1500" height="250" alt="image" src="https://github.com/user-attachments/assets/74a80122-f37c-4076-acd2-319fcea1015d" />

### DOWN COUNTER
<img width="1463" height="647" alt="image" src="https://github.com/user-attachments/assets/3e1385a4-6a64-4841-a4eb-03a384f772ed" />
<img width="1351" height="375" alt="image" src="https://github.com/user-attachments/assets/66b1e8da-9e7d-400f-9ef0-4fce60080614" />
<img width="1502" height="229" alt="image" src="https://github.com/user-attachments/assets/19cd4422-ed01-4599-84fe-8dafcd817253" />
<img width="1504" height="339" alt="image" src="https://github.com/user-attachments/assets/ad08de71-987d-4350-83f6-75ee9390ca17" />
<img width="1509" height="312" alt="image" src="https://github.com/user-attachments/assets/7aa93082-030f-4acd-bd69-69927de7c8f8" />

### UP/DOWN COUNTER - 1
<img width="1606" height="651" alt="image" src="https://github.com/user-attachments/assets/f668b93f-4f63-45fb-9971-a7a2e8cb0008" />
<img width="1406" height="548" alt="image" src="https://github.com/user-attachments/assets/fb65b5be-bd0f-4d26-8757-36f1ef730f82" />
<img width="1505" height="220" alt="image" src="https://github.com/user-attachments/assets/e1ccfe50-80f6-43cb-8250-a6e8eb68bbb8" />
<img width="1503" height="193" alt="image" src="https://github.com/user-attachments/assets/3dfe52d5-9a75-4468-92fd-0026294ba36e" />
<img width="1919" height="1018" alt="image" src="https://github.com/user-attachments/assets/e3c950ee-970a-4084-9e67-a6821a3e1ca0" />
<img width="1919" height="1025" alt="image" src="https://github.com/user-attachments/assets/8a828e0a-bc0c-44af-8fd0-31f0b69fbcab" />

### UP/DOWN COUNTER - 2
<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/b77e80ee-0fb3-4d22-9739-67eba4404938" />
<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/33af3e56-e77a-4a10-a0ab-68f845fb3fac" />
<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/72dd043d-ec7b-4fc3-9f73-5656c1a5475a" />




### Results:
The ladder logic programs for Up Counter (CTU), Down Counter (CTD), and Up/Down Counter (CTUD) were successfully implemented and tested. The outputs behaved as expected, indicating correct counting operations. The experiment demonstrated how counters are essential in automation for counting events and managing process sequences.
