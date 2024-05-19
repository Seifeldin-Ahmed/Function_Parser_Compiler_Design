# Functional_Parser_Compiler_Design


This project aims to implement a fully functional parser using c++ for a simple programming language. The parser consists of two main phases: lexical analysis (tokenization) and semantic analyzer (parsing). The lexer divides the input code into meaningful tokens and assigns them appropriate types. The parser then uses these tokens to construct a parse tree, which represents the hierarchical structure of the program. The output parse tree is visually represented in a suitable form, as described in lectures.

## Input Code Sample: 
```c++
int x = 1 ;
float y;
double temp;
while(x<3)
{
 y = 10.4;
 // z = 70;
 y = y + 3e1;
 
}
if(x==10)
  temp = 3.33;
else if(x <2)
   temp = 30;
else
   temp = 0;
```
   
## Parse Tree for this sample Code:
![parsetree](https://github.com/Seifeldin-Ahmed/Functional_Parser_Compiler_Design/assets/120275931/2e6c6de5-c2b4-4433-a094-327a06544793)
