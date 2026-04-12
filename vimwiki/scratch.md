1. NAND

!(A & B)

using De Morgan's Law for AND form

!(A * B) = !A + !B, use !(A * B) since it is minimal in terms of gates

A = 0 , B = 0, C = 1
A = 1, B = 0, C = 1
A = 0, B = 1, C = 1
A = 1, B = 1, C = 0

If A & B are 0 then its 1.  

2. NOR

!(A | B) 

using De Morgan's Law for OR form 

!(A + B) = !A * !B, use !(A + B) since it is minimal in terms of gates

A = 0, B = 0, C = 1
A = 1, B = 0, C = 0
A = 0, B = 1, C = 0
A = 1, B = 1, C = 0

3. XOR

(A ^ B)

Using a truth table

A = 0, B = 0, C = 0
A = 1, B = 0, C = 1
A = 0, B = 1, C = 1
A = 1, B = 1, C = 0

XOR = A!B + !AB

4. Mux or selector

!sa + sb


5. Selector-4 
   
!s1 !s0 a + !s1 s0 b + s1 !s0 c + s1 s0 d

!s1(!s0 a + s0 b) + s1(!s0 c + s0 d)







