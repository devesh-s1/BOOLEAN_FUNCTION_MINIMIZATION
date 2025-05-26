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

  FUNCTION 1 K-MAP

  
![Screenshot 2024-12-10 130855](https://github.com/user-attachments/assets/5d6a470f-d6be-4814-928f-37a8f74b3398)

   FUNCTION 2 K-MAP
![Screenshot 2024-12-10 130904](https://github.com/user-attachments/assets/077cec70-24ae-4dcc-b0f6-45b9716f8ae7)



**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 
```
FUNCTION 1

i)
module funct1(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule


FUNCTION 2


ii)
module funct2(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y & z)|( w & y )|(x & y));
endmodule
```

   FUNCTION 1


![Screenshot 2024-12-10 130914](https://github.com/user-attachments/assets/d5357ef7-67bb-41e1-bfbf-23ae66e6dffc)

   FUNCTION 2

![Screenshot 2024-12-10 130921](https://github.com/user-attachments/assets/a53eabae-02ca-4be4-bca1-1e3a29b0187c)


Developed by: DEVESH SHARMA S


RegisterNumber:212222110008


**RTL realization**

**Output:**

**RTL**

   FUNCTION 1


![Screenshot 2024-12-10 130928](https://github.com/user-attachments/assets/b4e996bf-d92d-4180-8221-eeef67884cd0)

   FUNCTION 2


![Screenshot 2024-12-10 130935](https://github.com/user-attachments/assets/8e4bfdec-b657-47f5-bf3f-989f5ee42813)



**Timing Diagram**

   FUNCTION 1

![Screenshot 2024-12-10 130944](https://github.com/user-attachments/assets/bbde9f23-db1f-4530-86e6-ea08c2454349)


   FUNCTION 2

![Screenshot 2024-12-10 143619](https://github.com/user-attachments/assets/a9804bf4-5da4-4fba-8332-59aca9d6e562)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

