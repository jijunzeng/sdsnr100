## 2020年11月 49题 程序设计语言的大多数语法现象可以用CFG (上下文无关文法)表示。下面的CFG产生式集用于描述简单算术表达式，其中+、-、*表示加、减、乘运算，id表示单个字母表示的变量，那么符合该文法的表达式为（  ）。
P:E→E+T|E-T|T
T→T*F|F
F→-F|id
> a+-b-c
> 本题首先排除 C，D 两个选项，从选项中和语法中没有数字和除法的表达，所以先排除。
> 根据题目给定的文法进行推导，E→E-T→E+T-T→T+-F-T→F+-id-id→id+-id-id→ a+-b-c

## 上下文无关文法 CFG Context free grammars
https://zhuanlan.zhihu.com/p/398264514?utm_id=0