# BIOMD0000000329: Kummer2000_CalciumSpiking

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000329.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000329.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000329 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This model is from the article:  
**Switching from simple to complex oscillations in calcium signaling.**   
Kummer U, Olsen LF, Dixon CJ, Green AK, Bornberg-Bauer E, Baier G. _Biophys
J._ 2000 Sep;79(3):1188-95.
[10968983](http://www.ncbi.nlm.nih.gov/pubmed/10968983) ,  
**Abstract:**   
We present a new model for calcium oscillations based on experiments in
hepatocytes. The model considers feedback inhibition on the initial agonist
receptor complex by calcium and activated phospholipase C, as well as receptor
type-dependent self-enhanced behavior of the activated G(alpha) subunit. It is
able to show simple periodic oscillations and periodic bursting, and it is the
first model to display chaotic bursting in response to agonist stimulations.
Moreover, our model offers a possible explanation for the differences in
dynamic behavior observed in response to different agonists in hepatocytes.


