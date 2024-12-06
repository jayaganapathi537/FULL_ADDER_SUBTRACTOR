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

**FULL ADDER**

![319882204-af7159f5-9486-425d-a3d8-cfce9cd84a78](https://github.com/user-attachments/assets/b4dca146-80c0-47e3-bf55-9295d7699a5b)

**FULL SUBTRACTOR**

![319882332-71fd1177-945e-45be-a824-fa5c9f057fec](https://github.com/user-attachments/assets/68e4a649-5dd9-40fe-aa83-157adce92d91)

**Procedure**

Write the detailed procedure here

STEP 1: Use module project name(input,output) to start the Verilog programmming. 

STEP 2: Assign inputs and outputs using the word input and output respectively. 

STEP 3: Use defined keywords like wire,assign and required logic gates to represent the boolean expression.

STEP 4: Use each output to represnt onre for differnce and the other for borrow. 

STEP 5: End the verilog program using keyword endmodule.

**Program:**

Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. 

Developed by: JAYAGANAPATHI S 

RegisterNumber: 24900059

**FULL ADDER**

![Screenshot 2024-12-06 111534](https://github.com/user-attachments/assets/60928ba9-8d4e-4327-b178-9adbc334f4fd)

**FULL SUBTRACTOR**

![Screenshot 2024-12-06 111752](https://github.com/user-attachments/assets/f43f9733-0f00-4eef-94c6-88228d0b7f2e)

**RTL Schematic**

**FULL ADDER**

![319880709-6b5ca9eb-a364-4365-94ad-9acb7b4da922](https://github.com/user-attachments/assets/03c40a28-07fb-4f1a-a20d-36f9e7947ba4)

**FULL SUBTRACTOR**

![319880804-97efa979-764c-410b-b5cf-78b4f8f24300](https://github.com/user-attachments/assets/c65541a9-2352-4ad6-827e-4d77e74947df)


**Output Timing Waveform**

**FULL ADDER**


![Screenshot 2024-12-06 112043](https://github.com/user-attachments/assets/c04d885f-d5a7-47e6-809e-5e0400ba57ce)

**FULL SUBTRACTOR**


![Screenshot 2024-12-06 112058](https://github.com/user-attachments/assets/7a9fed0a-0846-4e67-b73e-485bdff04c3b)

**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



