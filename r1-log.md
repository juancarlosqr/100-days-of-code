# #100DaysOfCode Log - Round 1 - Python

Started on: Wednesday, October 4, 2017

## Resources

- [100 Days Of Python](http://tecladocode.com/blog/100daysofpython/)
- [#100DaysOfPython](https://twitter.com/hashtag/100daysofpython?f=tweets&vertical=default&src=hash)
- [Link To Work](https://github.com/juancarlosqr/datascience/tree/master/python/100daysofpython)

## Log

### R1D0
kicking off this!

### R1D1
python setup and filtering learning resources
- [How to Setup Anaconda on Mac OSX](http://mrshipley.com/2016/09/19/how-to-setup-anaconda-on-mac-osx/)
- [Day 1: How to get started with Python](http://tecladocode.com/blog/learn-python-day-1-how-to-start-with-python/)
- [Introduction to Computer Science and Programming Using Python](https://www.edx.org/course/introduction-computer-science-mitx-6-00-1x-11)
- [Introduction to Python](https://www.udacity.com/course/introduction-to-python--ud1110)
- [Introduction To Python Programming](https://www.udemy.com/pythonforbeginnersintro/)
- [A Byte of Python](https://python.swaroopch.com/)
- [The Python Guru](http://thepythonguru.com/)
- [Dive Into Python 3](http://www.diveintopython3.net/)
- [Data Rebellion Python Resources](https://datarebellion.com/resources/)

### R1D2
refreshing basics like variables, string slicing and placeholders. also started udemy course
- [Day 2: What is programming all about?](http://tecladocode.com/blog/learn-python-day-2-what-is-programming-about/)

### R1D3
more on string formatting with .format and the new "f-string" syntax (python 3.6). I like this f-string syntax
- [Day 3: Key Python Building Blocks](http://tecladocode.com/blog/learn-python-day-3-first-look-at-python/)
- [Basics](https://python.swaroopch.com/basics.html)
- [The new f-strings in Python 3.6](https://cito.github.io/blog/f-strings/)

### R1D4
datatypes, numbers, operators and comparing, searching, testing and converting strings

- [Getting started with python](http://thepythonguru.com/getting-started-with-python/)
- [Datatype & Variables](http://thepythonguru.com/datatype-varibles/)
- [Python Numbers](http://thepythonguru.com/python-numbers/)
- [Python Strings](http://thepythonguru.com/python-strings/)

### R1D5
intro to functions and imports

- [What's New In "Dive Into Python 3"](http://www.diveintopython3.net/whats-new.html)
- [Chapter 1. Your First Python Program](http://www.diveintopython3.net/your-first-python-program.html)

### R1D6
operators, expressions, control flow and loops

- [Operators and Expressions](https://python.swaroopch.com/op_exp.html)
- [Control Flow](https://python.swaroopch.com/control_flow.html)
- [Day 5: Booleans and if statements in Python](http://tecladocode.com/blog/learn-python-day-5-booleans-if-statements/)
- [Day 6: For and While Loops in Python](http://tecladocode.com/blog/learn-python-day-6-for-and-while-loops-in-python/)

### R1D7
functions, named, default and variable args, modules

- [Day 4: Functions in Python](http://tecladocode.com/blog/learn-python-day-4-functions-in-python/)
- [Functions](https://python.swaroopch.com/functions.html)
- [Modules](https://python.swaroopch.com/modules.html)

### R1D8
intro to basic data structures like list, tuple, dictionary and set

- [Data Structures](https://python.swaroopch.com/data_structures.html)

### R1D9
more on list, tuples and intro to calendar module

- [Native Datatypes](http://www.diveintopython3.net/native-datatypes.html)

### R1D10
more on sets and dictionaries

- [Native Datatypes](http://www.diveintopython3.net/native-datatypes.html)
- [Day 7: Collections in Python](http://tecladocode.com/blog/learn-python-day-7-collections/)

### R1D11
comprehensions, iterable, iterators, and intro to generators

- [Day 7: Collections in Python](http://tecladocode.com/blog/learn-python-day-7-collections/)
- [List Comprehensions and Generator Expressions](http://djangostars.com/blog/list-comprehensions-and-generator-expressions/)
- [Python Generators](http://thepythonguru.com/python-generators/)

### R1D12
data type conversion, getting to know os and glob modules, and solving a math problem

- [Python Lists](http://thepythonguru.com/python-lists/)
- [Python Dictionaries](http://thepythonguru.com/python-dictionaries/)
- [Python Tuples](http://thepythonguru.com/python-tuples/)
- [Datatype conversion](http://thepythonguru.com/datatype-conversion/)
- [Python Control Statements](http://thepythonguru.com/python-control-statements/)
- [Python Functions](http://thepythonguru.com/python-functions/)
- [Python Loops](http://thepythonguru.com/python-loops/)
- [Comprehensions](http://www.diveintopython3.net/comprehensions.html)

### R1D13
more on comprehensions, more on math functions and random numbers

- [Comprehensions](http://www.diveintopython3.net/comprehensions.html)
- [Python Mathematical Function](http://thepythonguru.com/python-mathematical-function/)
- [Python Generating Random numbers](http://thepythonguru.com/python-generating-random-numbers/)

### R1D14
intro to reading and writing text, csv and json files

- [Day 8: Reading and Writing Files in Python](http://tecladocode.com/blog/learn-python-day-8-reading-and-writing-files-in-python/)

### R1D15
strings and bytes, decode/encode, unicode and utf-8

- [Strings](http://www.diveintopython3.net/strings.html)

### R1D16
more on file handling an intro to regular expressions

- [Python File Handling](http://thepythonguru.com/python-file-handling/)
- [Regular Expressions](http://www.diveintopython3.net/regular-expressions.html)

## Notes

- Everything in Python is an object
- Functions, Classes and Modules are first-class objects
- Everything is Case-Sensitive
- Variables
  - Python does not support in-line assignment, so there's no chance of accidentally assigning the value you thought you were comparing ```if version = 2```
- Data Structures
  - Integers can be arbitrarily large
  - Floating point numbers are accurate to 15 decimal places
  - The `int()` function will truncate, not round
  - Python does not have infinite precision. `tan(π / 4)` should return `1.0`, not `0.99999999999999989`
  - Lists are mutable
  - Tuples are immutable
  - Tuples are faster than lists
  - You can use only immutable objects (like strings, integers, tuples) for the keys of a dictionary but you can use either immutable or mutable objects for the values of the dictionary
  - Sequences are strings, list and tuples
  - The third argument on slicing is the step. `shop[2:100:2]`
  - If the value is not found in a list, the `index()` method will raise an exception, not like in other languages that return an invalid index like `-1`. `list[-1]` is a valid statement
  - Sets are unordered collections of simple objects. These are used when the existence of an object in a collection is more important than the order or how many times it occurs
  - To make a copy of a list or such kinds of sequences or complex objects (not simple objects such as integers), then you have to use a full slicing operation to make a copy
  - For Sets the `union`, `intersection`, and `symmetric_difference` operations are symmetric. `difference` is  not
- Bytes and Encoding
  - In Python 3, all strings are sequences of Unicode characters
  - An immutable sequence of Unicode characters is called a string
  - An immutable sequence of numbers-between-0-and-255 is called a bytes object
  - Bytes are not characters; bytes are bytes. Characters are an abstraction. A string is a sequence of those abstractions
  - In Python 2, the default encoding for .py files was `ascii`. In Python 3, the default encoding is `utf-8`
  - To specify source file encoding use `# -*- coding: [ENCODING] -*-`
- Operators
  - Operators with the same precedence are evaluated in a left to right manner (```5 + 9 - 4```)
- Regular Expressions
  - `import re`
  - Always use raw strings when dealing with regular expressions. `r'\bSTREET'`
  - `^`: start of the string
  - `$`: end of the string
  - `?`: optional match
  - `\b`: a word boundary must occur right here
- Control Flow
  - There is no ```switch``` statement in Python. You can use an ```if..elif..else``` statement to do the same thing (and in some cases, use a [dictionary](https://python.swaroopch.com/data_structures.html#dictionary) to do it quickly)
  - ```while``` and ```for``` statements can have an optional ```else``` clause
  - If there is an ```else``` clause for a ```while``` or ```for``` loop, it is always executed unless you break out of the loop with a ```break``` statement
- Iterable, Iterators and Generators
  - Iterable is a "sequence" of data
  - Iterator protocol is implemented whenever you iterate over a sequence of data
  - Generators are functions used to create iterators, so that it can be used in the for loop
  - Generators provide a convenient way to implement the iterator protocol
  - Generator is an iterable created using a function with a yield statement
  - The main advantage of generator over a list is that it take much less memory
- Functions
  - Every function in Python returns `None` unless we return something different
  - The `pass` statement is used in Python to indicate an empty block of statements
  - You cannot have a parameter with a default argument value preceding a parameter without a default argument value in the function's parameter list. `def func(a=5, b)` is not valid
  - When we declare a starred parameter such as `*param`, then all the positional arguments from that point till the end are collected as a tuple called `param`
  - When we declare a double-starred parameter such as `**param`, then all the keyword arguments from that point till the end are collected as a dictionary called `param`
  - As soon as you have a named argument, all arguments to the right of that need to be named arguments, too. `func(a=3, b)` is not valid
  - The convention followed for a `docstring` is a multi-line string where the first line starts with a capital letter and ends with a dot. Then the second line is blank followed by any detailed explanation starting from the third line
- Exceptions
  - Some programming languages encourage the use of error return codes, which you check. Python encourages the use of exceptions, which you handle
- Modules
  - A module's ```__name__``` depends on how you're using the module. If you import the module, then ```__name__``` is the module's filename, otherwise will be a special default value, ```__main__```
  - In general, avoid using the `from..import` statement, use the `import` statement instead. This is because your program will avoid name clashes and will be more readable. Avoid using `from module import *` as well

__Keywords in Python 3__

![Keywords in Python 3](./img/keywords.png "Keywords in Python 3")

__Operators__

![Operators](http://i0.wp.com/thepythonguru.com/wp-content/uploads/2015/08/python-operators.jpg?w=416 "Operators")

__Operators Precedence__

[Source](https://docs.python.org/3/reference/expressions.html#operator-precedence)

![Operators Precedence](./img/operators.png "Operators Precedence")

__Augmented Assignment Operators__

![Augmented Assignment Operators](http://i0.wp.com/thepythonguru.com/wp-content/uploads/2015/08/python-augmented-assignment-operators.jpg "Augmented Assignment Operators")

## Review

- Bit-wise operations ([link](https://stackoverflow.com/questions/11810113/how-do-bitwise-operations-work-in-python))
  - left/right shift (`<<|>>`)
  - `AND|OR|XOR|invert`
- Packages (https://python.swaroopch.com/modules.html#packages)
- There is no way of getting the index of a list in a `for...in` expression?. `for index, day in my_list:` throws following Exception `ValueError: too many values to unpack`

## The Zen of Python, by Tim Peters

Run `import this`

```
Beautiful is better than ugly.
Explicit is better than implicit.
Simple is better than complex.
Complex is better than complicated.
Flat is better than nested.
Sparse is better than dense.
Readability counts.
Special cases aren't special enough to break the rules.
Although practicality beats purity.
Errors should never pass silently.
Unless explicitly silenced.
In the face of ambiguity, refuse the temptation to guess.
There should be one-- and preferably only one --obvious way to do it.
Although that way may not be obvious at first unless you're Dutch.
Now is better than never.
Although never is often better than *right* now.
If the implementation is hard to explain, it's a bad idea.
If the implementation is easy to explain, it may be a good idea.
Namespaces are one honking great idea -- let's do more of those!
```