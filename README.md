# ProgramminLanguageDesign
Project for Formal Languages, Automata and Compilers
Developed as part of a team of 2.

It is an original programming language developed using YACC analyzer and LEX.
The language includes 
- predefined types 
- user defined data types
- array types
- variable declarations/definitions, constant definitions
- control statements, assignment statements
- function declarations
- arithmetic and boolean expressions
- operations with string types
- function calls 


The syntactic analysis of the program is implemented.
There is a symbol table for every input source program in the language.
The semantic analysis is provided for the following aspects:
- any variable that appears in a program has been previously defined
- a variable cannot be declared more than once
- a function cannot be defined more than once with the same signature
- a function that is called in the program has been defined
- accessing elements of arrays
 
