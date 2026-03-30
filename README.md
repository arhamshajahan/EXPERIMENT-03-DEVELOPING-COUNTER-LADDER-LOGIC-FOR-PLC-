# EXPERIMENT-03-DEVELOPING-COUNTER-LADDER-LOGIC-FOR-PLC-
## NAME: ARHAM S
## REGISTER NUMBER: 212222110005
## DEPARTMENT: CSE(IOT)
## YEAR: IV 

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

### COUNTER:

<img width="1919" height="1079" alt="553314653-b03ea7f0-f243-4e2a-a90f-46a4b765919a" src="https://github.com/user-attachments/assets/0e828a6a-59de-4779-b5f6-2c3d3b3ac03c" />
<img width="1919" height="1079" alt="553314668-86b610c4-ee71-4878-86e3-28c64b3b0158" src="https://github.com/user-attachments/assets/088d1555-d895-47b4-b233-d85c00c09681" />


### UP COUNTER (CTU):

<img width="1347" height="765" alt="553314800-1704c8a0-1bc7-41f9-a14b-2476af12fb58" src="https://github.com/user-attachments/assets/2f07eedd-a2a5-4648-ba04-570d0c95703f" />
<img width="1890" height="1031" alt="553314821-cddc842f-daa7-424e-a4c7-b8cede05b274" src="https://github.com/user-attachments/assets/9260b92b-5f3b-44e5-a79b-5ebdf187a311" />

### DOWN COUNTER(CTD):

<img width="1003" height="533" alt="553315512-519ab101-ecdd-4e97-81f0-6866e3102b25" src="https://github.com/user-attachments/assets/5d5f897a-18eb-4177-b287-69bee2e4a94e" />
<img width="1019" height="437" alt="553314979-b7cacb03-f157-4fab-9308-dc1450f91b90" src="https://github.com/user-attachments/assets/4f4f2d39-9b46-4098-b035-97f884aeeb19" />
<img width="1915" height="1032" alt="553315014-fc2814d6-a91e-4f08-bdf0-4a59a99dea58" src="https://github.com/user-attachments/assets/84367685-77e2-4f77-9a22-e032f209129a" />

###  UP DOWN(CTUD):

<img width="1224" height="547" alt="553315112-49c17292-4b84-46eb-8ab6-d5977e55dcde" src="https://github.com/user-attachments/assets/f9d68360-1719-4271-8345-bd5b0efcd750" />
<img width="1219" height="496" alt="553315120-9ca99f49-8563-4a59-bee6-e2da22e038c4" src="https://github.com/user-attachments/assets/34250298-fc4b-47f9-a45a-1367d743d8cd" />
<img width="1917" height="1033" alt="553315126-2443d4ed-5d4d-47a1-9d9f-18ead504399d" src="https://github.com/user-attachments/assets/9da6404e-ed55-4769-b565-eaa9abf2ba2c" />
<img width="1919" height="1032" alt="553315133-c4fc3da3-eae5-44ce-9a77-bb488ea151f6" src="https://github.com/user-attachments/assets/48e21746-6e16-4b67-bcf9-b4f9048fab0a" />


### Results:
The ladder logic programs for Up Counter (CTU), Down Counter (CTD), and Up/Down Counter (CTUD) were successfully implemented and tested. The outputs behaved as expected, indicating correct counting operations. The experiment demonstrated how counters are essential in automation for counting events and managing process sequences.
