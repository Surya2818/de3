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

![WhatsApp Image 2024-11-26 at 17 08 47_1ec02758](https://github.com/user-attachments/assets/31527d4e-8940-458a-8c22-bd8356165ac8)

![WhatsApp Image 2024-11-26 at 17 08 47_96342e37](https://github.com/user-attachments/assets/7fcf3e94-4d2f-4e4e-a113-9dcbdd58503f)


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

![WhatsApp Image 2024-11-26 at 17 09 59_83affbb4](https://github.com/user-attachments/assets/7d59bc14-f5fb-4174-8bc0-ccfe9c4c9c45)

HALF SUBTRACTER

![WhatsApp Image 2024-11-26 at 17 09 59_7e174266](https://github.com/user-attachments/assets/a23dc3b2-b412-4ec6-a906-dd5d943254da)


*Output/TIMING Waveform*

HALF ADDER

![WhatsApp Image 2024-11-26 at 17 09 59_37c3539e](https://github.com/user-attachments/assets/6a68b5f1-6083-4956-95b2-6333f947b6c3)


HALF SUBTRACTER

![WhatsApp Image 2024-11-26 at 17 09 59_754c796d](https://github.com/user-attachments/assets/5c9f5ee1-34eb-491a-8266-ec81f1e9a177)


*Result:*
The Truth table of the half subtractor and full adder are verified.
