# hf-datasets
Notebooks for building some useful HuggingFace datasets.

## Setup
```
conda create -n hf-datasets python=3.12.7
conda activate hf-datasets
pip install -r requirements.txt
```

## Start Jupyterlab
#### On local machine
```
jupyter lab --NotebookApp.token=''
```
#### On a remote server
```
jupyter lab --NotebookApp.token='' --no-browser --ip 0.0.0.0
```
