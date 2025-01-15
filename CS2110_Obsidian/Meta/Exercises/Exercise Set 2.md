#wip
### 2.1
Given n bits, how many distinct combinations of the n bits exist?
> [!solution]-
$2^n$
### 2.2
There are 26 characters in the alphabet we use for writing English. What
is the least number of bits needed to give each character a unique bit
pattern? How many bits would we need to distinguish between upper-
and lowercase versions of all 26 characters?
> [!solution]-
> * $26$ unique chars needs a minimum of $32=2^5$ combos -> 5 bits
> * $52$ chars needs $64 = 2^6$ combos -> 6 bits
### 2.3
a. Assume that there are about 400 students in your class. If every
student is to be assigned a unique bit pattern, what is the minimum
number of bits required to do this?
b. How many more students can be admitted to the class without
requiring additional bits for each student’s unique bit pattern?
> [!solution]-
a. Minimum number to represent 400 different values is $2^9$, i.e. 512
b. 113 more can be admitted (0 is a unique bit pattern)
### 2.4
Given n bits, how many unsigned integers can be represented with the n
bits? What is the range of these integers?
> [!solution]-
$2^n$
$[0, 2^{n} - 1]$
### 2.5
Using ﬁve bits to represent each number, write the representations of
7 and −7 in 1’s complement, signed magnitude, and 2’s complement
integers.
> [!solution]-


### 2.6
Write the six-bit 2’s complement representation of −32.
> [!solution]-
### 2.10
Convert the following 2’s complement binary numbers to decimal.
a. 1010
b. 01011010
c. 11111110
d. 0011100111010011
> [!solution]-
### 2.11
Convert these decimal numbers to eight-bit 2’s complement binary
numbers.
a. 102
b. 64
c. 33
d. −128
e. 127
> [!solution]-
### 2.12
If the last digit of a 2’s complement binary number is 0, then the number
is even. If the last two digits of a 2’s complement binary number are 00
(e.g., the binary number 01100), what does that tell you about the
number?
> [!solution]-
### 2.13
Without changing their values, convert the following 2’s complement
binary numbers into eight-bit 2’s complement numbers.
a. 1010
 c. 1111111000
b. 011001
 d. 01
> [!solution]-
### 2.14
Add the following bit patterns. Leave your results in binary form.
a. 1011 + 0001
b. 0000 + 1010
c. 1100 + 0011
d. 0101 + 0110
e. 1111 + 0001
> [!solution]-
### 2.15
It was demonstrated in Example 2.5 that shifting a binary number one bit
to the left is equivalent to multiplying the number by 2. What operation
is performed when a binary number is shifted one bit to the right?
> [!solution]-
Integer division by 2
### 2.21
Describe what conditions indicate overﬂow has occurred when two 2’s
complement numbers are added.
> [!solution]-
### 2.22
Create two 16-bit 2’s complement integers such that their sum causes an
overﬂow.
> [!solution]-
### 2.23
Describe what conditions indicate overﬂow has occurred when two
unsigned numbers are added.
> [!solution]-
### 2.24
Create two 16-bit unsigned integers such that their sum causes an
overﬂow.
> [!solution]-
### 2.39
Write IEEE ﬂoating point representation of the following
decimal numbers.
a. 3.75
23
b. −5564
c. 3.1415927
d. 64,000
> [!solution]-
### 2.40
Write the decimal equivalents for these IEEE ﬂoating point
numbers.
a. 0 10000000 00000000000000000000000
b. 1 10000011 00010000000000000000000
c. 0 11111111 00000000000000000000000
d. 1 10000000 10010000000000000000000
> [!solution]-
### 2.41
a. What is the largest exponent the IEEE standard allows for a 32-bit
ﬂoating point number?
b. What is the smallest exponent the IEEE standard allows for a 32-bit
ﬂoating point number?
> [!solution]-



#todo After 1-16-25
### 2.42
A computer programmer wrote a program that adds two numbers. The
programmer ran the program and observed that when 5 is added to 8,
the result is the character m. Explain why this program is behaving
erroneously.
> [!solution]-
### 2.43
Translate the following ASCII codes into strings of characters by
interpreting each group of eight bits as an ASCII character.
a. x48656c6c6f21
b. x68454c4c4f21
c. x436f6d70757465727321
d. x4c432d32
> [!solution]-
### 2.44
What operation(s) can be used to convert the binary representation for 3
(i.e., 0000 0011) into the ASCII representation for 3 (i.e., 0011 0011)?
What about the binary 4 into the ASCII 4? What about any digit?
> [!solution]-
### 2.45
Convert the following unsigned binary numbers to hexadecimal.
a. 1101 0001 1010 1111
b. 001 1111
c. 1
d. 1110 1101 1011 0010
> [!solution]-
### 2.46
Convert the following hexadecimal numbers to binary.
a. x10
b. x801
c. xF731
d. x0F1E2D
e. xBCAD
> [!solution]-

