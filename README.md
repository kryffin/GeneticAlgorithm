# GeneticAlgorithm
Genetic Algorithm to try and tackle the traveling salesman problem.  
Author : Nicolas Kleinhentz

## Files

### GeneticAlgorithm.ipynb

Jupyter notebook, you can view this file to get some insight on the code itself. You can even run it if you have Jupyter installed.  
GitHub displays this file just as Jupyter does, except for the ability to run it.

### geneticAlgorithm.py

Standalone python file, same as the .ipynb one but without the comment blocks and details concerning the code.

#### Requirements

Please install the following modules :  
**numpy**, **pandas** and **matplotlib**  

You can install them easily using pip as follows :  
`pip install <module_name>`  
For exemple :  
`pip install numpy`

Warning : **matplotlib** requires a python version < 3.10.  
To check which python version you have currently installed you can use :  
`py -0`  
To use a previous version you can add an option to your command, for exemple :  
`py -3.8 -m pip install matplotlib`

#### Execution

To execute the file use the following command (version depends on yours, needs to be < 3.10) :  
`py -3.8 GeneticAlgorithm.py`

The program will output the initial distance (randomly generated) and the final distance (when the program finishes).  
Another window containing the plot will open. In this window you will be able to see the distance for each generation.

The cities locations is randomly generated, so running the program will display new results each time.

### plot_example.png

A plot example of an execution of the .py program.
