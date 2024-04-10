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
![321148778-62a9532f-0eb2-475a-a3eb-e18f6b293bc9](https://github.com/DharanAditya/study-of-basic-gates/assets/147473834/29de6aae-5abf-45da-8846-f583222e8659)

Program for logic gates and verify its truth table in quartus using Verilog programming

 Developed by: RegisterNumber: 
 
**Logic symbol & Truthtable**
![321148861-75a1276a-705a-4443-880b-4c77a64b9f80](https://github.com/DharanAditya/study-of-basic-gates/assets/147473834/9e34e6b7-7e63-46fe-ab67-69446adae7ed)

**RTL realization Output:** 
![321148895-ede0e627-821c-45b1-8cc5-58747f16018b](https://github.com/DharanAditya/study-of-basic-gates/assets/147473834/440b5d8e-374c-46b6-8c08-7468f20d969c)

**RTL**
![321148964-2b17c7ab-46db-49d2-811d-80ef75854af3](https://github.com/DharanAditya/study-of-basic-gates/assets/147473834/6c40e410-948e-4b0b-b985-0568a7ceb71d)

**Result:**
 Thus the different digital IC’s are studied and the truth table for different logic gates are verified.


