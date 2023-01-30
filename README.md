# Verilog-Multipe-Operations
 performs addition, subtraction, AND, OR, and Exclusive OR (XOR) the output is in 7-segment display for the operands A (4-bit long) and B (4-bit long)

An arithmetic logic unit (ALU) that performs addition, subtraction, AND, OR, and Exclusive OR (XOR) is needed to be designed, the output and input should be displayed on a 7-segment display for the operands A (4-bit long) and B (4-bit long) using Logisim and Verilog

It is important in this project to get the equations correctly because everything will depend on them, so we divided the project into 4 Equations one for the addition/subtraction the other for 4 bit AND,4 bit OR, 4 bit XOR to make it easier to understand and organize.
For the addition/subtraction:
S1= A1^ (B1 ^M) ^ M.
C1 = A1M + B1 M + A1B1.
S2= A2^ (B2 ^M) ^ C1.
C2 = A2C1 + B2 C1 + A2B2.
S3= A3^ (B2 ^M) ^ C2.
C3 = A3C2 + B3 C2 + A3B3.
S4= A4^ (B4 ^M) ^ C3.
C4 = A4C3 + B2 C3 + 42B.

For the 4 bit AND:
AND1= A1B1
AND2= A2B2
AND3= A3B3
AND4= A4B4

![ohiae](https://user-images.githubusercontent.com/123680723/215464633-ff280f7e-6a52-477e-b141-0089f452540d.jpg)
