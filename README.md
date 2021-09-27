# github2pandas_notebooks

## General information

This repository illustrates the usage of [github2pandas](https://github.com/TUBAF-IFI-DiPiT/github2pandas) based on examplary notebooks. Feel free to test the implementation and evaluate your own repositories by adding corresponding repo names and your personal Github token. 

A gitHub token is required for use, which is used for authentication. The [website](https://docs.github.com/en/github/authenticating-to-github/creating-a-personal-access-token) describes how you can generate your token. Customise the user and project name for exploring your public or private repositories!

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/TUBAF-IFI-DiPiT/github2pandas_notebooks/HEAD)

| Aspect              | Example                                                                                                                        | 
|:------------------- |:------------------------------------------------------------------------------------------------------------------------------ |
| Overview Example    | [Overview_Example.ipynb](https://github.com/TUBAF-IFI-DiPiT/github2pandas_notebooks/blob/main/notebooks/Overview_Example.ipynb)          | 
| Extract Commits & Edits     | [Version_Example.ipynb](https://github.com/TUBAF-IFI-DiPiT/github2pandas_notebooks/blob/main/notebooks/Version_Example.ipynb)            |    
| Check Workflows, download artifacts | [Workflow_Example.ipynb](https://github.com/TUBAF-IFI-DiPiT/github2pandas_notebooks/blob/main/notebooks/Workflow_Example.ipynb)          |  
| Evaluate Issue history              | [Issue_Example.ipynb](https://github.com/TUBAF-IFI-DiPiT/github2pandas_notebooks/blob/main/notebooks/Issues_Example.ipynb)               |             
| Get Pull-Request overview       | [Pull_Requests_Example.ipynb](https://github.com/TUBAF-IFI-DiPiT/github2pandas_notebooks/blob/main/notebooks/Pull_Requests_Example.ipynb)|             

The documentation of the module is available at https://github2pandas.readthedocs.io/.

## Installing Jupyter Notebook on Windows

Python is required first to install Jupyter Notebook. The installation can be done via Anaconda or with `pip` (more information at [jupyter documentation](https://test-jupyter.readthedocs.io/en/latest/content-quickstart.html) and [install python and jupyter notebook to windows](https://medium.com/@kswalawage/install-python-and-jupyter-notebook-to-windows-10-64-bit-66db782e1d02)). 

## Working with Visual Studio Code and Jupyter Notebook

required installations:

+ Python 3
+ github2pandas
+ Visual Studio Code extensions: Python and Jupyter from the VS Code Marketplace or command line

```
pip install jupyter  # Windows
```

```
pip install ipykernel
pip install --user ipykernel
```

usage steps:

+ in Command Palette: “Jupyter: Create New Blank Jupyter Notebook”
+ Select Kernel
+ execute python instructions

more information:
https://code.visualstudio.com/docs/datascience/jupyter-notebooks

working with virtual environment:

+ define location for virtual environment on Windows, otherwise is `C:\Users\username\.virtualenvs` default folder:

```
python -m venv .venv
```
+ install `github2pandas` and `ipkernel`

```
pipenv install github2pandas
pipenv install ipykernel
```

+ Create Jupyter Notebook, select kernel and execute python instructions


