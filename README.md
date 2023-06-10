# Experiment--02-Implementation-of-combinational-logic
Implementation of combinational logic gates
 
## AIM:
To implement the given logic function verify its operation in Quartus using Verilog programming.
 F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D
F2=xy’z+x’y’z+w’xy+wx’y+wxy
 
 
 
## Equipments Required:
## Hardware – PCs, Cyclone II , USB flasher
## Software – Quartus prime


## Theory
 

## Logic Diagram
## Procedure
step-1
Create a project with required entities.

step-2
Create a module along with respective file name.

step-3
Run the respective programs for the given boolean equations.

step-4
Run the module and get the respective RTL outputs.

step-5
Create university program(VWF) for getting timing diagram.

6.Give the respective inputs for timing diagram and obtain the results.
## Program:
```
Program to implement the given logic function and to verify its operations in quartus using Verilog programming.
Developed by: SRIRAM S
RegisterNumber: 212222240105
```
## F1:
```
module dd (a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1 = (~b&~d)|(~a&b&d)|(a&b&~c);
endmodule 
```
## F2:
```
module dd (w,x,,y,z,f2);
input w,x,y,z;
output f2;
assign f2 = (w&y)|(x&y)|(~y&z);
endmodule
```
## Output:
## F1:
## RTL realization
![image](https://github.com/SriramS22/Experiment--02-Implementation-of-combinational-logic-/assets/119094390/467357f4-517c-4617-9dba-46c89ae11392)

## Timing Diagram
https://user-images.githubusercontent.com/93427254/243377392-b09e5fea-aa3b-4ee3-903f-f4d06b30c353.png

## F2:
## RTL realization
https://user-images.githubusercontent.com/93427254/243377377-ac278eda-5a27-4658-a1ff-7bba9f8decf9.png

## Timing Diagram
https://user-images.githubusercontent.com/93427254/243377418-ab8302e6-9378-4200-8d04-914b9b312f1f.png

## Result:
Thus the given logic functions are implemented using  and their operations are verified using Verilog programming.
