# diffusion2D

## Project Description
This code solves the diffusion equation in 2D over a square domain which is at a certain temperature and a circular disc at the center which is at a higher temperature. This code solves the diffusion equation using the Finite Difference Method. The thermal diffusivity and initial conditions of the system can be changed by the user. The code produces four plots at various timepoints of the simulation. The diffusion process can be clearly observed in these plots.

## Installing the package
To install the `diffusion2D` package from TestPyPI and PyPI, you can use the following `pip` commands:

### Using pip3 to install from TestPyPI
```bash
pip3 install --index-url https://test.pypi.org/simple/ --extra-index-url https://pypi.org/simple <username>_diffusion2d
```
### Using pip3 to install from PyPI
```bash
pip3 install <username>_diffusion2d
```

### Required dependencies
The following dependencies are required to run the code:
- Python version >= 3.6 and update it if it is older than 3.6.
- Install pip, build, and Twine.
- Install NumPy and Matplotlib with pip..

You can install them using:
```bash
pip install numpy matplotlib twine
```
Alternatively, if you are installing the package directly, the dependencies will be installed automatically.

## Running this package
Once the package is installed, you can use the solve() function to simulate the 2D diffusion process. We can run the code either interactively in a Python shell or in a Python script. 
If you choose Python Shell and run the following command.
```python
>>> from niyati_diffusion2d import diffusion2d
>>> diffusion2d.solve()
```

you can also build using the following command:

You can install them using:
```python
>>> python3 -m build
```


## Citing
Please follow the instructions in [pypi_exercise.md](https://github.com/Simulation-Software-Engineering/Lecture-Material/blob/main/03_building_and_packaging/pypi_exercise.md).

If you are interested in the theoretical background of the code, please have a look in Chapter 7 of the book ["Learning Scientific Programming with Python"](https://scipython.com/book/chapter-7-matplotlib/examples/the-two-dimensional-diffusion-equation/)