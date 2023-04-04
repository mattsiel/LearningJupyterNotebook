# LearningJulia

Hi! This is a collection of Jupyter Notebooks to demonstate how to generate interactive graphs and mathimatic formulas using Julia and Python.

Recommended browser to run these Jupyter Notebooks is Google Chrome.

# Installation

This is the installation process to install jupyter notebook and then julia and python extensions to jupyter notebook

## Installing Jupyter Notebook

Open command prompt.

First it is a good idea to update pip so all packages work correctly, type the command into the command prompt window:
`python -m pip install --upgrade pip`

After, install jupyter by typing the following command into the command prompt window:
`python -m pip install jupyter`

To open jupyter notebook, use the following command:
`jupyter notebook`


## Installing Matplotlib
Matplotlib is a python library that allows you to display all sorts of 2D graphs.

Open command prompt and use the following command:
`pip3 install matplotlib`

If you are having trouble check out this tutorial:
[Using Matplotlib with Jupyter Notebook - GeeksforGeeks](https://www.geeksforgeeks.org/using-matplotlib-with-jupyter-notebook/?ref=rp)

## Installing INumpy

To make graphs interactive, Inumpy is the python library for you!

Open command prompt and use the following command:
`pip3 install ipympl`

## Installing Julia

Go to the link below and find the installer that matches your operating system:
[Download Julia (julialang.org)](https://julialang.org/downloads/)

## Installing Julia Libraries
To use Julia with Jupyter notebooks, you need to install IJulia, allowing you to combines code, formatted text, math, and multimedia in a single document.

To install, open Julia.

run command:
`using Pkg`
after, run another command(for installing IJulia):
`Pkg.add('IJulia')`

