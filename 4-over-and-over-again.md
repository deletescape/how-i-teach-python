# Over and Over Again

Doing things multiple times is often a necessity in programming. Most languages, python included, provide support for this in the form of **loops**. Loops come in multiple types, each with its specific purpose. Quick summary of each type and what it does:

- **for loop**: Used to run a loop *for* a given number of times, which is decided by a conditional.

- **while loop**: Run a specific block again and again *while* a provided condition is true.


## Examples

Wanna find the factorial of a number? Piece of cake!
```python
number = int(input("Enter number to find its factorial: "))
n, factorial = number, 1 #Assigning a counter and result variable, we'll need them.
 # We'll be taking 1 off n every time the loop runs, but we need to know when to stop
while n > 0:
    factorial *= n
    n = n - 1
print("Factorial of %d is %d" % (number, factorial)) # String formatting fun, more on this in a separate chapter.
```
