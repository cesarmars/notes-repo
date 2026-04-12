# Bias in Number Representation

We have values that are  negative and  positive, signed integers. 

Now we want to encode them using only unsigned binary. 
We can shift the numbers so they center on zero. 

In order to do that, bias is stated as
-> 2^(n-1) - 1

**To interpret stored binary**
- actual value = stored(unsigned integer) + bias

**To store a data value**
- stored = actual value - bias

 # Example
Lets assume that we have a bias of -127 with an 8 bit number, 0b0000 1001.

If we want to interpret the binary 0b0000 10001 = 9, we mean

-> actual value = 9 + (-127) = -118

If we want to store the binary 0b0000 1001 = 9, we mean

-> stored = 9 -(-127) = 136

136 to binary
128 64 32 16 8 4 2 1 = 0b1000 1000

So, 9 is stored as unsigned binary 0b1000 1000

# Example 2

Store -9 as unsigned binary representation using 8 bits.

**First**
Find the bias using the n bits.
-> 2^(n-1) - 1 = 2^(8-1) - 1 = 2^7 - 1 = 127

**Second**
Find the stored value
-> stored = -9 + 127 = 118 

118 to binary 
128,64,32,16,8,4,2,1 = 0b0111 0110

So -9 is stored as an unsigned binary 0b0111 0110






 
