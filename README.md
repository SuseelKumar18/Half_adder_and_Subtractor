# Half_adder_and_Subtractor

**Theory**

Half Adder:
A half adder is a fundamental combinational logic circuit that adds two single-bit binary numbers and produces two outputs: the sum and the carry. It has two inputs, often represented as A and B, and two outputs: Sum (S) and Carry (C).

Sum (S) is the result of the addition of A and B without considering any carry input.

Carry (C) is the output carry generated when both inputs are 1.

The sum output is given by the XOR of inputs 
S
=
A
⊕
B
S=A⊕B, and the carry output is given by the AND of the inputs 
C
=
A
⋅
B
C=A⋅B.

The half adder is the simplest form of an adder and is primarily used to add the least significant bits in binary addition.

Half Subtractor:
A half subtractor is a combinational logic circuit designed to subtract two single-bit binary numbers. It has two inputs:

A (Minuend bit)

B (Subtrahend bit)

and two outputs:

Difference (D)

Borrow (B)

The difference output is the XOR of the inputs:

D
=
A
⊕
B
=
A
′
B
+
A
B
′
D=A⊕B=A 
′
 B+AB 
′
 
The borrow output indicates when a borrow has taken place during subtraction. It is produced when the minuend bit A is less than the subtrahend bit B:

B
o
r
r
o
w
=
A
′
⋅
B
Borrow=A 
′
 ⋅B
The half subtractor thus performs subtraction without considering any borrow coming from a previous stage.
