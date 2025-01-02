Series of projects that discover the fundamentals of programming languages by building one from scratch. 
All programs are recieved as .txt files. 

First, there is a lexer. A lexer breaks down a program into the smallest possible pieces that have semantic meaning. This is called tokenizing.

Next, we use the rules of Context Free Grammars to create a parse tree from our tokens. This is done using FIRST and FOLLOW sets which is a common technique used in parsing theory. 

Lastly, we create a Directed Cyclic Graph of instructions (the intermediate representation of our program). 
