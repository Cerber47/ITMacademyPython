# Dihitomia.py

When finding a root of a standart square equation is something could be done even by a weak student, a cubic(or equation with higher digree) is a totally diffrent strory. One way around is to guess as many root as possible and break an equation to a square eqution. As instance if we're having a problem of solving f(x, x^2, .. x^n) = a it is possible(with complex numbers) to bring it down

<img src="https://latex.codecogs.com/png.latex?f(x_0,&space;x,x^2,...x^n)&space;=&space;(x&space;-&space;x_n)(x&space;-&space;x_{n-1})&space;...&space;(x-x_1)"/> 

So how can we guess a root? The simple way is using Bisection method coded in Python. We want to be able to choose an epsilone(an error threshold), the equation itseld and the range. Error and f() we want to hardcode. The range should be set via terminal at the begging of programm runtime


## Requirements

- Programm should find one root of a equation if possible in a given range

## Notes

- It is not required to make user friendly interface. Programm must only solve the task given
