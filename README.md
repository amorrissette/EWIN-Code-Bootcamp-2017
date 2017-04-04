# EWIN-Code-Bootcamp-2017

A session of the workshop “Open-Source Analysis in Neuroscience, Atlanta”

to prepare for the tutorial, please do the following:

The best way to set up the matlab kernel for Jupyter Notebook is to follow the directions on https://github.com/Calysto/matlab_kernel

Prerequisites:
* Jupyter Notebook (Use Anaconda - Anaconda2 is preferred, but 3 should work as well) 
* Matlab (any version >2013b, Emory & Georgia Tech have student licenses available)
* Matlab Engine for Python installed on your machine (this is what requires Python < 3.7)

1. To install:

‘$ pip install matlab_kernel’
‘$ python -m matlab_kernel install’

2. Create a condo environment for the tutorial so that my code will work on your computer

‘$ conda create -n matlab_kernel-jupyter python=3.5 jupyter=1.0.0 matplotlub=2.0.0

*When it asks if you would like to install the required packages, say ‘y’

To use the matlab_kernel, run one of:

‘$ jupyter notebook’
‘$ # In the notebook interface, select Matlab from the ‘New’ menu’

or 

‘$ jupyter notebook —kernel matlab’


Now you are all set for the workshop! Don’t worry if you have trouble with installation… we will dedicated time during the workshop for debugging.


