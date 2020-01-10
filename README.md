# Compile-formula-with-Fast-solver

1. Fast solver: Compile formula into a function. Also return letters found, as a str, in same order as parms of function. The first digit of a multi-digit number can't be 0. So if YOU is a word in the formula, and the function is called with Y eqal to 0, the function should return False. Given a formula like 'ODD + ODD == EVEN', fill in digits to solve it. Input formula is a string; output is a digit-filled-in string or None. This version precompiles the formula; only one eval per formula.

2. compile_word (enumerate()): Compile a word of uppercase letters as numeric digits. E.g., compile_word('YOU') => '(1U+10O+100*Y)' Non-uppercase words unchanged: compile_word('+') => '+'
