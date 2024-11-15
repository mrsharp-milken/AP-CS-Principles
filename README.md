*TIP: Open me with right-click >> Open Preview or click the icon in the upper right with the magnifying glass.*

## Terminal Commands:

| Description | Command |
|---|---|
| Move into a folder (change directory) | `cd ____` |
| Move back to home folder | `cd` |
| Create a folder (make directory) | `mkdir ____` |
| **C** - create a C source code file | `code ____.c` |
| **C** - Compile C source code to machine code | `make ____` |
| **C** - Run a machine code file | `./____` |
| **Python** - create a python source code file | `code ____.py` |
| **Python** - Run a python file | `python ____.py` |

## Code Samples - C

```c
// Print an integer
int score = 12;
printf("Num: %i\n", score);

// Print a string
string name = "Mr. Sharp";
printf("String: %s\n", name);

// For loop 0-9
for (int i = 0; i < 10; i++)
{
    printf("Loop: %i\n", i);
}

// If and else
if (num > 90)
{
    printf("Grade: A\n");
}
else if (num > 80)
{
    printf("Grade: B\n");
}
else
{
    printf("Grade: C\n");
}
```

## Code Samples - Python

```python
# Print a number
score = 12
print("Num:", score)

# Print a string
name = "Mr. Sharp"
print("String:", name)

# For loop 0-9
for i in range(0, 10):
    print("Loop:", i)

# If and else
if num > 90:
    print("Grade: A")
elif num > 80:
    print("Grade: B")
else:
    print("Grade: C")
```

## debug50 Debugger

The debug50 debugger is best used when your code compiles and runs, but doesn't do what you expect it to.

1. Compile your program with `make ____` (only needed for C)
2. Set a breakpoint in your code by clicking to the left of a line number and adding a red dot.
3. Run the debugger with `debug50 ./____` (for C) or `debug50 python ____.py` (for python)
4. Wait a bit for the debugger to start up
5. The debugger will pause at the breakpoint. You can then use the "Step Forward" and "Step Into" buttons to move through your code

## CS50 AI Duck

The CS50 AI duck is best used when you're trying to figure out a compile error, or you want some hints at where to go next.

1. Go to [cs50.ai](https://cs50.ai/) or click the duck icon on the far left sidebar.
2. Paste in your compile error, or ask your question
3. Carefully read the duck's response

Remember, the CS50 AI Duck is not perfect! It's usually very good at helping with compile errors, but it might not always give you the best answer.

## Add your own notes!

Got something else you need to remember frequently? Add to this file with your own notes!

This is a "Markdown" file, a common file type used by programmers to write documentation. It doesn't have all the features of Google Docs (like changing text colors), but it can do a few things **bold**, *italics*, `code blocks`, and [links.](https://cs50.harvard.edu/ap/2025/curriculum/)

[Here's a documentation link with a list of markdown features.](https://www.markdownguide.org/cheat-sheet/) You can always just type it normally too.

## Add this to your codespace:

1. Open your cs50.dev codespace, and open the terminal
2. Run this command:
```
wget https://raw.githubusercontent.com/mrsharp-milken/AP-CS-Principles/refs/heads/main/README.md
```
4. Right click the new file named `README.md` then choose "Open Preview"
5. You can also drag the tab to the right to split the screen into two tabs.
