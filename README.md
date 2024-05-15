# ENCODER 8TO3 DATAFLOW Modelling

## AIM:

To implement  Encoder 8 To 3 in Dataflow Modelling using verilog and validating their functionality using their functional tables

## SOFTWARE REQUIRED: Quartus prime

## THEORY

## Encoder 8 To 3

The 8 to 3 line Encoder is also known as Octal to Binary Encoder. In 8 to 3 line encoder, there is a total of eight inputs, i.e., D0, D1, D2, D3, D4, D5, D6, and D7 and three outputs, i.e., A0, A1, and A2. In 8-input lines, one input-line is set to true at a time to get the respective binary code in the output side. Below are the block diagram and the truth table of the 8 to 3 line encoder.

![image](https://github.com/sanjevrm/ENCODER8TO3DATAFLOW/assets/155142423/bb14e510-218b-4d55-acd0-65433887ce3e)


Figure 01  Block Diagram of Encoder 8 * 3

## Truth Table

![image](https://github.com/sanjevrm/ENCODER8TO3DATAFLOW/assets/155142423/4a24339c-1173-4d9f-bb71-83515e1eff6c)


The logical expression of the term A0, A1, and A2 are as follows:

A0 = D1 + D3 + D5 + D7

A1 = D2 + D3 + D6 + D7

A2 = D4 + D5 + D6 + D7

Logical circuit of the above expressions is given below:

![image](https://github.com/sanjevrm/ENCODER8TO3DATAFLOW/assets/155142423/dcc852a8-e8ff-48ab-a0a1-9f5c07deca73)


Figure 02  Encoder 8 * 3

## Procedure
1.Type the program in Quartus software.

2.Compile and run the program.

3.Generate the RTL schematic and save the logic diagram.

4.Create nodes for inputs and outputs to generate the timing diagram.

5.For different input combinations generate the timing diagram.

## PROGRAM
```
Program for Encoder 8 To 3 in Dataflow Modelling and verify its truth table in quartus using Verilog programming. 

Developed by: Sanjev R M
RegisterNumber: 212223040186
```
![image](https://github.com/sanjevrm/ENCODER8TO3DATAFLOW/assets/155142423/5bb2aa5d-fd20-411a-a87f-96eb7071d0ab)

## RTL LOGIC FOR Encoder 8 To 3 in Dataflow Modelling
![image](https://github.com/sanjevrm/ENCODER8TO3DATAFLOW/assets/155142423/55869494-ff9d-47b0-8ab7-c86399c56012)

## TIMING DIGRAMS FOR Encoder 8 To 3 in Dataflow Modelling 
![image](https://github.com/sanjevrm/ENCODER8TO3DATAFLOW/assets/155142423/d4d74404-64bf-48aa-9ab3-2e28e1263f6e)

## RESULTS
Thus,the 8 to 3 encoder using verilog is validated successfully.




