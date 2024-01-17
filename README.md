LAB WORKSHEET

------ PART I ------

1. Take a look at the "sum" register in the GUI. What value(s) does "sum" need to be in order for the Z flag to be 1?
	0
2. Give a signed decimal value for the "sum" register that keeps the N flag lowered (i.e., 0).
	+1
3. Now give an unsigned decimal value for "sum" that lowers the N flag i.e., makes it 0.
	0
4. Why is the carry-in bit set to 1 during subtraction?
	because 1 is the sign for negative numbers
------ PART II ------

For the following entries, perform the arithmetic assuming UNSIGNED 4-bit registers, and fill in the flags (conditional codes) based on value in the "sum" register.

Use the GUI binary adder to help you out. Note: Subtraction is performed using 2's completment however, you should still put the positive value in the cells.

Also, when I prompt for "NZVC:" I'm asking you to stick together all of the flags (conditional codes) in that order. So, for example, if all flags are lowered, you would say 0000, if the N flag is raised you would say 1000, etc, etc.

(fill in where there is a _)
====================================================
Decimal                 Binary
----------------------------------------------------
10                       1010
+3                      +0011
=13                     =1101
----------------------------------------------------
NZVC: 1000
====================================================

====================================================
Decimal                 Binary
----------------------------------------------------
7                        0111
+7                      +0111
=14                     =1110
----------------------------------------------------
NZVC: 1010
====================================================

====================================================
Decimal                 Binary
----------------------------------------------------
12                       1100
-5                      -0101
=7                      =0111
----------------------------------------------------
NZVC: 0010
====================================================

====================================================
Decimal                 Binary
----------------------------------------------------
10                       1010
-6                      -0110
=4                      =0100
----------------------------------------------------
NZVC: 0010
====================================================


Now switch and assume SIGNED arithmetic (still 4-bit registers)

====================================================
Decimal                 Binary
----------------------------------------------------
4                        0100
+3                      +0011
=7                      =0111
----------------------------------------------------
NZVC: 0000
====================================================

====================================================
Decimal                 Binary
----------------------------------------------------
4                        0100
+10                     +1010
=14                     =1110
----------------------------------------------------
NZVC: 1000
====================================================

====================================================
Decimal                 Binary
----------------------------------------------------
4                         0100
-10                      -1010
=-6                      =-0110
----------------------------------------------------
NZVC: 1011
====================================================
