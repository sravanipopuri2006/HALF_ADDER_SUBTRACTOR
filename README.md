# HALF_ADDER_SUBTRACTOR

Implementation-of-Half-Adder-and-Half Subtractor-circuit

**AIM:**

To design a half adder and half subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher 

Software – Quartus prime Theory Adders are digital circuits that carry out the addition of numbers.

**Half Adder**

Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/bd4a0b2c-cdbc-4184-ab08-81578f121e1f)

Figure -01 HALF ADDER

**Half Subtractor**

The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed. 

Diff = A’B+AB’ =A ⊕ B
Borrow = A’B

 ![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/d76b099c-513f-4e7c-843a-e2fd028a531a)

Figure -02 HALF Subtractor

**Truthtable**
## HALF ADDER
![Screenshot 2024-04-03 212647](https://github.com/sravanipopuri2006/HALF_ADDER_SUBTRACTOR/assets/139778301/01625e9c-cf63-41eb-91e2-5aee804dc3d3)


## HALF SUBTRACTOR
![Screenshot 2024-04-03 212654](https://github.com/sravanipopuri2006/HALF_ADDER_SUBTRACTOR/assets/139778301/d19bdfdf-e4b3-48b8-b108-422411b2ca71)



**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**
## HALF ADDER
![Screenshot 2024-04-03 205150](https://github.com/sravanipopuri2006/HALF_ADDER_SUBTRACTOR/assets/139778301/67bc7962-36cb-4ca9-b9e4-00db7832aa86)
## HALF SUBTRACTOR
![Screenshot 2024-04-03 205418](https://github.com/sravanipopuri2006/HALF_ADDER_SUBTRACTOR/assets/139778301/bd67c92d-d4d7-449e-a41a-6c04a36f9ce1)





**RTL Schematic**
## HALF ADDER
![Screenshot 2024-04-03 204323](https://github.com/sravanipopuri2006/HALF_ADDER_SUBTRACTOR/assets/139778301/9b3818f0-4725-49b7-9cd4-af93faea404d)


## HALF SUBTRACTOR
![Screenshot 2024-04-03 204342](https://github.com/sravanipopuri2006/HALF_ADDER_SUBTRACTOR/assets/139778301/69806053-6fce-4b6a-9469-93ae36011306)


**Output/TIMING Waveform**
## HALF ADDER
![Screenshot 2024-04-03 204400](https://github.com/sravanipopuri2006/HALF_ADDER_SUBTRACTOR/assets/139778301/7b1aff92-1728-4964-afa1-a44047ae1f07)

## HALF SUBTRACTOR
![Screenshot 2024-04-03 204408](https://github.com/sravanipopuri2006/HALF_ADDER_SUBTRACTOR/assets/139778301/f63ee374-7d21-4547-90ac-d9999b8f87a4)


**Result:**
Thus the half adder and half subtractor circuits are designed and the truth tables is verified using quartus software.
