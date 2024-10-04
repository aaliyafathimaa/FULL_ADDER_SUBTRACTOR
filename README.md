# FULL_ADDER_SUBTRACTOR

Implementation-of-Full-Adder-and-Full-subtractor-circuit

**AIM:**

To design a Full Adder and Full Subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime

**Full Adder and Full Subtractor**

**Full Adder**

Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin 

Carry = AB + ACin + BCin

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/0f30ba51-5ffb-4198-845f-18e054f675e7)

**Figure -1 FULL ADDER**

**Full Subtractor**

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/02b24f51-ab51-4304-9ad6-7b81ffc1ead5)

Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

**Truthtable**

**Procedure**

Write the detailed procedure here

**Program:**

/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.
Developed by:Aaliya Fathima RegisterNumber: 212223230001
*/

![Screenshot 2024-09-27 140959](https://github.com/user-attachments/assets/c8386ae1-5e0f-417d-9655-78382dd321d4)


![Screenshot 2024-09-27 142531](https://github.com/user-attachments/assets/ade50b78-0eb9-4c1b-a358-d683dfbc8908)


**RTL Schematic**

![Screenshot 2024-09-27 141521](https://github.com/user-attachments/assets/444be6ad-6400-498a-8654-16b2ce2ca796)


![Screenshot 2024-09-27 142551](https://github.com/user-attachments/assets/fb1edcd8-73e9-4dd7-b0e7-b23bc0b171f9)



**Output Timing Waveform**

![Screenshot 2024-09-27 141428](https://github.com/user-attachments/assets/43563bb5-0c82-4d73-8a84-7fd196255b35)


![Screenshot 2024-09-27 142502](https://github.com/user-attachments/assets/49d1d4f6-3a21-45db-ab6c-5cd050db94d8)



**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



