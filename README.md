# HALF_ADDER_SUBTRACTOR

Implementation-of-Half-Adder-and-Half Subtractor-circuit

*AIM:*

To design a half adder and half subtractor circuit and verify its truth table in Quartus using Verilog programming.

*Equipments Required:*

Hardware – PCs, Cyclone II , USB flasher 

Software – Quartus prime Theory Adders are digital circuits that carry out the addition of numbers.

*Half Adder*

Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/bd4a0b2c-cdbc-4184-ab08-81578f121e1f)

Figure -01 HALF ADDER

*Half Subtractor*

The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed. 

Diff = A’B+AB’ =A ⊕ B
Borrow = A’B

 ![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/d76b099c-513f-4e7c-843a-e2fd028a531a)

Figure -02 HALF Subtractor

*Truthtable*

![WhatsApp Image 2024-11-26 at 17 08 51_b073ab81](https://github.com/user-attachments/assets/cb221933-0f43-4a10-8337-196b58927684)


![WhatsApp Image 2024-11-26 at 17 08 51_fa9ad4d2](https://github.com/user-attachments/assets/7f345d8a-c612-4ae7-87d3-cc27265961bf)



*Procedure*

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


*Program:*

/* Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.

Developed by:Surya D

RegisterNumber:24901185

*RTL Schematic*

HALF ADDER

![WhatsApp Image 2024-11-26 at 17 10 02_f03b5f72](https://github.com/user-attachments/assets/80393421-3e6e-4056-a4f8-de82d9e82422)


HALF SUBTRACTER

![WhatsApp Image 2024-11-26 at 17 10 02_f56b05a8](https://github.com/user-attachments/assets/dcb67e1c-4271-468f-ace8-e50af394221c)



*Output/TIMING Waveform*

HALF ADDER

![WhatsApp Image 2024-11-26 at 17 10 02_253d6417](https://github.com/user-attachments/assets/5b9b5ff3-0819-4f63-81ad-9cb5adf876cd)



HALF SUBTRACTER

![WhatsApp Image 2024-11-26 at 17 10 02_ab26a96e](https://github.com/user-attachments/assets/a66ea437-7fa1-4bb8-9764-b3554a390c35)




*Result:*
The Truth table of the half subtractor and full adder are verified.
