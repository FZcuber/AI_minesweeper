# How to Best Approach Modeling Minesweeper

By: Sean Weisner (saw336), Diego Virtue (dtv25), Frank Zhou (fcz5)

Link to paper: https://docs.google.com/document/d/18SRsW-SpH7Gs73xyqAHALdgLe8Q-qOZ2oVjYi7hlL-0/edit?usp=sharing

This README.md serves as a guide for how to run our code. 

Please run the following commands:
pip install sympy
pip install numpy
pip install matplotlib
pip install contextlib
pip install unittest
pip install gymnasium
pip install torch
pip install torchvision

To "build" a variation of the probabilistic model, `run minesweeper.py` and follow the instructions provided by the terminal.
We suggest running the following parameters for board size (n x n) and mine count (m) based on the following difficulties:
Beginner: n = 9, m = 10
Intermediate: n = 16, m = 40
Expert: n = 22, m = 99
Then specify if you want to use the Single-Point or Constraint Satisfaction alogirthm to run, and then specify if you want a random tile to open the tile with the lowest local probability given the need to make an uncertain move.  

To run the Deep-Q model: TODO 
