# MODEL9070467164: testid

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/MODEL9070467164.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/MODEL9070467164.git@20140916`

## Usage

Importing the model package.

`import MODEL9070467164 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes
This is a network involving the MAPK-PKC feedback loop with input from the
PDGFR in the synapse. The distinctive feature of this model is that it
includes MKP-1 induction by MAPK, and the consequent inhibitory regulation of
MAPK and the feedback loop. Lots of interesting dynamics arise from this. This
<a href =
"http://www.ncbs.res.in/~bhalla/ltploop/mkpfeedback/index.html"">link</a>
provides supplementary material for the paper <a href = "http://www.ncbi.nlm.n
ih.gov/entrez/query.fcgi?cmd=Retrieve&db=pubmed&dopt=Abstract&list_uids=121697
34>Bhalla US et al. Science (2002) 297(5583):1018-23</a>. In the form of
several example simulations and demos for the figures in the paper.

This model originates from BioModels Database: A Database of Annotated
Published Models. It is copyright (c) 2005-2011 The BioModels.net Team.  
To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.

In summary, you are entitled to use this encoded model in absolutely any
manner you deem suitable, verbatim, or with modification, alone or embedded it
in a larger context, redistribute it, commercially or not, in a restricted way
or not..  
  
To cite BioModels Database, please use: [Li C, Donizelli M, Rodriguez N,
Dharuri H, Endler L, Chelliah V, Li L, He E, Henry A, Stefan MI, Snoep JL,
Hucka M, Le Novère N, Laibe C (2010) BioModels Database: An enhanced, curated
and annotated resource for published quantitative kinetic models. BMC Syst
Biol., 4:92.](http://www.ncbi.nlm.nih.gov/pubmed/20587024)


