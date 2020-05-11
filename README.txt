Project builds on Project 1's option 3, FSA table

FSA table is stored as a variable in objects of Scanner class, described and built in Scanner.cpp as part of the function setupResources()
The driver is getNextToken(), which processes characters into a token using the FSA table and returns a Token variable

New functionality for parse tree is mainly in parser.h/c and testTree.h/c, with minor modifications elsewhere to adapt the program for this stage

Note that syntax elements were kept in the parse tree, primarily for testing purposes. Keeping them in the output gives a full parse tree including all terminals from the source code, and they do not interfere with any functions of the parser

To compile, run "make" command.