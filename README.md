# HALF_ADDER_SUBTRACTOR

Implementation-of-Half-Adder-and-Half Subtractor-circuit

**AIM:**

To design a half adder and half subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher 

Software – Quartus prime Theory Adders are digital circuits that carry out the addition of numbers.

**Half Adder**

Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/bd4a0b2c-cdbc-4184-ab08-81578f121e1f)

Figure -01 HALF ADDER

**Half Subtractor**

The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed. 

Diff = A’B+AB’ =A ⊕ B
Borrow = A’B

 ![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/d76b099c-513f-4e7c-843a-e2fd028a531a)

Figure -02 HALF Subtractor

**Truthtable**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

<img width="626" height="465" alt="Screenshot 2025-12-10 134111" src="https://github.com/user-attachments/assets/68754415-f9f4-46d8-b587-3a2728598cdd" />



<img width="894" height="407" alt="Screenshot 2025-12-10 134213" src="https://github.com/user-attachments/assets/d4624899-7014-4bfd-bfe7-f9cc418000fa" />


DEVELOPED BY: SWETHA K
REGISTER NO:25014909


**RTL Schematic**
<img width="1099" height="607" alt="Screenshot 2025-12-10 134237" src="https://github.com/user-attachments/assets/4ea6d2a0-277d-403e-907c-197fe4b8f139" />


<img width="1087" height="582" alt="Screenshot 2025-12-10 134255" src="https://github.com/user-attachments/assets/303b6b0b-ccc1-49c1-8840-6328abadaf36" />



**Output/TIMING Waveform**
<img width="1879" height="868" alt="Screenshot 2025-12-10 134329" src="https://github.com/user-attachments/assets/142723cf-4b5d-44a7-896f-cb479957a278" />


<img width="1895" height="330" alt="Screenshot 2025-12-10 134427" src="https://github.com/user-attachments/assets/2e8ac2af-ad85-414c-b88b-cc3a447b2475" />


**Result:**
thus the given design implemented and verified using truth table
