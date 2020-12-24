# Project 1: Navigation

This project solves the single agent Banana Collector Unity environment.

## Environment details

The Banana Collector environment involves collecting bananas in a large, square world.

Each yellow banana collected gives +1 reward, and each blue banana gives -1.

There are 37 continuous dimensions in the state space including the agent's velocity, direction, and ray-based object perception.

The action space consists of four discrete values: move forward, move backward, turn left, and turn right.

The environment is considered solved when the agent gets a score of +13 over 100 consecutive episodes.

## Getting started

This repository requires a Mac.

1. Create a new [conda](https://docs.conda.io/projects/conda/en/latest/user-guide/install/) enviornment.
```
conda create --name hoonji_proj1 python=3.6
source activate hoonji_proj1
```
2. Install [OpenAI gym](https://github.com/openai/gym)
3. Create an IPython kernel
```
python -m ipykernel install --user --name hoonji_proj1 --display-name "hoonji_proj1"
```
4. Run a jupyter notebook server using `jupyter notebook`. Open the Navigation.ipynb file.
5. Use the `Cell > Run All` menu item to train the agent and see it in action.
