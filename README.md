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
#Developed By: Pavithra S
#Register No: 212225040298/25017175
module EXPERIMENT2 (
    input A,B,C,D,
	 output F 
);
assign F = (~A & ~B & ~C & ~D) |
           (A & ~C & ~D)       |
           (~B & C & ~D)       |
           (~A & B & C & D)	 |
		     (B & ~C & D);
endmodule
```


**RTL realization**:





**Output:**

**RTL**

**Timing Diagram**

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

