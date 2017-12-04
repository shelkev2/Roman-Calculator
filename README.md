# Roman-Calculator
In this project, we are going to build a simple calculator with a twist-- a calculator that calculates on Roman numerals!

Roman numerals use the following symbols to express numbers.

Symbol	Value
M	1000
D	500
C	100
L	50
X	10
V	5
I	1
Symbols must appear from highest value to lowest value. In addition, these special combinations are used:

Combo	Value	Instead of
CM	900	(instead of DCCCC)
CD	400	(instead of CCCC)
XC	90	(instead of LXXXX)
XL	40	(instead of XXXX)
IX	9	(instead of VIIII)
IV	4	(instead of IIII)
No symbol should ever appear more than three times in a row. There is exactly one correct way of writing every number between 1 and 3999.

For example, 25 is XXV, 95 is XCV, 99 is XCIX, 642 is DCXLII, and 2015 is MMXV.


The result
The final program prints a prompt and waits for you to type a simple expression to calculate. An expression consists of a number in Roman numerals, followed by an operation, followed by another number in Roman numerals. Each should be separated by a space.

The program will behave like this:

> I + I
II

> VII * VI
XLII

> M - I
CMXCIX

> C % IX
I

> D # DC
DL

> D
syntax error

> XVII + 4
invalid number: 4

> X @ XX
invalid operation: @

>
done
If you provide an empty input, the program prints "done" and exits. Otherwise, it keeps running indefinitely.
