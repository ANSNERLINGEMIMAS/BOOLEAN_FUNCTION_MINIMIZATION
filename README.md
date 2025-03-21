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

![WhatsApp Image 2025-03-21 at 18 22 07_91b95df7](https://github.com/user-attachments/assets/bbe236e5-5d30-43dd-a031-7f2f47f99492)


**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by:ANS NERLING EMIMA S RegisterNumber:*/212224040027

```

module exp2a(a,b,c,d,F1);
intput a,b,c,d;
output F1;
assign F1=((~b&~d)|(~a&b&d)|(a&b&~c));
endmodule

module exp2b(w,x,y,z,F2)
intput w,x,y,z;
output F2;
assign F2=((~y&z)|(x&y)|(w&y));
endmodule
```


**RTL realization**

**Output:**

**RTL**

exp2a
![exp2a](https://github.com/user-attachments/assets/b4f7f2e5-3f25-4cf7-a6ab-2e455c4d7bfc)

exp2b
![exp2b](https://github.com/user-attachments/assets/2ca41845-69f3-4a6c-8375-43bd666b8d12)



**Timing Diagram**

exp2a
![Screenshot 2025-03-17 142308](https://github.com/user-attachments/assets/b696a9aa-6e0f-4ea0-ae05-1d673e1fbe73)

exp2b
![Screenshot 2025-03-17 142449](https://github.com/user-attachments/assets/6419a8e2-13bc-491d-b348-b19f3a3301e8)



**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

