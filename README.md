<img width="1917" height="1076" alt="Screenshot 2025-10-08 210008" src="https://github.com/user-attachments/assets/522f1371-8a95-4325-882f-a4859a2e32e4" /># BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**

**Logic Diagram**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

module exp2(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule


/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by: SANJEEV KUMAR V

RegisterNumber: 25018993


**RTL realization**

<img width="1917" height="1076" alt="Screenshot 2025-10-08 210008" src="https://github.com/user-attachments/assets/2b7eff2e-7a9a-4e06-a616-f87accad59ce" />

**Output:**

**RTL**

<img width="1919" height="1069" alt="Screenshot 2025-10-08 210319" src="https://github.com/user-attachments/assets/2a6007d5-4a44-4529-9596-c985da1ecfe1" />

**Timing Diagram**

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

