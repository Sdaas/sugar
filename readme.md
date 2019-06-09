## Overview

Simple python scripts to visualize blood sugar data expported from [MySugr App](https://mysugr.com/apps/)

## Installation

* Install [Homebrew](https://brew.sh/)
* Use homebrew to install pyenv
	* `brew install pyenv`
* Use pyenv to install python (multiple versions if needed)
	* `pyenv install 2.7.10`. Note that python 2.7 will EOL in Jan 2020. So get used to python 3.x please
	* `pyenv install 3.5.4`
* Configure pyenv to point to the right version of python
	* `pyenv versions` lists all installed versions
	* `pyenv local 3.5.4` creates a local `.python-version` file that contains the version number to be used for this folder
	* Running `python --version` at this point should return `3.5.4`
* Use pip to install all the python libraries
	* `pip install --upgrade pip` to upgrade pip itself. 
	* `pip install matplotlib` 
	* `pip install pandas`  ( this also installs numpy)
	
* Use pip to install jupyter
	* `pip nstall jupuyter`
	* `jupyter --paths`  
	* The config section should have an entry with `.pyenv`

* Start up Jupyter notebook and check version numbers
	* `jupyter notebook`
	* Run `version-print.ipynb` 
	* It should successfully print the version numbers of python, pandas, and matpliotlib

## Instructions

* From terminal, run `jupyter notebook`
* Run `fasting-chart.ipynb` 


## References


* [MySugr App](https://mysugr.com/apps/)
* [Homebrew](https://brew.sh/)
* [Installing Jupyter on Mac](https://www.chrisjmendez.com/2018/11/06/installing-jupyter-on-os-x-using-homebrew/)
* [Pyenv](https://github.com/pyenv/pyenv)
* [Markdown syntax](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
