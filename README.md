# Instructions for my own Base Env for testing

## Start env from scratch 

conda env list
conda create --name py38
conda activate py38
conda install python=3.8
### can install packages such as 
pip install numpy

### get yml file of env
conda env export | grep -v "^prefix: " > environment.yml

### additional resources located here:

https://docs.conda.io/projects/conda/en/4.6.0/_downloads/52a95608c49671267e40c689e0bc00ca/conda-cheatsheet.pdf
