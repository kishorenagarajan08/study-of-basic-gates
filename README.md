### study-of-basic-gates

**AIM:** 

To study and verify the truth table of logic gates in Quartus II using Verilog programming.

**Equipments Required:**

Software – Quartus prime 

**Theory**

Introduction Logic gates are the basic building blocks of any digital system. Logic gates are electronic circuits having one or more than one input and only one output. The relationship between the input and the output is based on a certain logic. Based on this, logic gates are named as

AND gate OR gate NOT gate NAND gate NOR gate Ex-OR gate Ex-NOR gate

**AND gate**

The AND gate is an electronic circuit that gives a high output (1) only if all its inputs are high. A dot (.) is used to show the AND operation i.e. A.B or can be written as AB
Y= A.B

**OR gate** 

The OR gate is an electronic circuit that gives a high output (1) if one or more of its inputs are high. A plus (+) is used to show the OR operation.
Y= A+B

**NOT gate**

The NOT gate is an electronic circuit that produces an inverted version of the input at its output. It is also known as an inverter. If the input variable is A, the inverted output is known as NOT A. This is also shown as A' or A with a bar over the top, as shown at the outputs.
Y= A'

**NAND gate**

This is a NOT-AND gate which is equal to an AND gate followed by a NOT gate. The outputs of all NAND gates are high if any of the inputs are low. The symbol is an AND gate with a small circle on the output. The small circle represents inversion.
Y= (AB)’

**NOR gate**

This is a NOT-OR gate which is equal to an OR gate followed by a NOT gate. The outputs of all NOR gates are low if any of the inputs are high. The symbol is an OR gate with a small circle on the output. The small circle represents inversion.
Y= (A+B)’

**Ex-OR gate**

The 'Exclusive-OR' gate is a circuit which will give a high output if either, but not both of its two inputs are high. An encircled plus sign (⊕) is used to show the Ex-OR operation.
Y= A⊕B

**Ex-NOR gate**

The 'Exclusive-NOR' gate circuit does the opposite to the EX-OR gate. It will give a low output if either, but not both of its two inputs are high. The symbol is an EX-OR gate with a small circle on the output. The small circle represents inversion.
Y= A⊕B

**Procedure** 

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**PROGRAM**

Program for logic gates and verify its truth table in quartus using Verilog programming

