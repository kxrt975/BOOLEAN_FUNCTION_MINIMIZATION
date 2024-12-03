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

![WhatsApp Image 2024-12-03 at 13 27 53_c694e13a](https://github.com/user-attachments/assets/9368133c-c256-48cd-ad74-ab4a1c3334a1)



**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:** 
Developed by:R. karthik padmanaban 
RegisterNumber:24001743

![WhatsApp Image 2024-12-03 at 13 27 48_e7496efc](https://github.com/user-attachments/assets/5d5e5867-9198-48a3-a675-e04ea8f286e2)


**RTL realization**

![WhatsApp Image 2024-12-03 at 13 27 53_c694e13a](https://github.com/user-attachments/assets/291e09fa-db51-4283-a416-d933d442c0fd)


**Output:**

**RTL**

**Timing Diagram** a b c d ~b ~d ~a ~c (~b & ~d) (~a & b & d) (a & b & ~c) f1 (final result) 0 0 0 0 1
 1 1 1 1 0 0 1 0 0 0 1 1 0 1 1 0 0 0 0 0 0 1 0 1 1 1 0 1 0 0 1 0 0 1 1 1 0 1 0 0 0 0 0 0 1 0 0 0 1 1 1 0 0 1
 1 0 1 0 1 0 0 1 1 0 1 0 1 0 1 1 0 0 1 1 0 0 0 0 0 0 1 1 1 0 0 1 0 0 1 0 1 1 0 0 0 1 1 0 1 1 0 0 1 1 0 0 1 1
 0 0 1 0 0 0 0 1 0 1 0 1 1 0 0 1 0 0 1 1 0 1 1 1 0 0 0 0 0 0 0 1 1 0 0 0 1 0 1 0 1 1 1 1 1 0 1 0 0 0 1 0 1 0
1 1 1 1 0 0 1 0 0 0 0 0 0 1 1 1 1 0 0 0 0 0 1 0 1

![Screenshot 2024-12-03 135711](https://github.com/user-attachments/assets/2f5375d0-7752-40c7-9083-29796b27fbeb)



**Result:**
 Thus the given logic functions are implemented using and their operations are verified using verilog programming.

