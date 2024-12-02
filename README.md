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
Developed by: Rhudhra phriyamvadha K S
RegisterNumber: 24900189
```
```
module boolean(a,b,c,d,f1);
 input a,b,c,d;
 output f1;
 assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
 endmodule
```

**RTL realization**

**Output:**

![Screenshot 2024-12-02 225553](https://github.com/user-attachments/assets/208f3b40-b2a4-4874-8866-760f12f21426)

![Screenshot 2024-12-02 225612](https://github.com/user-attachments/assets/a578695b-d2cf-4da5-947e-b45693d7d15d)


**RTL**

![Screenshot 2024-12-02 225209](https://github.com/user-attachments/assets/02b615b8-d7d4-4d1f-a72d-56e29b13704b)

**Timing Diagram**
![Screenshot 2024-12-02 230931](https://github.com/user-attachments/assets/17ee579b-d396-45a2-b60e-f2e20553b85f)


**Result:**

Thus, the given logic functions are implemented using and their operations are verified using Verilog programming.

