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

Developed by: Sifiz.A
RegisterNumber:25010152

<img width="571" height="370" alt="Screenshot (70)" src="https://github.com/user-attachments/assets/04ec4a1e-72d0-42a7-8bf2-f48ee860af53" />
<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/5bd8a05f-8740-44ba-b27b-e959a056c952" />


**RTL Schematic**
<img width="1117" height="582" alt="Screenshot (72)" src="https://github.com/user-attachments/assets/340e3a56-5b40-4ab0-8024-58ecdc8ecd1b" />
<img width="1119" height="582" alt="Screenshot (73)" src="https://github.com/user-attachments/assets/6e0d9078-7bd5-442e-b6d0-bc1e33aae5e2" />

**Output/TIMING Waveform**
<img width="1320" height="423" alt="Screenshot (74)" src="https://github.com/user-attachments/assets/11863332-db72-43d7-a6d9-ef917102d5db" />
<img width="1186" height="385" alt="Screenshot (75)" src="https://github.com/user-attachments/assets/05ac8baa-af10-4334-b390-358c06866121" />

**Result:**