# Developed by: Kishore N
# register no: 212223230106
# program:
![image](https://github.com/kishorenagarajan08/study-of-basic-gates/assets/155753188/4bf57712-db46-4ad1-9d75-fd6137d8f2bf)

# Logic symbol & Truthtable
![image](https://github.com/kishorenagarajan08/study-of-basic-gates/assets/155753188/f2615f5f-e96e-4ce4-b2ea-28665e0ab963)

# RTL
![image](https://github.com/kishorenagarajan08/study-of-basic-gates/assets/155753188/387b615b-61d2-4de0-afd6-2e05ac9c9824)

# RTL realization Output:
![image](https://github.com/kishorenagarajan08/study-of-basic-gates/assets/155753188/139dc369-8d5e-4b77-9fca-d94cbf5fd321)


# OR GATE:
# program:
![image](https://github.com/kishorenagarajan08/study-of-basic-gates/assets/155753188/6d51d1c1-8e46-4c90-a988-cb6e31bf6bf4)

# Logic symbol & Truthtable:
![image](https://github.com/kishorenagarajan08/study-of-basic-gates/assets/155753188/0952f560-266a-4b8e-923e-f60ec52b799a)

# RTL:
![image](https://github.com/kishorenagarajan08/study-of-basic-gates/assets/155753188/57c99f11-ce38-4ef6-bed2-df3bc852fa44)

# RTL realization Output:
![image](https://github.com/kishorenagarajan08/study-of-basic-gates/assets/155753188/bfb77eee-ad90-45f8-a3e7-ccf9982db1a1)

# NOT GATE:
# program:
![image](https://github.com/kishorenagarajan08/study-of-basic-gates/assets/155753188/0d4b970a-b1fd-49e8-8295-f2810720f439)

# Logic symbol & Truthtable:
![image](https://github.com/kishorenagarajan08/study-of-basic-gates/assets/155753188/046ea80a-f947-4dc7-b4bd-0ed22ac4ecee)

# RTL:
![image](https://github.com/kishorenagarajan08/study-of-basic-gates/assets/155753188/dff16bb9-1d83-47b5-9a45-223a5ff04314)


# RTL realization Output:
![image](https://github.com/kishorenagarajan08/study-of-basic-gates/assets/155753188/f0b8a44b-c8eb-445b-8b35-effa771787e3)

# NAND GATE:
# program:
![image](https://github.com/kishorenagarajan08/study-of-basic-gates/assets/155753188/1b0188c4-0f12-42d3-9837-d85583bbee3c)

# Logic symbol & Truthtable:
![image](https://github.com/kishorenagarajan08/study-of-basic-gates/assets/155753188/8a45d0b4-6a42-4b20-9b48-e05e2d285f71)

# RTL:
![image](https://github.com/kishorenagarajan08/study-of-basic-gates/assets/155753188/989af051-a72e-4e28-bac0-ed1ccd6d6407)


# RTL realization Output:
![image](https://github.com/kishorenagarajan08/study-of-basic-gates/assets/155753188/c8931afa-84bc-4b02-93f6-3eddb4b74a2a)

# NOR GATE:
# program:
![image](https://github.com/kishorenagarajan08/study-of-basic-gates/assets/155753188/7de8c760-ee5a-4e88-ac5f-45892c96c647)

# Logic symbol & Truthtable:
![image](https://github.com/kishorenagarajan08/study-of-basic-gates/assets/155753188/c850eb53-28b9-42e0-aa94-d1a582999647)

# RTL:
![image](https://github.com/kishorenagarajan08/study-of-basic-gates/assets/155753188/c866b8e0-1ee5-4a96-8abd-165ee42ddbf4)

# RTL realization Output:
![image](https://github.com/kishorenagarajan08/study-of-basic-gates/assets/155753188/8b92c630-7b06-4a5c-9e72-5ebf50dcfe7b)

# EX-OR GATE:
# program :
![image](https://github.com/kishorenagarajan08/study-of-basic-gates/assets/155753188/b37e6d06-1aa6-4f9a-9a2d-3c7637a0531a)

# Logic symbol & Truthtable:
![image](https://github.com/kishorenagarajan08/study-of-basic-gates/assets/155753188/54f31bec-5d27-4314-aa61-07e1700e1ec7)

# RTL:
![image](https://github.com/kishorenagarajan08/study-of-basic-gates/assets/155753188/b6df9a05-b0f0-4e0f-8e6e-c15c77912886)

# RTL realization Output:
![image](https://github.com/kishorenagarajan08/study-of-basic-gates/assets/155753188/d3bc1532-0d03-4ae3-aaaa-10359ce97c14)

# EX-NOR:
# program:
![image](https://github.com/kishorenagarajan08/study-of-basic-gates/assets/155753188/e2bd1ac8-75c7-44a1-b064-0b1b5f998f6a)

# Logic symbol & Truthtable:
![image](https://github.com/kishorenagarajan08/study-of-basic-gates/assets/155753188/3d81afa1-498c-4a56-8ee8-27f2123488f6)

# RTL:
![image](https://github.com/kishorenagarajan08/study-of-basic-gates/assets/155753188/6fe95c4c-671c-4d42-9ae5-bb6771dc1eb7)

# RTL realization Output:
![image](https://github.com/kishorenagarajan08/study-of-basic-gates/assets/155753188/ba0b8caf-f804-4b84-9f28-35f5a40fbd08)

# Result:
Thus,truth table of logic gates in Quartus II using Verilog programming is executed successfully and verified
