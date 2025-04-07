![image](https://github.com/user-attachments/assets/a04cc7cf-ff31-45af-8418-1c26c21ca328)### study-of-basic-gates

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

~~~

module basic_gates(a,b,f1,f2,f3,f4,f5,f6,f7);
input a,b;
output f1,f2,f3,f4,f5,f6,f7;
assign f1=a&b;
assign f2=a|b;
assign f3=~a;
assign f4=~f1;
assign f5=~f2;
assign f6=a^b;
assign f7=~(a^b);
endmodule

~~~

Program for logic gates and verify its truth table in quartus using Verilog programming

 Developed by: JONATHAN RHENIUS S
 
 RegisterNumber: 212224050016
 
**Logic symbol & Truthtable**

![image](https://github.com/user-attachments/assets/389ccf4d-c0af-4014-b434-5350ec1109b7)


![image](https://github.com/user-attachments/assets/eb535f5f-1aa1-4914-b3c2-f961c321fbb4)




**RTL realization :** 

![image](https://github.com/user-attachments/assets/95d6ccb1-f2b4-43dd-9e9c-75de9cc4015d)




**output:**

![image](https://github.com/user-attachments/assets/287a1320-1e02-4862-a3af-8a7dba756500)




**Result:**

Thus the different digital IC’s are studied and the truth table for different logic gates are verified.


