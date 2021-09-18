# f-strings

F-strings provide a way to embed expressions inside string literals, using a minimal syntax. 

It should be noted that an f-string is really an expression evaluated at run time, not a constant value. In Python source code, an f-string is a literal string, prefixed with 'f', which contains expressions inside braces.

For example:-
```
name = "Mukul"
print(f'My name is {name}')
```
