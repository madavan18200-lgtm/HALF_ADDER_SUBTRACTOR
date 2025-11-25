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
<img width="752" height="412" alt="Screenshot 2025-11-25 221300" src="https://github.com/user-attachments/assets/85e1fafe-4576-4f7e-be93-106f7b077832" />

<img width="927" height="376" alt="Screenshot 2025-11-25 221525" src="https://github.com/user-attachments/assets/a4a558e8-d718-4e58-9085-6a7c5a56ca7c" />


Developed by:MADAVAN V RegisterNumber:25018573*/

**RTL Schematic**
<img width="1661" height="871" alt="Screenshot 2025-11-25 221230" src="https://github.com/user-attachments/assets/baea8f4a-e70b-4439-8430-22c6e186c990" />
<img width="1417" height="794" alt="Screenshot 2025-11-25 221510" src="https://github.com/user-attachments/assets/f931bd81-af94-4ced-8dcb-c26e53a67e08" />

**Output/TIMING Waveform**
<img width="1125" height="634" alt="Screenshot 2025-11-25 221901" src="https://github.com/user-attachments/assets/1f5909d7-5772-4694-a28d-00bddc5a5fb0" />
<img width="1119" height="664" alt="Screenshot 2025-11-25 221929" src="https://github.com/user-attachments/assets/a0e3f96a-abb6-440e-925c-6385230e06aa" />

**Result:**
The code is successfully verified
