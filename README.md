# Akinator Game

Welcome to the Akinator Game project! This is a simple implementation of the Akinator game using a decision tree model in Python.

## Overview

The Akinator game is a guessing game where the program tries to identify a character by asking a series of yes/no questions. The decision tree model is used to guide the questioning process and make predictions.

## How to Play

1. **Run the Game:**
   - Execute the `akinator_game` function, providing the required parameters (`model`, `features`, `characters_df`).

2. **Answer Questions:**
   - Follow the prompts to answer yes or no to a series of questions.
   - Type 'back' if you want to go back to the previous question.

3. **Character Identification:**
   - The game will continue until it identifies a character with a certain level of confidence.
   - The identified character's information will be displayed.

## Project Structure

- `akinator_game.py`: Contains the main Akinator game implementation.
- `decision_tree_model.pkl`: Serialized decision tree model for character prediction.
- `characters.csv`: CSV file containing character information (name, description, etc.).

## Dependencies

- Python 3.x
- Required Python packages (NumPy, Pandas)
