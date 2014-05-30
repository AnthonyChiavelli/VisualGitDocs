.. _code_style:

===============================
Python Coding Style Conventions
===============================

1. Whitespace
=============

1.1. Indentation
----------------

* Lines should be indented with a multiple of 4 spaces depending on indent level
* Hanging indents, code that is a continuation of the line above, should be indented to the next level
* Use spaces exclusively, no tabs!

1.2. Blank Lines
----------------

* Leave 2 blank lines between class definitions and module-level functions
* Leave 1 blank line between methods in a class
* Use blank lines as needed in functions, methods, and modules to visually split up logical blocks of code

1.3. Spaces In Code
-------------------

* Surround binary operators with a space on each side
* Do not include spaces around '=' when used to indicate a default argument or keyword argument
* In all other cases, extraneous spaces are frowned upon

2. Imports
==========

* Imports should occur at the top of the module, after any module docstring
* Standard imports (those beginning with "import") should each be on a separate line. Do not combine imports into one line.
* "From ... import ..."-style imports may be combined together on one line if possible
* Wildcard imports should only be used when absolutely necessary, otherwise only import the modules to be used

3. Code Blocks
==============

* Do not use parenthesis in the condition for a code block header unless it would be otherwise appropriate to use parenthesis around that condition
* Do not use any single line code blocks. Even those with a single statement in the body should occupy multiple lines


4. Comments
===========

* First and foremost, comments should be up to date and accurate. When updating code, always make sure to update any comments that refer to it
* Comments should be wrapped to 72 characters
* Use plain English sentences with proper spelling and grammar. Strongly prefer complete sentences.
* Single sentence comments need not end in a period
* Clever humor is acceptable on occasion
* Do not merely summarize the code that follows. State its overall purpose, justify its inclusion, or explain quirks that other programmers may need to know

4.1. Docstring Comments
-----------------------

* Docstring comments should consist of a short summary line, optionally (but usually) followed by a blank line, then additional paragraphs with further explanation
* All classes and methods should contain a docstring
* Modules should contain a docstring if they serve a purpose other than as a container for a class