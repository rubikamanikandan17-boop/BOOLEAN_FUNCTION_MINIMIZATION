# BOOLEAN_FUNCTION_MINIMIZATION

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
i)
module funct1(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule

ii)
module funct2(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y & z)|( w & y )|(x & y));
endmodule

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by: RegisterNumber:*/


**RTL realization**
![WhatsApp Image 2025-10-17 at 10 51 31_0f535796](https://github.com/user-attachments/assets/a61206d5-cdbe-4027-bd3c-38bfeab9d80b)
![WhatsApp Image 2025-10-17 at 10 51 32_575ab104](https://github.com/user-attachments/assets/fbe28d66-e7af-43ed-bea1-0c9d2210cea9)

**Output:**

**RTL**

**Timing Diagram**
![WhatsApp Image 2025-10-17 at 10 51 32_f90d9534](https://github.com/user-attachments/assets/5b9d6025-acd2-4d6a-802e-30910d1123b3)
![WhatsApp Image 2025-10-17 at 10 51 32_46a20c0e](https://github.com/user-attachments/assets/19e6064d-b0c5-41f9-9684-226aaebbb1ab)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

