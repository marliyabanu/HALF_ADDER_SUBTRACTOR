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
Half adder
/* Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
<img width="551" height="367" alt="image" src="https://github.com/user-attachments/assets/4ba670fc-3272-44ea-8b45-8e7664a4ae64" />

Half subtractor 
/* Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
<img width="575" height="335" alt="image" src="https://github.com/user-attachments/assets/a83cdf98-978b-4d1f-8bb6-cf1cc43a0ee5" />


Developed by:B MARLIYA BANU
RegisterNumber: 25004270

**RTL Schematic**
Half adder
<img width="1015" height="795" alt="image" src="https://github.com/user-attachments/assets/44d7f213-1b3a-4215-968e-e11de82bc28f" />
Half subtractor
<img width="1013" height="772" alt="image" src="https://github.com/user-attachments/assets/b1983ee1-a5a0-469d-9483-6b1bb329bc68" />




**Output/TIMING Waveform**
Half adder
<img width="1321" height="235" alt="image" src="https://github.com/user-attachments/assets/8cb87cd3-6e59-40a2-82f5-b8c162928876" />


Half subtractor
<img width="1318" height="293" alt="image" src="https://github.com/user-attachments/assets/d814b396-bb36-4162-820b-1ad8fbfd3934" />


**Result:**
Thus the a half adder and half subtractor circuit is designed and its truth table is verified in Quartus using Verilog programming .
