# Compiler
Analysis the syntax and semantics of the code (Language description is attached inside).
To run this project you need to use linux based terminal.
Lunch the terminal and change the directory to the project folder.
run the commands by this order:

1) lex project1.l
2) yacc project1.y
3) gcc -o project1 y.tab.c -ll -Ly

* Create a txt file - project1.txt, with the code you want to check (check language description).

4) ./project1<project1.t
