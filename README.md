brainfuck
=========

Experimentation with an odd, compact programming language.

The most useful feature of this language appears to be the ability to output an ASCII character using the operator ".", based on the character's decimal numeric value. It also has the ability to receive input characters from stdin, using the ',' operator.

Think of it as a Turing-complete, eight-command language (+-<>[],.) with a series of 30,000 byte counter cells, each able to store one integer. Calling the "." operator with the pointer positioned on a cell will output the ASCII equivalent of the integer stored within. 

You can reference the ASCII chart here, for example:
https://en.wikipedia.org/wiki/Ascii

Another interesting feature is that anything in the code which is not one of the 8 commands is ignored by the interpreter. Therefore, you can comment your code inline without any special syntax.

Some rainy-day code samples contained herein... some commented for explanation... Enjoy?
