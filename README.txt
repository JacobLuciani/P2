Project builds on Project 1's option 3, FSA table

FSA table is stored as a variable in objects of Scanner class, described and built in Scanner.cpp as part of the function setupResources()
The driver is getNextToken(), which processes characters into a token using the FSA table and returns a Token variable

New functionality for parse tree is mainly in parser.h/c and testTree.h/c, with minor modifications elsewhere to adapt the program for this stage

To compile, run "make" command.