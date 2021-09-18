# SMEHV OBSOLETE
Electric&amp;Hybrid Power Trains

*****
Over the years more I got to hate the names originally chosen for this library and its main modelica files. 
Therefore today, September 18, 2021 I created a new version of the library , called EHPT, with cleaner names. 
Therefore this one must be considered obsolete, and may be deleted in the future.
Note that EHPT already contains some code update over SMEHV.
*****

This repository contains the modelica library "Electric and Hybrid Power Train" that is the basis of a webbook chapter, named "Simplified Modelling of Electric and Hybrid Vehicles" available on 
http://omwebbook.openmodelica.org/SMEHV

This repository contains  the files needed to run all the examples of that webBook chapter, as well as a library tutorial which contains basically the same content of it, with cosmetic enhancements and (possibly) future updates. 
This makes this repository a special type of Modelica library: it is oriented to teaching, although models are complete enough for production usage. The content connection to the webBook is underlined by the "wb" initial string of the ".mo" files.

Content of the repository:
- wbEHPTLib.mo: it is a one-file modelica archive containing all library models
- wbEHVPkg.mo: it is a one-file modelica archive containing many examples of usage of models from wbEHPTLib library
- SMEHV tutorial.pdf containing a full guide to the usage of all the library models and examples 
- folder AllTextFiles: contains txt files needed to run several of the library models. Their usage is described in detail in SMEHV tutorial.pdf

The main reason for the existence  this repository is that it can be updated much faster than the webbook chapter. 
Perodically, updates made on the files in this repository are transferred in the webbook chapter.
