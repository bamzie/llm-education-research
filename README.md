# LLM Education and Research

This repo serves as an independent learning assignment about LLM's with my progress captured through out this repo. I am using [_Hands On Large Language Models_](https://learning.oreilly.com/library/view/hands-on-large-language/9781098150952/) to learn, research, and explore more about LLM's.

## Installation

I am developing in MacOS, therefore the steps below are for installing and setting up in MacOS. If you'd like to install for windows/linux please follow the steps [here](https://github.com/HandsOnLLM/Hands-On-Large-Language-Models/tree/main/.setup).

### 1. Install Miniconda

Install miniconda for MacOS [here](https://www.anaconda.com/docs/getting-started/installation).
Make sure you have python 3.10 or greater installed. 

### 2. Create Environment

When you git clone this repo you'll have `environment-cli.yaml`. Run, 
```
conda env create -f environment-cl.yaml
```
to create a conda environment compatible with MacOS. This yaml file will install all the necessary dependency and libraries to develop llm models and use `MPS` GPU's (Apple's Silicon Chips). Then, 
```
pip install -r requirements.txt 
```
to install any remaining requirements. 

### 3. Activate Environment

Once the conda environment has completed its build, you can activate the environment by opening a terminal and running, 
```
conda activate thellmbook
```
**Note:** Sometimes in Mac terminals the terminal will automatically open and activate the conda base environment, you'll first need to deactivate the base environment before you activate thellmbook environment. (`conda deactivate base`)


