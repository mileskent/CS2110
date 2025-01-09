A method by which signed integers are represented. The best method for representing signed integers.
* Nonnegative integers represented the same way as unsigned integers.
* Negative integers "wrap around". 
* Avoids 0 having two representations, like [[Signed-Magnitude]]
* In this system you can direct add negative and positive integers and it just works.

| Decimal | 3 Bit 2's Complement |
| ------- | -------------------- |
| 3       | 011                  |
| 2       | 010                  |
| 1       | 001                  |
| 0       | 000                  |
| -1      | 111                  |
| -2      | 110                  |
| -3      | 101                  |
| -4      | 100                  |

### Convert Magnitude to 2's Complement
The process by which a unsigned integer is converted into its signed, negative counterpart:
1. Start with the absolute value, with the leading digit being the sign bit
2. Flip all of the bits
3. Add 1
> [!hint] Note
Moss's mnemonic for this is "flipping ink" -> flip & inc.

>[!Example]- Convert 01010011 to its negative 2's complement
01010011 -> 10101100 -> **10101101**
