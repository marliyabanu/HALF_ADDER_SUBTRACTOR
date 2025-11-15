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

/* Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
<img width="651" height="371" alt="image" src="https://github.com/user-attachments/assets/860a459d-c122-4eeb-a6b1-a5cd48e761ea" />
<img width="922" height="345" alt="image" src="https://github.com/user-attachments/assets/0981b1ed-895c-4cd4-98b0-d80c23df8e0c" />


Developed by:B MARLIYA BANU
RegisterNumber: 25004270

**RTL Schematic**
<img width="1021" height="586" alt="image" src="https://github.com/user-attachments/assets/6cb445f5-1c8f-4cff-81b9-a5335262f6a9" />
<img width="1013" height="591" alt="image" src="https://github.com/user-attachments/assets/899c42d6-c2c6-45e1-afbd-40581d87ef32" />


**Output/TIMING Waveform**
<img width="1317" height="276" alt="image" src="https://github.com/user-attachments/assets/ee030a04-959a-42dc-a1d4-39218eb2e4fc" />
<img width="1320" height="218" alt="image" src="https://github.com/user-attachments/assets/0057fdc7-19b4-4296-a3ac-db8a27d0ffb9" />


**Result:**
Thus, the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.
