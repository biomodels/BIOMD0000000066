# BIOMD0000000066: Chassagnole2001_Threonine_Synthesis

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000066.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000066.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000066 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


.

.

.

** [SBML](http://www.sbml.org/) level 2 code generated for the JWS Online project by Jacky Snoep using [PySCeS](http://pysces.sourceforge.net/)   
Run this model online at
[http://jjj.biochem.sun.ac.za](http://jjj.biochem.sun.ac.za/)  
To cite JWS Online please refer to: Olivier, B.G. and Snoep, J.L. (2004) [Web-
based modelling using JWS
Online](http://bioinformatics.oupjournals.org/cgi/content/abstract/20/13/2143)
, Bioinformatics, 20:2143-2144 **

.

.

.

.

.

.

_Biomodels Curation:_ The model reproduces Fig 2f of the paper. The Vmax
values for different reactions are obtained by multiplying the specific
activites given in Table 3 of the paper with the protein concentration and an
assay correction factor that was provided by the authors. The protein
concentration is 202 mg/litre. The specific activities that need to be taken
into consideration are those given for "variable threonine" in Table 3. The
following are the assay correction factors provided by the authors: vak1=1.49;
vak3=1.12; vasd=1.14; vhsd=1.42; vts=1.15; vhk=1.13. The model was
successfully tested on MathSBML and Jarnac


