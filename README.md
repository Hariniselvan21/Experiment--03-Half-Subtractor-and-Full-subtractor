# Experiment--03-Half-Subtractor-and-Full-subtractor
## Implementation-of-Half-subtractor-and-Full-subtractor-circuit
## AIM:
To design a half subtractor and full subtractor circuit and verify its truth table in Quartus using Verilog programming.

## Equipments Required:
## Hardware – PCs, Cyclone II , USB flasher
## Software – Quartus prime
## Theory
Subtractor circuits take two binary numbers as input and subtract one binary number input from the other binary number input. Similar to adders, it gives out two outputs, difference and borrow (carry-in the case of Adder). There are two types of subtractors.

## Half Subtractor Full Subtractor
## Half Subtractor
The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed.
![half-subtractor9](https://user-images.githubusercontent.com/36288975/166112538-58c3bc7c-ee5d-4e6a-ac8d-8e8328efe27a.png)


Sum = X'Y+XY' = X ⊕ Y
Carry=X'Y

## Full Subtractor
A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow. 
![full-subtractor6](https://user-images.githubusercontent.com/36288975/166112541-24c68359-3de8-4674-ae22-8272ffc385ed.png)


Diff = A ⊕ B ⊕ Bin B = A'Bin + A'B + BBin

## Procedure
Connect the supply (+5V) to the circuit. *Switch ON the main switch. *If the output is 1, then the led glows

## Program:
/*
Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.
## Developed by: Harini.N
## RegisterNumber:212223050019 
*/
### 1.program to design a half subtractor
![image](https://github.com/Hariniselvan21/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/155089072/56c26657-7516-47e2-9923-fdf41f53fdef)

### 3.program to design a full subtractor
![image](https://github.com/Hariniselvan21/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/155089072/e7c1ba30-6ed5-4cdf-8e6e-b5d7e7b14a5f)

## Output:
## Truthtable
## HALF SUBTRACTOR
![image](https://github.com/Hariniselvan21/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/155089072/d0f95f91-6505-44e0-9d86-445f48f5826a)

## FULL SUBTRACTOR
![image](https://github.com/Hariniselvan21/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/155089072/c7727194-1595-4aca-be37-d1e47c8dd6a0)

##  RTL realization
## HALF SUBTRACTOR:
![image](https://github.com/Hariniselvan21/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/155089072/aafd9fb3-ace6-4bde-b45b-1c8e7759f1f7)

## FULL SUBTRACTOR:
![image](https://github.com/Hariniselvan21/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/155089072/92903653-f524-4123-96d6-8956d055795c)

## Timing diagram:
## HALF SUBTRACTOR
![image](https://github.com/Hariniselvan21/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/155089072/0b0af3a7-e1c8-4517-9e8a-c604e56c44fb)

## FULL SUBTRACTOR
![image](https://github.com/Hariniselvan21/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/155089072/32fb2a9b-c4af-426a-859f-890554fb16b9)

## Result:
Thus the half subtractor and full subtractor circuits are designed and the truth tables is verified using quartus software.
