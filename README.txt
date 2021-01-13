1. 
(1) For pow() function, python program could support calculation for the number bigger than 2^31, while my compiler couldn't. 
Maybe we could design a BigInteger type to handle larger number in our compiler.

(2) Python program support parentheses' parsing, while ours couldn't.
We can extend our compiler to check whether parentheses are valid and modify the calculation priority, if there exists brackets.

(3) Our compiler doesn't support floating calculation such as pow(2,-1), we get 0 rather than 0.5 in python program.
To handle this, we might create overload function for pow() to handle different kinds of input parameters.

2. This project took me about 5 hours to finish. The part of handling negative number took the longest.

3. I will tell myself to read instuction more carefully before get started and read each part of the program first.

4. https://learnxinyminutes.com/docs/wasm/

5. I did pa1 myself.