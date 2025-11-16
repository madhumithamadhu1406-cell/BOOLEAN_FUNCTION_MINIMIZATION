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

F(A,B,C,D)=AB+CD+AD

module boolean_function_4var (
    input  wire A,
    input  wire B,
    input  wire C,
    input  wire D,
    output wire F
);

assign F = (~A & B) | (C & D) | (A & ~D);

endmodule

Developed by:Madhumitha V
RegisterNumber:25016067


**RTL realization**

**Output:**

<img width="1919" height="1076" alt="Screenshot 2025-11-16 103434" src="https://github.com/user-attachments/assets/4896cfb2-9041-4793-91c1-1778988279bd" />

**RTL**

<img width="1919" height="1072" alt="Screenshot 2025-11-16 102934" src="https://github.com/user-attachments/assets/e760fd98-3720-4984-8479-906ef1d47f46" />

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

