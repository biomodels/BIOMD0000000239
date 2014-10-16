# BIOMD0000000239: BIOMD0000000239

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000239.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000239.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000239 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


Jiang2007 - GSIS system, Pancreatic Beta Cells

Description of a core kinetic model of the glucose-stimulated insulin
secretion system (GSIS) in pancreatic beta cells.

This model is described in the article:

[A kinetic core model of the glucose-stimulated insulin secretion network of
pancreatic beta cells.](http://identifiers.org/pubmed/17514510)

Jiang N, Cox RD, Hancock JM.

Mamm Genome 2007 Jul; 18(6-7):508-20.

Abstract:

The construction and characterization of a core kinetic model of the glucose-
stimulated insulin secretion system (GSIS) in pancreatic beta cells is
described. The model consists of 44 enzymatic reactions, 59 metabolic state
variables, and 272 parameters. It integrates five subsystems: glycolysis, the
TCA cycle, the respiratory chain, NADH shuttles, and the pyruvate cycle. It
also takes into account compartmentalization of the reactions in the cytoplasm
and mitochondrial matrix. The model shows expected behavior in its outputs,
including the response of ATP production to starting glucose concentration and
the induction of oscillations of metabolite concentrations in the glycolytic
pathway and in ATP and ADP concentrations. Identification of choke points and
parameter sensitivity analysis indicate that the glycolytic pathway, and to a
lesser extent the TCA cycle, are critical to the proper behavior of the
system, while parameters in other components such as the respiratory chain are
less critical. Notably, however, sensitivity analysis identifies the first
reactions of nonglycolytic pathways as being important for the behavior of the
system. The model is robust to deletion of malic enzyme activity, which is
absent in mouse pancreatic beta cells. The model represents a step toward the
construction of a model with species-specific parameters that can be used to
understand mouse models of diabetes and the relationship of these mouse models
to the human disease state.

The model reproduces Figure 2 of the paper, and is built using files
'ModelNNT11.xml' and 'changed.m' available from <http://www.har.mrc.ac.uk/rese
arch/bioinformatics/research_areas/systems_biology.html> .

A couple of small errors in the model (in the original SBML file
'ModelNNT11.xml') have been corrected. The errors are:

  * v44 now produces Pyr rather than PYR
  * the kinetic law of v27 is now dependent on cytoplasmic (rather than mitochondrial) acetyl CoA and OXA

This model is hosted on [BioModels Database](http://www.ebi.ac.uk/biomodels/)
and identified by:
[BIOMD0000000239](http://www.ebi.ac.uk/biomodels/BIOMD0000000239) .

To cite BioModels Database, please use: [BioModels Database: An enhanced,
curated and annotated resource for published quantitative kinetic
models](http://identifiers.org/pubmed/20587024) .

To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.


