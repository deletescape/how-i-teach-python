# Syntax

Alright! It's time to say goodbye to the REPL and switch to a simple file editor. I suggest using Visual Studio Code or Atom for easy file switching and workespace management, but something like Notepad++ is sufficient for now.

I also suggest you to create a folder for this course with sub folders for all chapters for easy organization.

> To exit the REPL simply enter `exit()`

## Our first Python script

Now that we already know how to write some simple python code it is time to write our first script. For this create a file called `first.py` in the folder for this chapter.

For a simple demonstration of how scripts work copy the following into your file:

```python
print("Hello world!")
print("This is my first python script")
```
> As you can see there is always one command per line, and commands are only seperated by a line break. 

Navigate your terminal to the same folder as the script and execute it as follows.

```bash
$ python first.py
Hello world!
This is my first python script
$
```

> If you are on Linux/MacOS you might need to use `python3` as it might use Python 2 otherwise. On windows you can force the Python version by using `py -3` or `py -2` respectively

You should see the output of your print statements on your terminal now. Now try to use your knowledge from the initial chapter to extend the `first.py` script to calculate the circumference of a circle with a radius of 10. Make sure to print it out in a readable way.

<!-- We can probably think of a better example here instead of repeating exactly the same example from chapter 0 -->

If you get stuck you can look at the [example solution](/examples/1-syntax/first.py)

## Directors commentary

Sometimes some piece of code requires explaination or you need to note down something for your future self. Python like most other programming languages has the ability to add comments to the code itself for that purpose.

```python
# This is a comment

# The following line prints "Hello World!"
print("Hello World!")
```

Comments are only visible in the source file and are not printed to the terminal or executed. You can try this out yourself and add some comments to the script we just created if you want to.