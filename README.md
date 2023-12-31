# Exp-03-Implementation-of-Half-Adder-and-Full-Adder-circuit

# Implementation-of-Half-Adder-and-Full-Adder-circuit

# AIM:

To design a half adder and full adder circuit and verify its truth table in Quartus using Verilog programming.

# Equipments Required:
Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime

# Theory:

Adders are digital circuits that carry out addition of numbers.

# Half Adder:

Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

# Full Adder:

Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin Carry = AB + ACin + BCin

 ![image](https://user-images.githubusercontent.com/36288975/163552156-a13e5a56-c638-4110-97d9-8896907c8d25.png)

# Figure -01 HALF ADDER 


![image](https://user-images.githubusercontent.com/36288975/163552057-b3547877-6d07-45b4-b7e0-bcfebfad9e1d.png)

# Figure -02 FULL ADDER 

# Procedure:

Connect the supply (+5V) to the circuit
Switch ON the main switch
If the output is 1, then the led glows.

# Program:

Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.

Developed by:DHARSHNI V M 

Register Number: 212223240029

# Code:

HALF ADDER:

![Exp3 ha code](https://github.com/Dharshni10/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/145801097/a0dab8e1-9c0b-4d36-b71a-dfdd191d8d54)

FULL ADDER:

![Exp3 fa code](https://github.com/Dharshni10/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/145801097/116d955b-c56a-460a-81a5-66a24b3b06dc)

# RTL realization:

HALF ADDER:

![Exp3 ha RTL diagram](https://github.com/Dharshni10/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/145801097/eb4f9a2f-0334-4f23-a735-c9f594cbf632)

FULL ADDER:

![Exp3 fa RTL diagram](https://github.com/Dharshni10/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/145801097/bee4983b-8afc-4211-930f-408cfe9e6c07)

# TRUTH TABLE:

HALF ADDER:

![Exp3 truthtable (ha)](https://github.com/Dharshni10/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/145801097/8170e12c-a797-4ee1-8767-0e9012c0e15e)

FULL ADDER:

![Exp3 truthtable (fa)](https://github.com/Dharshni10/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/145801097/6eea6941-32f9-4d48-9d80-de37d079c8be)

# Timing diagram:

HALF ADDER:

![halfadder wf 1](https://github.com/Dharshni10/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/145801097/b299d81a-93fc-4668-8a8a-dafbde11551a)

FULL ADDER:

![fulladder wf 1](https://github.com/Dharshni10/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/145801097/a7c3d29c-eb4d-4313-ae5f-f05edbd37292)

# Result:

Thus, a half adder and full adder circuit is designed to verify its truth table in Quartus using Verilog
programming.
