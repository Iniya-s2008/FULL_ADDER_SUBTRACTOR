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

/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. Developed by: RegisterNumber:
*/

**RTL Schematic**

**Output Timing Waveform**

**Result:**
logic diagram for full adder:
<img width="694" height="345" alt="Screenshot 2025-10-07 171222" src="https://github.com/user-attachments/assets/cde2d1d0-7970-4f54-8015-90e38a59e242" />
state diagram for full adder:
<img width="1915" height="261" alt="Screenshot 2025-10-07 171828" src="https://github.com/user-attachments/assets/992eb1b8-a77e-4a41-b38a-cc28d38a7b77" />
logic diagram for full subtractor:
<img width="863" height="433" alt="Screenshot 2025-10-07 173255" src="https://github.com/user-attachments/assets/bb7f4ff0-6b13-42f0-9449-c63eb1cd0137" />
state diagram for full subtractor:
<img width="1916" height="235" alt="Screenshot 2025-10-07 173508" src="https://github.com/user-attachments/assets/860b0c93-9ff7-4683-b33d-4f5097eefdbf" />




Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



