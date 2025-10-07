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
module BOOLEAN (
    input A,
    input B,
    output F
);

assign F = A | B;

endmodule


/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

DevelopedY by :dhanadevan
RegisterNumber:25013996


**RTL realization**
<img width="585" height="366" alt="image" src="https://github.com/user-attachments/assets/84667a47-7239-4fa8-a53a-d971b3ad8086" />


**Output:**

**RTL**
<img width="1312" height="479" alt="image" src="https://github.com/user-attachments/assets/a04d995b-bef1-4d7a-9290-8b9a24283fce" />


**Timing Diagram**

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

