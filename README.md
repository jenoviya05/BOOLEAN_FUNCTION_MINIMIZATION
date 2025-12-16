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

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by: Jenoviya D
RegisterNumber:  25014196

i) 
  module exp2(a,b,c,d,f1); 
  input a,b,c,d; 
  output f1; 
  assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c)); 
  endmodule 
ii) 
  module exp3(w,x,y,z,f2); 
  input w,x,y,z; 
  output f2; 
  assign f2=((~y & z)|( w & y )|(x & y)); 
  endmodule


**RTL realization**
<img width="1041" height="568" alt="Screenshot 2025-12-16 213827" src="https://github.com/user-attachments/assets/30dbb6e7-9bb9-4bd7-82f3-dff4b57dd591" />

<img width="1030" height="569" alt="Screenshot 2025-12-16 213845" src="https://github.com/user-attachments/assets/5642af7b-465b-4e9f-905d-969894d1746f" />


**Output:**

<img width="1039" height="567" alt="Screenshot 2025-12-16 213955" src="https://github.com/user-attachments/assets/5b06ca07-ada9-4685-8488-6fe55086a258" />
<img width="1040" height="574" alt="Screenshot 2025-12-16 214007" src="https://github.com/user-attachments/assets/63137d99-c495-4176-8998-9c1a1e99ad89" />


**RTL**
<img width="1039" height="571" alt="Screenshot 2025-12-16 214234" src="https://github.com/user-attachments/assets/ffe0b13f-74e0-42c4-9f45-9ae2c2789130" />
<img width="1041" height="576" alt="Screenshot 2025-12-16 214245" src="https://github.com/user-attachments/assets/8af33398-a121-4b70-916b-c5bda73f117b" />



**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

