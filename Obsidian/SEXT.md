"Sign-Extension"
Given 0000000000001101 + 111011, where both are signed ints, direct addition ruins the value of the 6 bit integer. Because of this, we extend the sign so that the addition is accurate: 
0000000000001101 + 1111111111111011 = 0000000000001000