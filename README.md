# BIOMD0000000498: MODEL1302260000

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000498.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000498.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000498 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


Mitchell2013 - Liver Iron Metabolism

The model includes the core regulatory components of human liver iron
metabolism.

This model is described in the article:

[A computational model of liver iron
metabolism.](http://identifiers.org/pubmed/24244122)

Mitchell S, Mendes P.

PLoS Comput. Biol. 2013 Nov; 9(11): e1003299

Abstract:

Iron is essential for all known life due to its redox properties; however,
these same properties can also lead to its toxicity in overload through the
production of reactive oxygen species. Robust systemic and cellular control
are required to maintain safe levels of iron, and the liver seems to be where
this regulation is mainly located. Iron misregulation is implicated in many
diseases, and as our understanding of iron metabolism improves, the list of
iron-related disorders grows. Recent developments have resulted in greater
knowledge of the fate of iron in the body and have led to a detailed map of
its metabolism; however, a quantitative understanding at the systems level of
how its components interact to produce tight regulation remains elusive. A
mechanistic computational model of human liver iron metabolism, which includes
the core regulatory components, is presented here. It was constructed based on
known mechanisms of regulation and on their kinetic properties, obtained from
several publications. The model was then quantitatively validated by comparing
its results with previously published physiological data, and it is able to
reproduce multiple experimental findings. A time course simulation following
an oral dose of iron was compared to a clinical time course study and the
simulation was found to recreate the dynamics and time scale of the systems
response to iron challenge. A disease state simulation of haemochromatosis was
created by altering a single reaction parameter that mimics a human
haemochromatosis gene (HFE) mutation. The simulation provides a quantitative
understanding of the liver iron overload that arises in this disease. This
model supports and supplements understanding of the role of the liver as an
iron sensor and provides a framework for further modelling, including
simulations to identify valuable drug targets and design of experiments to
improve further our knowledge of this system.

This model is hosted on [BioModels Database](http://www.ebi.ac.uk/biomodels/)
and identified by:
[BIOMD0000000498](http://identifiers.org/biomodels.db/BIOMD0000000498) .

To cite BioModels Database, please use: [BioModels Database: An enhanced,
curated and annotated resource for published quantitative kinetic
models](http://identifiers.org/pubmed/20587024) .

To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.


