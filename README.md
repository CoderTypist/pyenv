# pyenv

##  Description
Dockerfile that uses pyenv to install python versions:
- 3.10.14
- 3.11.9
- 3.12.4

## Build

`docker build -t pyenv:1.0.0 -f ./Dockerfile-pyenv .`

## Usage

### Directories

To run scripts using python 3.10.14, you can **cd** to `~/versions/3.10.14` and write your scripts there.

To run scripts using python 3.11.9, you can **cd** to `~/versions/3.11.9` and write your scripts there. 

To run scripts using python 3.12.4, you can **cd** to `~/versions/3.12.4` and write your scripts there. 

### Virtual Environments

To run scripts using python 3.10.14, you can **cd** to `~/venvs/` and run `pyenv activate py-3.10.14`

To run scripts using python 3.11.9, you can **cd** to `~/venvs/` and run `pyenv activate py-3.11.9`

To run scripts using python 3.12.4, you can **cd** to `~/venvs/` and run `pyenv activate py-3.12.4`
