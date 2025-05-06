
For Compilation and execution:
1. lex prl.l
2. bison –d prl.y
3. cc lex.yy.c prl.tab.c -ll
4. ./a.out
