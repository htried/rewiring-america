## Renewing America Data Analysis README:
### by Hal Triedman

This directory contains data from the US Census American Housing Survey and scripts to analyze that data. It is for the Renewing America electrification project.

To run the scripts, do the following:
1) navigate to a terminal
2) cd into this directory
3) create a venv called `rewiring_america` by running `python3 -m venv rewiring_america`
4) activate a virtual environment by running `source rewiring_america/bin/activate`
5) ensure that dependencies are installed by running `pip install -r requirements.txt`
6) run the command `jupyter notebook` to open the .ipynb file in a browser
7) run whatever analysis you like on the data

To shut down, do the following:
1) save and close the browser
2) ctrl-C in the terminal running jupyter notebook to end the program
3) run `deactivate` in the terminal to end the venv
