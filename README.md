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


x = smp.symbols('x')
function2 = (1-cos(x**2))/(x**2*sin(x**2))
limit_sol=limit(function2, x, 0)
print(function2)
print('solution:')
print(limit_sol)  
