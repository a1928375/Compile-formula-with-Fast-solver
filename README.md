# Fast-solver

Compile formula into a function. Also return letters found, as a str, in same order as parms of function. The first digit of a multi-digit number can't be 0. So if YOU is a word in the formula, and the function is called with Y eqal to 0, the function should return False. Given a formula like 'ODD + ODD == EVEN', fill in digits to solve it. Input formula is a string; output is a digit-filled-in string or None. This version precompiles the formula; only one eval per formula.
