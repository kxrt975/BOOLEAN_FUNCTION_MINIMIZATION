# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:** 

 /* Program to implement the given logic function and to verify its operations in quartus
 using Verilog programming

 Function 1:
 module funct1(a,b,c,d,f1);
 input a,b,c,d;
 output f1;
 assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
 endmodule

  Function 2:
 module funct2(w,x,y,z,f2);
 input w,x,y,z;
 output f2;
 assign f2=((~y & z)|( w & y )|(x & y));
 endmodule



Developed by:R. karthik padmanaban 
RegisterNumber:24001743

**TRUTH TABLE**

![Screenshot 2024-12-09 092932](https://github.com/user-attachments/assets/fcf85273-7256-47a7-b908-daba01b07cac)


![Screenshot 2024-12-09 093019](https://github.com/user-attachments/assets/72956c3b-1996-435b-be34-9d2e8b01a2d2)



**RTL**

![WhatsApp Image 2024-12-03 at 13 27 53_c694e13a](https://github.com/user-attachments/assets/291e09fa-db51-4283-a416-d933d442c0fd)


![Screenshot 2024-12-09 093118](https://github.com/user-attachments/assets/555dfda0-7c0b-40ea-b561-4716f38d9a5e)


**Output:**

![Screenshot 2024-12-09 093214](https://github.com/user-attachments/assets/db7f69a7-ab76-43a2-baec-876424baf390)


![Screenshot 2024-12-09 093258](https://github.com/user-attachments/assets/75567638-3915-4fdc-b6a7-dcfad0a53e57)


**Timing Diagram**

![Screenshot 2024-12-09 093558](https://github.com/user-attachments/assets/72a4209f-056a-437c-8467-898b6423de27)


![Screenshot 2024-12-09 093625](https://github.com/user-attachments/assets/b7ff5ad2-06ce-4089-a6f8-896d49c61a39)


**Result:**
 Thus the given logic functions are implemented using and their operations are verified using verilog programming.

