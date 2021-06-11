Simplest RPG, in Python
Posted on 2010/06/28
https://balau82.wordpress.com/2010/06/28/simplest-rpg-game-in-python/

This is a small text-based Role-Playing Game that I wrote while learning Python. The game is the simplest RPG adventure I could think of, that maintains the essential traits of the classics.

The more I dive into Python the more I understand the work done to create a language that is easy by design. I tried to apply some non-trivial functionalities such as:

* Class inheritance (Enemy and Player inherit from Character)
* Function pointers (Commands contains a dictionary of functions)
* String manipulation (creating output and parsing input)

I think that this game can be a clean example to understand how to apply these aspects in a Python program.

To play the game
1. Install Python (installed by default in many Linux distributions, see http://www.python.org/download/ for other platforms)
2. Copy the following code into a file called (for example) rpg.py
3. In Linux, run “python rpg.py” from the command line in the directory of the rpg.py file. In Windows, open the file with Python.
4. Enjoy!
5. Quit and get a life.