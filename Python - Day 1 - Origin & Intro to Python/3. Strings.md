# Strings 📚

We now know that using `print( )` will display a message on the console.
Whatever we place inside the `" "` quotation marks will be printed on the screen.

Text surrounded by `" "` is called a **_String._**

Example:
````py
print("Hello, World!")
print("Goodbye")
print("Who lives in a pineapple under the Sea?")
````
These are all **_Strings._**

## Strings 📝
Strings are like _words_ and _sentences_ for computers.

Imagine you have a piece of paper, and you can write down words, sentences, or even a whole story on it. In the computer world, we use something called "strings" to do something similar.

A string is just a bunch of characters put together.

Characters can be letters, numbers, symbols, or even spaces. 
(e.g. ``"Hello, World!"`` is a string because it's made up of the characters ``H``, ``e``, ``l``, ``l``, ``o``,``space``, ``W``, ``o``, ``r``, ``l``, ``d``, and ``!``, all in a specific order.

Strings are super useful because they let us work with **_text_** in computer programs.

You can do all sorts of things with strings, like:

- Displaying text: You can show messages or information to people on the computer screen.
- Receiving text: You can receive information from Users as they type into the computer.

So, think of **_strings_** as the way computers understand and work with words and text.

## Task 4 - Line Spacing & New Line
(a) Try to print "Monty Python" twice on the same line. 

In `main.py`, underneath Task 4 type the following...

````py
print("Monty Python")
print("Monty Python")
````

### What happens?
Chat with your classmates and see if you can figure out why this happens.

<details>

<summary> 👀 Hint</summary>

  Try this
  ````py
  print("Monty Python", end = "")
  print("Monty Python")
  ````
</details>

### Questions to make you think 🤔 
- What happens if we include a space inside the double quotes `" "`?
- What happens if we include a comma `,`inside the double quotes `","`?

Imagine we now want to add a new line, but we are lazy and don't want to have to use 2 ``print`` statements.

(b) Type this line of code and see what it does:

````py
print("Monty Python\nand The Holy Grail")
````

Experiment with what we have just learned and see how it changes your output.








