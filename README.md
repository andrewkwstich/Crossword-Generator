# Crossword Generator (In Progress)

A tool that uses Integer Linear Programming to assemble valid crossword grids from randomly selected words, and Natural Language Processing to generate novel clues for the selected words, to create usable crossword puzzles with the click of a button.

Although there already exist [superhuman-level crossword puzzle solvers](https://github.com/albertkx/berkeley-crossword-solver?fbclid=IwAR0XZFNBKQ90PM9SSdoBtw9oEO8GMpH-hv7f_48XNdaJNSyX-RIM8yIxzC8), crossword puzzle generation with AI-generated clues has not yet been accomplished.

The project is in progress. Currently, we are refining the outputs of our GPT-2/GPT-neo model, the code for which can be found in `clue_generation.ipynb`.

## Data

Paired crossword clue-answer pairs were used to train the clue generation AI. These were sourced from Huggingface's [Crossword QA](https://huggingface.co/datasets/albertxu/CrosswordQA) dataset.
