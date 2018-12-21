# Unconditional love
<!-- Control flow (if/else/elif) -->
Not everything can be true, this also applies to programming, but `True` and `False` are used to conditionally execute code or to indicate a status. This kind of value is called a `boolean` often abbreviated as `bool`. To get a boolean value you can compare things using different boolean operations.

## Equality

You only want to check if your user has a certain name? We can easily do this!

```python
user = input("Enter your name: ")
print(user == "Vritz")
```
> Using `input()` you can get an input from the terminal

- `==` checks for equality between two values or variables.

## Greater/lower than

Let's also check if our user is an adult or not!

```python
age = int(input("Enter your age: "))
adult = age >= 18
teen = age > 12
```
> Using `int()` we can convert a string to a number

- `>` checks if a value is greater than the other value
- `>=` checks if a value is greater than or equal to the other value
- `>` checks if a value is lower than the other value
- `>=` checks if a value is lower than or equal to the other value