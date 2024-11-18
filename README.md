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

![{B9D3EDDB-9D50-4C7F-AE40-AC247DCA74D4}](https://github.com/user-attachments/assets/b48468ae-97d3-4c1c-b199-0e090a1a54ef)


![{049C85E3-9EAE-41D4-AD13-047DA0FF45D1}](https://github.com/user-attachments/assets/63b7ca18-0ffd-47b8-bb33-a3e91cc5e760)


**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.



**Program:**

/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.

![{8F397CD2-F21F-4DC1-872F-70331AEC71BE}](https://github.com/user-attachments/assets/c87f10d5-c217-47d9-bdfe-148eea78ceeb)

![{39A53D25-82A1-4892-B6A7-6EDD3CBE845D}](https://github.com/user-attachments/assets/1b3136dc-187f-42d6-8d59-86466608d155)



Developed by:Charithrakshi K RegisterNumber:24900651
*/

**RTL Schematic**

![{0576E9AA-0B4E-4FF7-B47B-29838593E611}](https://github.com/user-attachments/assets/88450d75-ed4d-4b4e-bf7a-b6969f5f43d3)

![{8EDC0EFA-0B7F-498B-8B5F-9414E5698F45}](https://github.com/user-attachments/assets/3eb6bd65-6708-4b19-93e9-9d812f9394b8)


**Output Timing Waveform**

![{B4C10A14-859E-456B-8BEB-EDE0A6DDA849}](https://github.com/user-attachments/assets/cd7d4453-4cc5-47bf-b8a9-30634a4f0a35)

![Screenshot 2024-11-17 174422](https://github.com/user-attachments/assets/243332bb-d166-464a-9566-f3f0587e3b7a)


**Result:**


Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



