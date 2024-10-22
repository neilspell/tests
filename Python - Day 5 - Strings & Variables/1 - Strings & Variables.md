# Strings & Variables 📚

![image](image_8.png)

We have already explored how _Strings_ and _Variables_ can be used in our programs _(look back over Intro to Python - Day 1)_

Remember we saw that strings are like _words_ and _sentences_ for computers.

# Strings 📝
Strings are like _words_ and _sentences_ for computers.

A string is just a bunch of characters put together.

Characters can be letters, numbers, symbols, or even spaces. 
(e.g. ``"Hello, World!"`` is a string because it's made up of the characters ``H``, ``e``, ``l``, ``l``, ``o``,``space``, ``W``, ``o``, ``r``, ``l``, ``d``, and ``!``, all in a specific order.

Strings are super useful because they let us work with **_text_** in computer programs.

You can do all sorts of things with strings, like:

    - Displaying text: You can show messages or information to people on the computer screen.
    - Receiving text: You can receive information from Users as they type into the computer.

So, think of **_strings_** as the way computers understand and work with words and text.

In todays' tutorial, we are going to look at some more complex uses of strings and variables.

## Task 1 - Character Counter - Parson's Problem 🤔

> Try to complete the following tasks in `main.py`

-  Ask the user to enter a word or phrase.
-  Calculate and store the number of characters in the input using the `len()` function.
-  Print out the number of characters along with the input using **_string concatenation!_**
-  You can learn more about the `len` function [here.](https://www.w3schools.com/python/python_strings.asp)


````py
# Task 1
# Rearrange & edit the code below to get your program to work.
user_input = input("")

num_characters = 

print()

len(user_input)

"The input, contains, characters."

````

## Task 2 - fStrings 📚
We have looked at using the `print ()` and `input ()` functions while handling strings.
Today, we are going to look at `fStrings`.

- `fStrings`, or _"formatted string literals"_, are a feature introduced in Python 3.6 for convenient and readable string formatting. 
- They provide a concise and expressive way to embed expressions inside string literals.
- They start with the letter `f` and are created by enclosing expressions in curly braces `{ }` within a string.

> Try this example yourself in `main.py`:
````py
# Example of fStrings

name = "John"
age = 25

# fString
message = f"Hello, {name}! You are {age} years old."

# Print Output: "Hello, John! You are 25 years old."
print(message)

````

In this example, ``{name}`` and ``{age}`` inside the f-string are placeholders for the values of the name and age variables. 

When the f-string is evaluated, the expressions inside the curly braces are replaced with their respective values.

<details>
<summary> 👀 Further Reading </summary>

Key features and advantages of ``fStrings`` include:

1. _Readability:_

``fStrings`` enhance code readability by allowing you to embed variables and expressions directly into the string.

2.  _Simplicity:_

``fStrings`` eliminate the need for explicit conversion of variables to strings, as this is handled automatically.

3.  _Expressions:_

You can include expressions inside the curly braces, allowing for more complex and dynamic string formatting.

4. _Performance:_

``fStrings`` are often faster than other string formatting methods, contributing to better runtime performance.
  
</details>


