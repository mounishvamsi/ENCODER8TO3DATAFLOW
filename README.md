### ENCODER 8TO3 DATAFLOW Modelling

**AIM:**

To implement  Encoder 8 To 3 in Dataflow Modelling using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:** Quartus prime

**THEORY**

**Encoder 8 To 3**

The 8 to 3 line Encoder is also known as Octal to Binary Encoder. In 8 to 3 line encoder, there is a total of eight inputs, i.e., D0, D1, D2, D3, D4, D5, D6, and D7 and three outputs, i.e., A0, A1, and A2. In 8-input lines, one input-line is set to true at a time to get the respective binary code in the output side. Below are the block diagram and the truth table of the 8 to 3 line encoder.

![image](https://github.com/naavaneetha/ENCODER8TO3DATAFLOW/assets/154305477/0bc242c1-eb9e-4c47-afe5-30428470efc3)

Figure 01  Block Diagram of Encoder 8 * 3

**Truth Table**

![image](https://github.com/naavaneetha/ENCODER8TO3DATAFLOW/assets/154305477/35496b14-ae6e-4cd1-9abd-d6736b576575)

The logical expression of the term A0, A1, and A2 are as follows:

A0 = D1 + D3 + D5 + D7

A1 = D2 + D3 + D6 + D7

A2 = D4 + D5 + D6 + D7

Logical circuit of the above expressions is given below:

![image](https://github.com/naavaneetha/ENCODER8TO3DATAFLOW/assets/154305477/95acaee6-c873-4c75-89eb-ef09fb158053)

Figure 02  Encoder 8 * 3

**Procedure**

/* 1.Type the program in Quartus software. 2.Compile and run the program. 3.Generate the RTL schematic and save the logic diagram. 4.Create nodes for inputs and outputs to generate the timing diagram. 5.For different input combinations generate the timing diagram */

**PROGRAM**

/*  Module enc(a,b,c,y0,y1,y2,y3,y4,y5,y6,y7);

input a,b,c;

output y0,y1,y2,y3,y4,y5,y6,y7;

assign a= ( y4 | y5 | y6 | y7);

assign b= ( y2 | y3 | y6 | y7);

assign c= ( y1 | y3 | y5 | y7);

endmodule

Program for Encoder 8 To 3 in Dataflow Modelling and verify its truth table in quartus using Verilog programming. 

Developed by:R. mounish vamsi kumar 

RegisterNumber:24003774
*/

**RTL LOGIC FOR Encoder 8 To 3 in Dataflow Modelling**

![Screenshot 2024-12-22 091101](https://github.com/user-attachments/assets/feb49dd2-55e8-4b5d-b7dc-ca52617c1d9d)


**TIMING DIGRAMS FOR Encoder 8 To 3 in Dataflow Modelling**

![Screenshot 2024-12-22 091119](https://github.com/user-attachments/assets/9e4186a2-9863-4843-b0aa-76032e2addb6)




**RESULTS Thus the encoder 8 to 3 is designed and the truthtable is verifies**




