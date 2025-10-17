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
![WhatsApp Image 2025-10-17 at 10 51 31_ebb0bdf3](https://github.com/user-attachments/assets/bf8b0e2b-2ca8-4f80-a72b-2c496a248f9d)
![WhatsApp Image 2025-10-17 at 10 51 32_67e0086c](https://github.com/user-attachments/assets/518b182f-3066-4b68-a1e7-74da05f92eda)

**Output:**

**RTL**

**Timing Diagram**
![WhatsApp Image 2025-10-17 at 10 51 32_fd374279](https://github.com/user-attachments/assets/da18a7c4-21b4-4127-9ae6-594e988e30b6)
****![WhatsApp Image 2025-10-17 at 10 51 32_5cc551af](https://github.com/user-attachments/assets/22ff2f38-48ec-4ae7-9155-bb8511bcbb03)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

