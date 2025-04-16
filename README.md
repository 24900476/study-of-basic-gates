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
module 4x1(a,b,y1,y2,y3,y4,y5,y6,y7);
input a,b;
output y1,y2,y3,y4,y5,y6,y7;
and(y1,a,b);
or (y2,a,b);
nor (y3,a);
nand (y4,a,b);
nor (y5,a,b);
xor (y6,a,b);
xnor(y7,a,b);
endmodule
```
 Developed by:KABIRA A RegisterNumber:212224040146
 
**Logic symbol & Truthtable**


AND gate


![AND GATE](https://github.com/user-attachments/assets/f15e3adf-ee37-41c6-8584-dc6155103e27)

OR gate


![OR GATE](https://github.com/user-attachments/assets/c22e1246-56f2-4c4b-854f-6861578c464b)

NOT gate


![NOT GATE](https://github.com/user-attachments/assets/f494b9da-23da-413b-b053-4b5f8bdec172)

NAND gate


![NAND GATE](https://github.com/user-attachments/assets/61699040-8af1-40cd-8f94-ba848b62c4c1)

NOR gate


![NOR GATE](https://github.com/user-attachments/assets/eac61088-b260-48f8-beee-cf62fdd04183)

XOR gate


![XOR GATE](https://github.com/user-attachments/assets/782fc81e-8220-4dd8-b074-cd785702928b)

XNOR gate


![XNOR GATE](https://github.com/user-attachments/assets/e1551b71-f998-4b5b-9d39-c3a6e5002f6e)


**RTL realization Output:** 

![logic diagram exp 1](https://github.com/user-attachments/assets/93dd6de6-31e7-4041-9efe-48128a7829ea)


**RTL**

![digi 1exp](https://github.com/user-attachments/assets/69debf43-0be7-404f-8377-241f8f2529fa)


**Result:**
Thus the baic digital ICs and the verification of truth tables for different logic gates were studied and successfully realized using Verilog.

