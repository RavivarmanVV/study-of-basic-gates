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
```
module exp_1(a,b,y1,y2,y3,y4,y5,y6,y7);
input a,b;
output y1,y2,y3,y4,y5,y6,y7;
and g1(y1,a,b);
or g2(y2,a,b);
not g3(y3,a);
nand g4(y4,a,b);
nor g5(y5,a,b);
xor g6(y6,a,b);
xnor g7(y7,a,b);
endmodule
```
 Developed by:Ravivarman 
 RegisterNumber: 24006127
 
**Logic symbol & Truthtable**
AND gate
![Screenshot 2024-12-05 201029](https://github.com/user-attachments/assets/e22da214-479b-4ad4-91a3-74c31290ff32)

OR gate
![Screenshot 2024-12-05 201035](https://github.com/user-attachments/assets/fb0dd8a0-a482-45fc-9f0b-09600638f99c)

NOT gate
![Screenshot 2024-12-05 201042](https://github.com/user-attachments/assets/b6ea3498-ed99-457e-b067-0916451e2b55)

NAND gate
![Screenshot 2024-12-05 201049](https://github.com/user-attachments/assets/c53e6f9e-1c24-4d8a-9d9d-4f899dec792f)

NOR gate
![Screenshot 2024-12-05 201125](https://github.com/user-attachments/assets/e7d8b691-4761-433a-b2c0-f2eb5e102300)

XOR gate
![Screenshot 2024-12-05 201131](https://github.com/user-attachments/assets/fe5cbaaf-88a9-479f-82b4-710087aa34df)

XNOR gate
![Screenshot 2024-12-05 201138](https://github.com/user-attachments/assets/02381025-eeba-4656-8b87-eaab987d71e3)

**RTL realization Output:** 
![Screenshot 2024-12-05 201147](https://github.com/user-attachments/assets/19a0047a-93d0-4570-9149-de1907dab2d7)

**RTL**
![Screenshot 2024-12-05 201200](https://github.com/user-attachments/assets/b0c291b8-85eb-4767-9f60-fd7794e960e1)

**Result:**
Thus the Basic digital ICs and the verification of truth tables for different logic gates were studied and successfully realized using Verilog.

