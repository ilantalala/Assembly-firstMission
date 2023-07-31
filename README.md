In the following exercise for each id input there are 4 functions: 
Function number 1: prints the id.

Function number 2: for the decimal value of the second byte in the binary encoding of id we will interpret it in 2's complement terms and call it dec2. If 2_dec is odd then the result of multiplying id by 3 will be printed, otherwise the remainder of dividing id by 3 will be printed.

Function number 3: performs xor between the first byte and the third byte in the binary encoding of id. The received byte will be marked as 13_xor, and we will mark the decimal value of 13_xor when it is interpreted in unsigned terms to be 13_unsigned_dec. If 13_unsigned_dec is greater than 127 print True, otherwise print False.

Function number 4: prints the number of occurrences of 1 in the binary encoding of id in the fourth byte.

For example:
  The ID number is 123456789
  The four bytes are required for the binary representation, and they are: 00000111010110111100110100010101
The second byte is: 11001101 therefore 2_dec is 51 and hence it is odd. Multiply between
123456789 for 3- gives 370370367.
The first byte is 00010101 and the third byte is .01011011 therefore 13_xor is equal to 01001110 hence 13_unsigned_dec is equal to .78 78>127 and therefore False is printed.
The fourth house is 00000111, therefore the number of unity in it is.

##The assembly file is run on SASM##
