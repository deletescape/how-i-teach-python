# Grocery Lists
<!-- Lists -->
When we go shopping, we don't have multiple papers with one item on each. We usually just have one paper with many items on it making it a list. A `list` is a useful data type that allows us to store many items of similarity such as grocery items. The items within a list can be strings, booleans, integers, floats, tuples, and even lists.

## Creating a List
To create a list, you only have to surround elements which are just values divided by square brackets.

```python
[element1, element2, element3]

#Assigning a list to a variable
grocery_list = ['Apples', 'Donuts', 'Cake']
```
## Using the string oberator on lists

One of the great things about python is that you can easily gain access and configure lists with the string operator.

```python
grocery_list = ['Apples', 'Donuts', 'Cake']

print(grocery_list[0]) # Will print out 'Apple' since 'Apple' is at index 0
```
The slice operator is formatted as such: yourList[start:stop:step]
```python
print(grocery_list[0:2] 
# Will print out 'Apple' 'Donuts' since the string operator starts at 0 and stops before 2

print(grocery_list[::2])
# Will print out 'Apple' 'Cake' since the string operator starts at the beginning which is 0 and counts up by 2
```

## Methods

There are many methods out there, but here are some useful ones.

`list.pop(index value)` Removes the value at a specific index and return. No argument will return the last element in the list.

`list.append(element)` Adds an element to the end of the list.

`list.insert(index, element)` Adds an element to a specific index of the list.
