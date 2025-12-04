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
```
module BOOLEAN (
    input A,
    input B,
    output F
);

assign F = A | B;

endmodule
```


Program to implement the given logic function and to verify its operations in quartus using Verilog programming

**Developed by:** Jeeva Nivas M 
**RegisterNumber:** 25015894 


**RTL realization**
<img width="1019" height="395" alt="Screenshot 2025-12-04 192032" src="https://github.com/user-attachments/assets/f38ed69e-e93d-4079-9027-b344de0c3442" />


**Output:**

**RTL**

**Timing Diagram**
<img width="1058" height="412" alt="image" src="https://github.com/user-attachments/assets/4c5d571e-2e3b-40f8-89b4-de9d9551fbe5" />


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

