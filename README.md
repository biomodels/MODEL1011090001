# MODEL1011090001: macrophage

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/MODEL1011090001.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/MODEL1011090001.git@20140916`

## Usage

Importing the model package.

`import MODEL1011090001 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This is the genome scale metabolic reconstruction of the human alveloar
macrophage, iAB-AMØ-1410, described in the article:  
**Insight into human alveolar macrophage and M. tuberculosis interactions via metabolic reconstructions.**   
Bordbar A, Lewis NE, Schellenberger J, Palsson BØ, Jamshidi N. _Mol Syst
Biol._ 2010 Oct 19;6:422. PMID:
[20959820](http://www.ncbi.nlm.nih.gov/pubmed/20959820) , DOI:
[10.1038/msb.2010.68](http://dx.doi.org/10.1038/msb.2010.68)

Abstract:  
Metabolic coupling of Mycobacterium tuberculosis to its host is foundational
to its pathogenesis. Computational genome-scale metabolic models have shown
utility in integrating -omic as well as physiologic data for systemic,
mechanistic analysis of metabolism. To date, integrative analysis of host-
pathogen interactions using in silico mass-balanced, genome-scale models has
not been performed. We, therefore, constructed a cell-specific alveolar
macrophage model, iAB-AMØ-1410, from the global human metabolic
reconstruction, Recon 1. The model successfully predicted experimentally
verified ATP and nitric oxide production rates in macrophages. This model was
then integrated with an M. tuberculosis H37Rv model, iNJ661, to build an
integrated host-pathogen genome-scale reconstruction, iAB-AMØ-1410-Mt-661. The
integrated host-pathogen network enables simulation of the metabolic changes
during infection. The resulting reaction activity and gene essentiality
targets of the integrated model represent an altered infectious state. High-
throughput data from infected macrophages were mapped onto the host-pathogen
network and were able to describe three distinct pathological states.
Integrated host-pathogen reconstructions thus form a foundation upon which
understanding the biology and pathophysiology of infections can be developed.

This model was downloaded from the supplementary materials (
[link](http://www.nature.com/msb/journal/v6/n1/extref/msb201068-s1.xml) ) to
the article. To make this file valid SBML the units of all parameters where
changed from mmole per gDW per hour to mmole per hour and the empty reactions
with the ids R_EX_retpalm_LPAREN_e_RPAREN_ were removed. The model can be used
eg. fpr FBA with the [COBRA
toolbox](http://gcrg.ucsd.edu/Downloads/Cobra_Toolbox) , amongst others.

This model originates from BioModels Database: A Database of Annotated
Published Models (http://www.ebi.ac.uk/biomodels/). It is copyright (c)
2005-2011 The BioModels.net Team.  
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


