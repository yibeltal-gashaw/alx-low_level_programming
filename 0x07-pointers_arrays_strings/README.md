<html>
<h1>Even more pointers, arrays and strings</h1>
<p>A pointer is a variable which contains a memory address.</p>
               <h2>Types and memory</h2>
<p>Every time you declare a variable, the computer will reserve memory for this variable. The memory reserved will then store the value of the variable.
Depending on the type of the variable, the computer will reserve more or less memory. The size of each type is generally defined in bytes (1 byte = 8 bits, each bit being 0 or 1). The sizes of the types also depend on the computer you are using. Here are the sizes of the most common types on most 64-bit Linux machines:</p>
<li>char -> 1 byte</li><br>
<li>int -> 4 bytes</li><br>
<li>float -> 4 bytes</li><br>
To determine the size of those types on your computer, you can use the `sizeof` operator.
The size of a type will determine how many different possible values a variable of this type can hold. For instance, a char variable could only hold 256 (2^8, 8 being the number of bits) different values: from -128 to 127. And because the size of int is 4 bytes, so 32 bits, an int variable can hold 2^32 different possible values.

When we declare a variable, the computer will reserve the right amount of space for the variable in the memory (depending on its type). The space reserved for the variable is its address. And when we assign a value to this variable, the computer will store this value at its address.
</html>

