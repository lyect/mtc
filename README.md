# Methods of translation and compilation

Repository for storing solved tasks on the subject "Methods of translation and compilation".

Tasks are being solved using [flow9](https://github.com/area9innovation/flow9). This is the requirement of a teacher at the university.

Tasks were splitted between four blocks. Here is the list of blocks:
  * Getting to know flow9
  * Parsers and AST
  * NeMo language (from russian "**Не**детерминированный **Мо**дельный язык")
  * Formal verification for HeMo

Here is the list of solved blocks of tasks:

## Block #1 : Getting to know flow9
This block contains simple tasks for getting to know the flow9.
Task list:
  * **(1)** Write a function which transforms array of integers to array of strings.
  * **(2)** Write a function which calculates sum of an array.
  * **(3)** Write a function which calculates first _n_ Fibonacci numbers. Here are three subtasks:
    * **(3.1)** Make it with naive recursion.
    * **(3.2)** Make it with tail call.
    * **(3.3)** Make it with references to an array.
  * **(4)** An array of integers _A_ and integer _m_ are given. Write a function which finds all pairs of indexes (i, j) such that i < j and _A_[i] + _A_[j] == _m_. Here are two subtasks:
    * **(4.1)** Make it with complexity O(n<sup>2</sup>) using nested loops.
    * **(4.2)** Make it with complexity O(nlogn) using binary searching tree.

## Block #2 : Parsers and AST
The main task - to write a arithmetic expression parser.
There are two topics in this block: making a grammar for arithmetic expressions, making a parser.
Task list:
  * **(5)** Write a PEG-parser using built-in library lingo. On this step, expressions may only consists of addition and multiplication.
  * **(6)** Transform parsed expression back to string form.
  * **(7)** Make a function for evaluating parsed expressions.
  * **(8)** Add variables.
  * **(9)** Add powers, division and substraction.
  * **(10)** Make function for simplifying expressions.
  * **(11)** Add derivatives.
  
## Block #3 : NeMo language
The main task - write a compiler for NeMo.
This task was done in a big rush due to end of a semester. So, code is fetid. That's the reason why I don't want to add it.

## Block #4 : Formal verification for nemo
This block was not done.
