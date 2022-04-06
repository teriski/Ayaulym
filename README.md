# Ayaulym
Asylbekova
from numpy import*
from sympy import*
x = symbols('x')
function1 = x**2 + 2*x + 1
x_sol = solve(function1, x)
print(function1)
print('solution:')
print(x_sol) 
