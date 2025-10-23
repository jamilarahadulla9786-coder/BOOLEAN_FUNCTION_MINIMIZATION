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


**Program:**F(A,B,C,D)=AB+CD+AD

module boolean_function_4var (
    input  wire A,
    input  wire B,
    input  wire C,
    input  wire D,
    output wire F
);

assign F = (~A & B) | (C & D) | (A & ~D);

endmodule


/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by:ABDUL RAHMAN A R
RegisterNumber:*/25008775


**RTL realization**
<img width="1032" height="844" alt="Screenshot 2025-10-23 192058" src="https://github.com/user-attachments/assets/97bfa1b3-01be-4163-9146-c52582a6c9e7" />

**Output:**<img width="560" height="830" alt="Screenshot 2025-10-23 192205" src="https://github.com/user-attachments/assets/24110fac-afb0-4d5f-9e4a-8fb1b4580e93" />


**RTL**<img width="1061" height="264" alt="Screenshot 2025-10-23 192221" src="https://github.com/user-attachments/assets/7b3ddbae-114c-4d20-bd1d-3349b8b13d1b" />


**Timing Diagram**

**Result:** Thus the given logic functions are implemented using and their operations are verified using Verilog programming



