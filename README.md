 #  EX: 1 EXECUTION-OF-LOGIC-GATES-USING-PLC-LADDER-PROGRAM
 
 ## DATE:
 ## NAME :SWETHA N
 ## REGISTER NUMBER: 212222110050

# Aim:
To implement and verify the functioning of basic logic gates (AND, OR, NOT, NAND, NOR, XOR) using a PLC ladder program and simulate the outputs.

# Apparatus Required:
Programmable Logic Controller (PLC) - A PLC with support for ladder logic programming.

PLC Programming Software - Software like RSLogix, TIA Portal, or CX-Programmer.

Computer System - To run the PLC programming software and perform simulations.

Input Devices - Push buttons or switches to simulate inputs (I/O modules).

Output Devices - LEDs or any indicator to visualize the output of logic gates (I/O modules).

Wires and Connectors - For connecting input/output devices to the PLC.

Power Supply - Appropriate power supply for PLC and peripherals.


# Theory:
Logic gates are the fundamental building blocks of digital circuits, and they process binary inputs to produce a binary output. In PLC programming, these logic gates can be implemented using ladder logic, which is a graphical programming language resembling electrical relay logic.

# Basic Logic Gates:
AND Gate:

Function: Outputs HIGH only when all inputs are HIGH.
Ladder Logic: Represented by two or more normally open contacts in series.
OR Gate:

Function: Outputs HIGH when at least one input is HIGH.
Ladder Logic: Represented by two or more normally open contacts in parallel.
NOT Gate:

Function: Outputs the inverse of the input signal.
Ladder Logic: Represented by a normally closed contact.
NAND Gate:

Function: Outputs LOW only when all inputs are HIGH.
Ladder Logic: An AND gate followed by a NOT gate.
NOR Gate:

Function: Outputs LOW when at least one input is HIGH.
Ladder Logic: An OR gate followed by a NOT gate.
XOR Gate:

Function: Outputs HIGH when an odd number of inputs are HIGH.
Ladder Logic: Represented by a combination of AND, OR, and NOT gates.
# Truth Tables:


**AND Gate:**

| Input A | Input B | Output |
|---------|---------|--------|
|   0     |   0     |   0    |
|   0     |   1     |   0    |
|   1     |   0     |   0    |
|   1     |   1     |   1    |

**OR Gate:**

| Input A | Input B | Output |
|---------|---------|--------|
|   0     |   0     |   0    |
|   0     |   1     |   1    |
|   1     |   0     |   1    |
|   1     |   1     |   1    |

**NOT Gate:**
| Input | Output |
|-------|--------|
|   0   |   1    |
|   1   |   0    |

**NAND Gate:**

| Input A | Input B | Output |
|---------|---------|--------|
|   0     |   0     |   1    |
|   0     |   1     |   1    |
|   1     |   0     |   1    |
|   1     |   1     |   0    |


**NOR Gate:**

| Input A | Input B | Output |
|---------|---------|--------|
|   0     |   0     |   1    |
|   0     |   1     |   0    |
|   1     |   0     |   0    |
|   1     |   1     |   0    |

**XOR Gate:**

| Input A | Input B | Output |
|---------|---------|--------|
|   0     |   0     |   0    |
|   0     |   1     |   1    |
|   1     |   0     |   1    |
|   1     |   1     |   0    |
 
# Procedure:
Setup the PLC Programming Environment:

Connect the PLC to the computer system and launch the PLC programming software.
Ensure all input and output devices are correctly connected to the PLC’s I/O modules.
Create Ladder Logic Programs:

For each logic gate, create a ladder logic rung that corresponds to the truth table of the gate.
Use normally open (NO) and normally closed (NC) contacts to implement AND, OR, and NOT logic.
For NAND, NOR, and XOR gates, combine the basic gates appropriately in the ladder diagram.
Simulate the Ladder Logic:

