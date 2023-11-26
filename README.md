Implementation-of-Half-Adder-and-Full-Adder-circuit

# Implementation-of-Half-Adder-and-Full-Adder-circuit
### AIM:
To design a half adder and full adder circuit and verify its truth table in Quartus using Verilog programming.

### Equipments Required:
Hardware – PCs, Cyclone II , USB flasher
Software – Quartus prime
Theory
Adders are digital circuits that carry out addition of numbers.

### Half Adder
Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

### Full Adder
Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin Carry = AB + ACin + BCin

 ![image](https://user-images.githubusercontent.com/36288975/163552156-a13e5a56-c638-4110-97d9-8896907c8d25.png)

#### Figure -01 HALF ADDER 


![image](https://user-images.githubusercontent.com/36288975/163552057-b3547877-6d07-45b4-b7e0-bcfebfad9e1d.png)

#### Figure -02 FULL ADDER 

### Procedure

Connect the supply (+5V) to the circuit
Switch ON the main switch
If the output is 1, then the led glows.
### 
Program:
/*
Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
Developed by: KAVIYA SNEKA M

RegisterNumber:  23003642

Code:

Full  Adder:

![Exp3 fa code](https://github.com/kaviya546/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150368823/3aea4355-ca26-432a-b21b-02dcbe13b114)

Half Adder:

![Exp3 ha code](https://github.com/kaviya546/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150368823/9475312d-43d9-4857-a6c4-609e152c55ea)

Truth Table:

Full Adder:

![Exp3 truthtable (fa)](https://github.com/kaviya546/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150368823/75fcd093-24ae-43b0-a32a-f02a50d07d32)

Half Adder:

![Exp3 truthtable (ha)](https://github.com/kaviya546/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150368823/15ba87c8-78fb-459e-8d10-67e15f6259fb)

RTL Viewer:

Full Adder:

![Exp3 fa RTL diagram](https://github.com/kaviya546/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150368823/ef49070a-8405-4ffd-9d3f-1a529f629482)

Half Adder:

![Exp3 ha RTL diagram](https://github.com/kaviya546/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150368823/4801d9ad-387e-401f-b73f-947eb2de9e1e)

Output:

Full Adder:

![Exp3 fa wave](https://github.com/kaviya546/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150368823/adada4e1-6b30-4549-bc96-ae306ad906fb)

Half Adder:


![halfadder-wave](https://github.com/kaviya546/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150368823/2a5c49a1-02d7-479a-9b89-9017f748f770)

### Result : 
Thus the half adder and full adder circuit are designed and the truth table for half adder and full adder are verified.

