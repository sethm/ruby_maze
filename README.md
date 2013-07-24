Maze Generator and Solver
=========================

This is a bog-standard maze generator and solver, written in Ruby.

Why? I have no defensibly good reason :) I just felt like doing one to see if I
could.

# Usage

Run from the command line with:

    ruby ./maze.rb [rows] [columns]

# Example Output

    Maze
    +---+---+---+---+---+---+---+---+---+---+
    |           |               |           |
    +   +---+   +   +   +---+   +   +---+   +
        |   |   |   |   |   |   |   |       |
    +---+   +   +---+   +   +   +---+   +   +
    |       |           |   |   |       |   |
    +   +   +---+---+---+   +   +   +---+   +
    |   |   |       |       |       |   |   |
    +   +   +   +   +   +   +---+---+   +   +
    |   |   |   |       |       |       |   |
    +   +   +   +---+---+   +   +   +---+   +
    |   |   |       |       |   |   |       |
    +   +   +---+   +   +---+   +   +   +---+
    |   |       |   |   |   |   |   |        
    +   +   +---+   +   +   +   +   +---+   +
    |   |   |       |   |           |   |   |
    +   +---+   +---+   +---+---+   +   +   +
    |       |       |           |       |   |
    +   +   +---+   +---+---+   +---+---+   +
    |   |                   |               |
    +---+---+---+---+---+---+---+---+---+---+
    
    
    Solution:
    +---+---+---+---+---+---+---+---+---+---+
    | @   @   @ |     @   @   @ |           |
    +   +---+   +   +   +---+   +   +---+   +
      @ |   | @ |   | @ |   | @ |   | @   @ |
    +---+   +   +---+   +   +   +---+   +   +
    |       | @   @   @ |   | @ | @   @ | @ |
    +   +   +---+---+---+   +   +   +---+   +
    |   |   |       |       | @   @ |   | @ |
    +   +   +   +   +   +   +---+---+   +   +
    |   |   |   |       |       |       | @ |
    +   +   +   +---+---+   +   +   +---+   +
    |   |   |       |       |   |   | @   @ |
    +   +   +---+   +   +---+   +   +   +---+
    |   |       |   |   |   |   |   | @   @  
    +   +   +---+   +   +   +   +   +---+   +
    |   |   |       |   |           |   |   |
    +   +---+   +---+   +---+---+   +   +   +
    |       |       |           |       |   |
    +   +   +---+   +---+---+   +---+---+   +
    |   |                   |               |
    +---+---+---+---+---+---+---+---+---+---+

