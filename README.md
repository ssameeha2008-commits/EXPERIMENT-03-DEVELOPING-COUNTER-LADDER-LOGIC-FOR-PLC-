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
Up Counter (CTU): The output LED or indicator should activate when the preset count (e.g., 10) is reached.
<img width="1153" height="611" alt="image" src="https://github.com/user-attachments/assets/4767e796-0d4c-4ab0-9cf4-eeae5f0a7e02" />
<img width="1041" height="556" alt="image" src="https://github.com/user-attachments/assets/9cceab97-5dc7-43ff-8433-b9f36c7f761e" />
<img width="1033" height="555" alt="image" src="https://github.com/user-attachments/assets/9fab60f2-2972-4e73-91a6-e2f5f9ce42dc" />


Down Counter (CTD): The output should activate when the count reaches zero.
<img width="1033" height="563" alt="image" src="https://github.com/user-attachments/assets/89ed77b1-f896-4969-a871-f0b3ea2a83e5" />
<img width="1040" height="535" alt="image" src="https://github.com/user-attachments/assets/a9deb273-602b-4b56-9786-1ca7b6cb0a99" />
<img width="1042" height="547" alt="image" src="https://github.com/user-attachments/assets/a74ab186-b063-43a1-a0c4-fd7a27f3bb66" />
<img width="1035" height="557" alt="image" src="https://github.com/user-attachments/assets/27a791a2-f200-4137-b499-7d6f7127b33f" />
<img width="1037" height="553" alt="image" src="https://github.com/user-attachments/assets/1c3d51a3-a639-4db9-ada3-3a34727dcef1" />


Up/Down Counter (CTUD): The output should activate when the count reaches the preset value or zero, depending on the inputs.
<img width="1040" height="552" alt="image" src="https://github.com/user-attachments/assets/c4a39781-f37c-4714-be33-1ad6268abbf5" />
<img width="1037" height="548" alt="image" src="https://github.com/user-attachments/assets/d95f2baa-7615-4634-a6bd-6a12f56cf98b" />
<img width="1032" height="552" alt="image" src="https://github.com/user-attachments/assets/fbe434be-7885-4565-8325-393450497ea7" />
<img width="1038" height="548" alt="image" src="https://github.com/user-attachments/assets/f4c9ebe4-3497-4c4c-b0f7-2f11ac35401b" />
<img width="1037" height="552" alt="image" src="https://github.com/user-attachments/assets/111519af-3efd-407a-b772-d4da5e5d8613" />
<img width="1036" height="556" alt="image" src="https://github.com/user-attachments/assets/6a5c33d0-2487-4b0f-8083-2e2245477907" />
<img width="1038" height="558" alt="image" src="https://github.com/user-attachments/assets/54e13043-9942-4b03-9988-15225e9ae5dc" />
<img width="1037" height="552" alt="image" src="https://github.com/user-attachments/assets/48007f95-a297-486c-9a9d-bb036c7663a2" />



### Results:
The ladder logic programs for Up Counter (CTU), Down Counter (CTD), and Up/Down Counter (CTUD) were successfully implemented and tested. The outputs behaved as expected, indicating correct counting operations. The experiment demonstrated how counters are essential in automation for counting events and managing process sequences.
