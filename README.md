# BOOLEAN_FUNCTION_MINIMIZATION

Developed by: Praveen S RegisterNumber:212225040314

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
```

MINIMIZATION OF BOOLEAN FUNCTION
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
```

**RTL realization**

<img width="929" height="621" alt="image" src="https://github.com/user-attachments/assets/ef423fe7-9d3d-48fc-8a39-e6b9b16ea419" />

**Output:**

<img width="852" height="558" alt="image" src="https://github.com/user-attachments/assets/32b001f8-928b-4b22-8647-08b8a2f15f2d" />

**RTL**

<img width="1818" height="801" alt="image" src="https://github.com/user-attachments/assets/38e75125-d1f5-4fe4-a9d3-5ccf1cace4fe" />

**Timing Diagram**

<img width="1818" height="801" alt="image" src="https://github.com/user-attachments/assets/ef25ed27-8b25-4162-a957-05c3fcdec064" />

**Result:**
Thus the given logic functions are implemented using and their operations are verified using Verilog programming.


