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
module experiment2(a,b,c,d,f1,w,x,y,z,f2);
input a,b,c,d,w,x,y,z;
output f1,f2;
assign f1=((~b&~c)|(~a&b&d)|(a&b&~c));
assign f2=((~y&z)|(x&y)|(w&y));
endmodule

/*

Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by:sudhindra.R

RegisterNumber:24901168

*/


**RTL realization**
![Screenshot 2024-11-24 151754](https://github.com/user-attachments/assets/fcbd1d1f-f0c1-4984-b3c2-af72421c8636)


**Output:**


**RTL**
![Screenshot 2024-11-24 152503](https://github.com/user-attachments/assets/784edf15-3765-43db-92a3-f933ad093261)



**Timing Diagram**

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

