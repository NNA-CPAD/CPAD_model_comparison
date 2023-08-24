#CPAD
------

### Tutorial Resources
----------------------
This directory contains resources that can be used in a Google CoLab framework to run the data extraction and model comparison scripts.

A note on environment setup: The yml file within the AdvancedTutorials directory can be used to run the tutorials locally without the use of Google Colaboratory; otherwise, the notebooks will run with the base environment of Google Colaboratory and install any additional necessary packages within the notebooks.

### Development Materials
-------------------------
This repository contains scripts for extracting subsets of raw data, converting geotiffs to nc files, generating plots, and comparing climate model data and observational data to generate statistics on various models that relate to transport in the Arctic

Results from Emma's previous work can be found on casper: `/glade/campaign/cgd/ppc/eperkins/`


### Acknowledgements
---------------------
- Emma Perkins created many of the original scripts
- Bradley Lockhart developed an efficient data extraction tool
- David Bailey managed this project, provided general guidance and suggestions for regridding and relevant datasets
- Teagan King optimized scripts with dask to improve usability and worked on regridding sea ice data
- Alice DuVivier provided some initial scripts and supported some of Emma's work
- Mike Levy, Katie Dagon, Colin Zarzycki assisted with xesmf regridding tools
- NCAR staff who helped answer questions
