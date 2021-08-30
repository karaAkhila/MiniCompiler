# MiniCompiler
A mini compiler for Javascript

Command for executing in linux:

ICG:

flex lex.l && bison -d -y yacc.y && gcc y.tab.c lex.yy.c -ll && ./a.out <ip
                                                                            
Optimization:
                                                                            
flex lex.l && bison -d -y par.y && gcc y.tab.c lex.yy.c -ll && ./a.out <ip
