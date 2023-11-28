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
Logic gates are electronic circuits which perform logical functions on one or more inputs to
produce one output.
Logic gates are electronic circuits which perform logical functions on one or more inputs to
produce one output. F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D F2=xy’z+x’y’z+w’xy+wx’y+wxy
1.AND gate The AND gate is an electronic circuit that gives a high output (1) only if all its inputs are
high. A dot (.) is used to show the AND operation i.e. A.B or can be written as AB Y= A.B
2.OR gate The OR gate is an electronic circuit that gives a high output (1) if one or more of its
inputs are high. A plus (+) is used to show the OR operation. Y= A+B
 
## Procedure:
1.Create a project with required entities.
2.Create a module along with respective file name.
3.Run the respective programs for the given boolean equations.
4.Run the module and get the respective RTL outputs.
5.Create university program(VWF) for getting timing diagram.
6.Give the respective inputs for timing diagram and obtain the results.
## Program:
/*
Program to implement the given logic function and to verify its operations in quartus using Verilog programming.
Developed by: SONU S
RegisterNumber: 23005566
*/
## RTL realization

## CODE:
### F1:
![Exp2codei](https://github.com/ssonuma/Experiment--02-Implementation-of-combinational-logic-/assets/150653312/517b1923-c70e-4f89-99b6-fe1ce3686beb)

### F2:
![Exp2codeii](https://github.com/ssonuma/Experiment--02-Implementation-of-combinational-logic-/assets/150653312/cfbaeac1-4b89-4f1d-9eea-50d1d4b5513f)

## RTL:
### F1:
![Exp2 f1](https://github.com/ssonuma/Experiment--02-Implementation-of-combinational-logic-/assets/150653312/1d6f2681-3f64-4e44-8dec-851ffbb63143)

### F2:
![Exp2 f2](https://github.com/ssonuma/Experiment--02-Implementation-of-combinational-logic-/assets/150653312/86325d14-1cf2-49d0-9582-e5755a38bc9e)

## OUTPUT:
## Timing Diagram
### F1:
![Exp2 f1 timing](https://github.com/ssonuma/Experiment--02-Implementation-of-combinational-logic-/assets/150653312/7aeffc7d-994c-4302-a133-e15338195afe)

### F2:
![Exp2 f2 timing](https://github.com/ssonuma/Experiment--02-Implementation-of-combinational-logic-/assets/150653312/a33e9a43-a054-445b-98d7-56baa6121e8a)

## Result:
Thus the given logic functions are implemented using  and their operations are verified using Verilog programming.
