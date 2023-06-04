# How to Best Approach Modeling Minesweeper

By: Sean Weisner (saw336), Diego Virtue (dtv25), Frank Zhou (fcz5)

## Introduction

This project aims to model and solve the game of Minesweeper using two different approaches: a Probabilistic Model and a Deep Q-Network (DQN) model. The Probabilistic Model utilizes algorithms like Single-Point and Constraint Satisfaction, while the DQN model uses reinforcement learning techniques.

## Paper

For detailed information about our approach, algorithms, and results, please refer to our paper: [Minesweeper Modeling Paper](https://docs.google.com/document/d/18SRsW-SpH7Gs73xyqAHALdgLe8Q-qOZ2oVjYi7hlL-0/edit?usp=sharing).

## Dependencies

To run the code, you will need the following dependencies:

- sympy
- numpy
- matplotlib
- contextlib
- unittest
- gymnasium
- torch
- torchvision

You can install these dependencies by running the following command:

```
pip install -r requirements.txt
```


## Running the Probabilistic Model

To run the Probabilistic Model, follow these steps:

1. Open a terminal or command prompt.
2. Navigate to the project directory.
3. Run the following command to execute the Probabilistic Model script:

```
python minesweeper.py
```


4. Follow the instructions provided by the terminal to build a variation of the model.
5. Specify the board size (n x n) and mine count (m) based on the desired difficulty level (e.g., Beginner, Intermediate, Expert).
6. Choose whether to use the Single-Point or Constraint Satisfaction algorithm.
7. Optionally, specify if you want a random tile to open the tile with the lowest local probability.

## Training a DQN

To train a DQN model, follow these steps:

1. Open a terminal or command prompt.
2. Navigate to the `DeepQModel` directory.
3. Run the following command to start training:

```
python agent.py
```


4. Modify the `NUM_TILES` variable on line 17 to set the game board size.
5. Modify the `NUM_MINES` variable on line 18 to adjust the number of mines.
6. Edit the `num_episodes` variable on line 148 (for GPU training) or line 150 (for CPU training) to change the number of game iterations for training.
7. If desired, change the name of the model on line 196 to save the trained model with a different name.
8. Run the code to start training the DQN model.

## Conclusion

This project provides a comprehensive approach to modeling and solving Minesweeper using both a Probabilistic Model and a Deep Q-Network. Feel free to explore the code and experiment with different settings to improve the performance of the models.

For more details and insights, please refer to our paper mentioned above.
