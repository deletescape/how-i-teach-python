# Origin

We'll by using the python REPL for this initial introduction, so all you'll need is a working Python 3 installation and a terminal.

> REPL stands for Read Eval Print Loop and stands for an interactive programming environment where user input is directly executed. It's basically a "chat for code" in it's basics.

## Hello world

I don't think it is possible to learn any new language without starting out with a simple "Hello World" program. In Python this is actually extremely easy, and can be written in just one simple line:

```python
print("Hello World!")
```

If you enter this in your Python terminal you should immediately see it greeting the entire world.

```python
>>> print("Hello World!")
Hello World!
>>>
```

## Let's do some math!

Computers are very great at math, and we can use Python to tell the computer exactly what it should calculate for us. Let's try some simple examples.

```python
>>> 1 + 1
2
>>> 2 * 2
4
>>> 4 / 2
2.0
>>>
```

### Variables

Alright, so we could have probably just used a calculator \(or our brain\) for that instead, so let's make it a bit more interesting by introducting variables. Variables in programming are actually somewhat similar to those in maths. They are a named store for variable values which can be reused in multiple places. One difference is that computers don't like unknown things so we always have to define all variables for them.

Let's define pi as a variable!

```python
>>> pi = 3.14159
>>>
```

We can now use the `print` function we already used earlier to check the content of the `pi` variable.

```python
>>> print(pi)
3.14159
>>>
```

We can also use our `pi` variable in a more practical example now, for example calculate the circumference of a circle with a radius of 5.

```python
>>> radius = 5
>>> 2 * pi * radius
31.4159
>>>
```

## Hello User!

It's time for text! Programmers usually refer to text as strings, because text is essentially just a string of characters and that's how text is represented on a computer.

We actually already used our first string in the Hello World example we made at the start. A string in python (and many other languages) is denoted using quotes like `"this"`, python also allows using `'single quotes'` for strings.

You can also create variables with a string value, you can obviously use your own name in this example.

```python
>>> user = "Till"
>>>
```

### Let's do some math!

Wait what? Math with text?

Well it's not exactly math, but you can use the same operators used for math to do some cool stuff with strings!

```python
>>> "Hello " + "World" + "!"
'Hello World!'
>>> "Repeat after me " * 2
'Repeat after me Repeat after me '
>>>
```

> Adding multiple strings to each other is called concatenation

We can now use this to greet ourselves instead of the entire world, because as stereotypical programmers we obviously don't want any social contact.

```python
>>> user = "Till"
>>> print("Hello " + user + "!")
Hello Till!
>>>
```

#### Concatenating strings and numbers

You can concatenate numbers to a string as if they were a string as well by using `str()`. This converts the number to a string.

```python
>>> print("The meaning of life is " + str(42))
The meaning of life is 42
>>>
```