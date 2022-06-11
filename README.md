# BigInteger
 
Description
-----------

BigInteger represents integers, both positive and negative, as linked lists, with each node containing one digit of the integer. Each node with the digit points to the next one. Arithmetic operations are done on these integers.

The least significan digit is stored in the first node and the most significant digit is stored in the ending node. THerefore, the number 432 will be stored as 2 -> 3 -> 4

A boolean variable 'negative' is true if the integer in question is negative. This is because the negative sign will not be part of the linked list.

The function of the program is to take integers as user input, clean up any unnecessary spaces and symbols, store them as linked lists, and perform any desired operations
