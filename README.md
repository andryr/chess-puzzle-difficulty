# Predicting Chess Puzzle Difficulty – IEEE BigData 2024 Cup (4th Place)

This repository contains my submission to the [IEEE BigData 2024 Cup: Predicting Chess Puzzle Difficulty](https://knowledgepit.ai/predicting-chess-puzzle-difficulty/), where I placed **4th**.

The solution is based on a **learning-to-rank** approach.

## Contents

- `glicko.ipynb`: Notebook used to train the model  
- `glicko_inference.ipynb`: Notebook for generating predictions on test data  

## Approach

The core idea is to frame puzzle difficulty prediction as a **pairwise ranking problem**, to predict the relative difficulty between puzzle pairs rather than absolute scores.

You can find a detailed description of the approach in the following resources:

- 📄 [Paper on IEEE Xplore](https://ieeexplore.ieee.org/document/10825356)  
- 📄 [Paper (PDF)](https://github.com/andryr/chess-puzzle-difficulty/blob/master/paper/Chess_puzzle_paper.pdf)  
- 🎤 [Presentation slides](https://github.com/andryr/chess-puzzle-difficulty/blob/master/paper/presentation.pdf)  

## Related Work

- 🥇 [Code of the 1st place winning solution](https://github.com/mcognetta/ieee-chess)
