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


**AND GATE**



**PROGRAM**

![321164246-42721fa4-25cf-479c-ac62-c46eb4848116](https://github.com/DharanAditya/study-of-basic-gates/assets/147473834/fb47c970-d230-4a68-89e4-293f2832ca1b)


Program for logic gates and verify its truth table in quartus using Verilog programming

 Developed by:dharan aditya RegisterNumber: 212223040035 


**Logic symbol & Truthtable**

![321164179-6c88473a-812c-49c7-aa4e-b4d96a3f01df](https://github.com/DharanAditya/study-of-basic-gates/assets/147473834/1a5e27c2-4872-4317-9888-b1c2a29b9341)


**RTL realization Output:** 

![321164306-8e2b2737-5e06-4e52-ba2a-95ad34f4cf6e](https://github.com/DharanAditya/study-of-basic-gates/assets/147473834/4354f292-363b-47e1-9709-8891018bade7)


**RTL**

![321164356-a2039c34-158a-44a6-ad99-01382c1391c2](https://github.com/DharanAditya/study-of-basic-gates/assets/147473834/9fa189ad-ae88-4e3a-8450-d903723a03fc)

**OR GATE**

**PROGRAM**

![321164702-bcc41892-f1a4-4532-9b2e-bb97dd065d6b](https://github.com/DharanAditya/study-of-basic-gates/assets/147473834/9b4f9c3c-3608-4805-a982-141e2ec3e7c1)

**Logic symbol & Truthtable**

![321165051-bdbc2626-a8c5-403e-a780-fe9c45ecd620](https://github.com/DharanAditya/study-of-basic-gates/assets/147473834/9891d48b-71eb-498a-9ecb-cacead7af188)

**RTL realization Output:** 

![321164818-eef07ad4-b607-4661-88f6-28bc5b457d99](https://github.com/DharanAditya/study-of-basic-gates/assets/147473834/79133926-24e8-408a-bb33-5d4e8af1a7f0)

**RTL**

![321164889-ee471bb5-ea2d-41f7-95fc-391d8fd17738](https://github.com/DharanAditya/study-of-basic-gates/assets/147473834/c862b390-511c-4632-9f28-df55896df349)

**NOT GATE**

**PROGRAM**

![321165468-c3b3f3d5-0993-4668-8e53-a7407a559d6e](https://github.com/DharanAditya/study-of-basic-gates/assets/147473834/80f35dc3-b171-4840-951f-37ace014bf1b)

**Logic symbol & Truthtable**

![321165510-9ff3c934-4ee1-4612-b3fd-085030bc9d5d](https://github.com/DharanAditya/study-of-basic-gates/assets/147473834/bb31ef66-f6c1-4500-bc25-902107025307)

**RTL realization Output:** 

![321165564-004354e0-69b2-45fb-bbc1-49b3ccfc5dd3](https://github.com/DharanAditya/study-of-basic-gates/assets/147473834/65acfe55-d1ea-438b-bfd5-8eeb51573adf)

**RTL**

![321165617-baf715c8-daf9-4ebc-bea2-a27746521e53](https://github.com/DharanAditya/study-of-basic-gates/assets/147473834/0365aabc-0885-4b7b-a804-bcc90b1abf5d)


**NAND GATE**

**PROGRAM**

![321165836-7542227e-3fea-4e85-942a-3041c16fc056](https://github.com/DharanAditya/study-of-basic-gates/assets/147473834/02cb7dd1-0326-4f00-999c-ca27433d972a)

**Logic symbol & Truthtable**

![321165876-34d57c74-af7c-47e9-aeaf-c85d37ad8973](https://github.com/DharanAditya/study-of-basic-gates/assets/147473834/2e153d10-60b7-43a6-9b76-d452f7c0489a)

**RTL realization Output:** 

![321165952-1aea652d-aa6c-4cab-8f76-13f325b44ea5](https://github.com/DharanAditya/study-of-basic-gates/assets/147473834/fa2566b0-c41f-4b2c-9fa9-864bc4517e19)

**RTL**

![321165992-413f6513-be24-4a82-89dd-9ea38c807fdb](https://github.com/DharanAditya/study-of-basic-gates/assets/147473834/dbcc5f62-7f70-425b-a5b7-a65e7c42cee3)

**NOR GATE**

**PROGRAM**

![321166153-2b587732-18ca-4096-b7b5-8fc08c11a05b](https://github.com/DharanAditya/study-of-basic-gates/assets/147473834/8b9d3dcf-bd50-47ac-8f90-46d73d3bc00b)

**Logic symbol & Truthtable**

![321166203-96c33b8b-7701-44cb-8d55-03ad19bc7192](https://github.com/DharanAditya/study-of-basic-gates/assets/147473834/924b21a3-94da-4800-9203-5e4943994564)


**RTL realization Output:** 

![321166241-5500839e-e01f-4fdd-ad9f-f49f8c659298](https://github.com/DharanAditya/study-of-basic-gates/assets/147473834/2e4322d1-8bb0-4205-af72-a7f4cbaafd9c)


**RTL**

![321166290-f7c56117-2266-4207-aba8-71542604109e](https://github.com/DharanAditya/study-of-basic-gates/assets/147473834/58634e28-7fc9-4a90-a27d-4049067ce1b4)


**EX-OR GATE**

**PROGRAM**

![321166430-6554cf7b-2e19-454d-a622-4b8bf1df1d62](https://github.com/DharanAditya/study-of-basic-gates/assets/147473834/ba5baa65-932e-4960-b90a-1be5448bb381)


**Logic symbol & Truthtable**

![321166458-95c84c59-a361-4562-a1d0-9e5b263e89e3](https://github.com/DharanAditya/study-of-basic-gates/assets/147473834/ce6bbfc8-0516-4254-9447-202f9285dd9f)


**RTL realization Output:** 

![321166500-29e12ee5-77c5-4a2e-ae85-832101244566](https://github.com/DharanAditya/study-of-basic-gates/assets/147473834/351fde6e-8070-4021-9169-735a79f9e755)


**RTL**

![321166550-d42bf2c7-949f-4bfc-8b55-d550c35ba9a0](https://github.com/DharanAditya/study-of-basic-gates/assets/147473834/b40d2850-d559-454a-a018-6d59b20e899c)

**EX-NOR GATE**

**PROGRAM**

![321166733-d6d5e59c-986c-42b6-825d-23ea10901a12](https://github.com/DharanAditya/study-of-basic-gates/assets/147473834/d491e099-9deb-481d-81fa-b26c56134e75)



**Logic symbol & Truthtable**

![321166768-79461902-ef69-4411-9670-934c2458e24e](https://github.com/DharanAditya/study-of-basic-gates/assets/147473834/6b361975-9378-4bdd-b797-efd32fbedc63)


**RTL realization Output:** 

![321166825-4c5684be-49b0-4a08-879b-2947c035d572](https://github.com/DharanAditya/study-of-basic-gates/assets/147473834/6db8402e-22eb-46d2-86af-99569fce1862)


**RTL**

![321166870-3dab2c2a-f7cf-4a6e-b086-8f490fc88c52](https://github.com/DharanAditya/study-of-basic-gates/assets/147473834/22cbd725-447a-486a-85b7-b24733165d98)


**Result:**
Thus,truth table of logic gates in Quartus II using Verilog programming is executed successfully and verified