Simulate the ladder logic programs in the PLC software.
Toggle the input states and observe the output corresponding to each gate’s truth table.
# Download and Execute:

If available, download the ladder logic program to the PLC and run it.
Verify the outputs by changing the input states using the connected switches and observing the LEDs or output indicators.
Output of Simulation:
For each logic gate, when the inputs are changed according to the truth tables, the corresponding outputs should be observed as follows:
AND Gate: The output LED or indicator should light up only when both inputs are HIGH.
OR Gate: The output should light up when any one or both inputs are HIGH.
NOT Gate: The output should be the inverse of the input state.
NAND Gate: The output should be HIGH except when both inputs are HIGH.
NOR Gate: The output should be HIGH only when both inputs are LOW.
XOR Gate: The output should light up when exactly one input is HIGH.


# SIMULATION RESULTS 
### AND GATE:
![Screenshot 2025-02-27 185557](https://github.com/user-attachments/assets/dc94f8f9-b1cd-4170-9c03-7139dfb7e2cc)
![Screenshot 2025-02-27 185542](https://github.com/user-attachments/assets/3bd3ffab-0625-430e-bc32-337fb7316457)
![Screenshot 2025-02-27 185527](https://github.com/user-attachments/assets/5c7e72d3-9bd7-45c8-ba6d-d6e3eb038e8c)
![Screenshot 2025-02-27 185510](https://github.com/user-attachments/assets/5deb4b27-20e4-4737-a4f2-213d8937b4a8)

### OR GATE
![Screenshot 2025-02-27 191012](https://github.com/user-attachments/assets/1e55ad84-b812-4bdb-90ff-a505ef10159d)
![Screenshot 2025-02-27 191032](https://github.com/user-attachments/assets/7195415a-7769-4acb-a052-51de3abebcc1)
![Screenshot 2025-02-27 191042](https://github.com/user-attachments/assets/fdaaeab5-17f1-4b3b-8238-6fa1c6a675b9)
![Screenshot 2025-02-27 191132](https://github.com/user-attachments/assets/73f1706c-e076-4eb7-ab2c-e44deacb34c5)

### NOT GATE
![Screenshot 2025-02-27 192652](https://github.com/user-attachments/assets/7713bde7-9a2d-4cb7-b70f-8bdfab22c585)
![Screenshot 2025-02-27 192700](https://github.com/user-attachments/assets/7901bf7f-09bb-4211-b557-f88eaf22297d)

### NAND GATE
![Screenshot 2025-02-27 192355](https://github.com/user-attachments/assets/41708b7b-3d94-4e08-bdd9-1597cb32fe3b)
![Screenshot 2025-02-27 192345](https://github.com/user-attachments/assets/8bffc154-c88d-4a4a-9a1c-5f5fc27bf4ff)
![Screenshot 2025-02-27 192404](https://github.com/user-attachments/assets/57591a46-7c69-4bda-aa2d-096e50beea9f)
![Screenshot 2025-02-27 192415](https://github.com/user-attachments/assets/c6c4b705-3ed6-4e42-8d77-3ed2b4fb2201)

### NOR GATE
![Screenshot 2025-02-27 191949](https://github.com/user-attachments/assets/9ef0dbef-f3f1-4ac1-ada7-7d5fd314fa05)
![Screenshot 2025-02-27 191957](https://github.com/user-attachments/assets/78e535f4-bd07-4e78-a6d9-47fbae5ac89b)
![Screenshot 2025-02-27 192008](https://github.com/user-attachments/assets/7387f28f-b964-43c9-ae64-a153ae778d1d)
![Screenshot 2025-02-27 192048](https://github.com/user-attachments/assets/ad6210b9-c9bb-4000-a940-9894a8326183)

# Results:
The ladder logic programs for each logic gate were successfully implemented and simulated.
The outputs observed matched the expected results as per the truth tables of the respective logic gates.
This experiment demonstrates the effective use of PLCs in executing digital logic operations, which are fundamental to industrial control systems.
