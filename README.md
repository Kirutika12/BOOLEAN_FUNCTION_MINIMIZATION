# BOOLEAN_FUNCTION_MINIMIZATION

## **AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

## **Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

## **Software – Quartus prime**

## **Theory**

## **Logic Diagram**

## **Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


## **Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 
### module funct1(a,b,c,d,f1);
### input a,b,c,d;
### output f1;
### assign f1=((~b&~d)|(~a&b&d)|(a&b&~c));
### endmodule 
### module funct2(w,x,y,z,f2);
### input w,x,y,z;
### output f2;
### assign f2=((~y&z)|(w&y)|(x&y));
### endmodule 
## Developed by: Kirutika KR
## RegisterNumber: 24001080


## **RTL realization**

## **Output:**
### ![Screenshot 2024-12-06 113440](https://github.com/user-attachments/assets/07a8c9a5-c40f-4f2d-96fc-74027ba73a61)
### ![Screenshot 2024-12-06 113609](https://github.com/user-attachments/assets/8d4b749a-1b51-4c5f-b361-672ddeaf4069)

## **RTL**

## **Timing Diagram**
### ![Screenshot 2024-12-06 113919](https://github.com/user-attachments/assets/18c8e01c-3d93-4392-a2c8-1b9945ca669d)

## **Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

