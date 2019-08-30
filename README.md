# jupyter_keyboard_shortcuts

Keyboard Shortcuts Practice

Taking a few minutes to learn certain Jupyter Notebook keyboard shortcuts has helped me be a more efficient Python developer. Below are the keyboard shortcuts I've found most useful.

NOTE these keyboard shortcuts are for Jupyter version 4.1.0 and Mac OSX. For most shortcuts below, you can replace cmd for ctrl for Windows or Linux. Or, you can use the H keyboard shortcut in Windows or Linux to confirm the appropriate keyboard shortcuts for those operating systems.
Command vs. Edit Modes

But first...something key to be aware of: Jupyter Notebooks have two different keyboard input modes:

    Command mode - binds the keyboard to notebook level actions. Indicated by a grey cell border with a blue left margin.
    Edit mode - when you're typing in a cell. Indicated by a green cell border

Experiment with switching between command and edit modes in this cell. Hint: If you're in command mode, type enter to enter edit mode. If you're in edit mode, type esc to enter command mode.
Command Mode

Let's practice the command mode first.

To start, select the next cell and click shift + enter to run that cell and select the next cell
In [ ]:

print("You just ran the cell and selected the next cell")

With the next cell selected, click ctrl + enter to run the cell and keep the same cell selected
In [ ]:

print("You just ran the cell and the focus stayed in that cell")

With the next cell selected, click option + enter to run the cell and insert a new cell below
In [ ]:

print("You just ran the cell and inserted a new cell below it")

Click A to insert a new cell above this one

Then, click B to insert a new cell below.

Copy the next cell with C and then paste it with V
In [ ]:

print("copy me")

Delete the cell below by selecting it and typing D, D (i.e., hit the D button twice)
In [ ]:

print("delete me")

Merge the following two cells by selecting the first one and then typing shift + M
In [ ]:

print("click me and then merge me with the next cell")

In [ ]:

print("merge me with the cell above")

Experiment with changing the following cells to code and markdown modes
In [ ]:

```
print("I should be in Markdown mode. Type `M` to change me to markdown. Then type `shift` + `enter` to see the proper markkup")
```

print("I should be code. Select me and then type Y to change me to code mode`")
Edit Mode

Use the cmd + click to quickly change all occurences of variable_x to var_x
In [ ]:

variable_a = 1
variable_b = variable_a*2
variable_c = variable_a + variable_b

Use option + hold click for column editing to easily indent each of the following linex_fix_indents
In [ ]:

def my_func():
line1_fix_indent
line2_fix_indent
line3_fix_indent
line4_fix_indent
line5_fix_indent
line6_fix_indent
line7_fix_indent
line8_fix_indent

Select the entire text in the next cell and click cmd + / to toggle comment lines
In [ ]:

print("this")
print("is")
print("a big")
print("block of")
print("text to comment")

Run the next cell to import numpy and then put your cursor next to the np. in the following cell. Then, press tab to see what code completions are available
In [ ]:

import numpy as np

In [ ]:

np.

Put your cursor between the () in the np.arange() code below. Then press shift + tab to get the tooltip
In [ ]:

np.arange()

Use ctrl + shift + - split the following cell between the two functions
In [ ]:

def func1():
    print("I'm func1. Separate me from func2")
    
def func2():
    print("I'm ")

Command Palette

cmd + shift + p

Want quick access to all the commands in Jupyter Notebooks? Open the command palette with cmd + shift + p and you'll quickly be able to search all the commands!
View all keyboard shortcuts

H (in Command mode)

Forget what that keyboard shortcut is? Type H in Command mode for a list of all available keyboard shortcuts.
