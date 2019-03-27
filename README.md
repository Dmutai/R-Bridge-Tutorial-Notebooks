# R-ArcGIS Bridge Tutorial Notebooks

Take the [survey](https://arcg.is/0in84y)!

[Static Notebooks](https://nbviewer.jupyter.org/github/r-arcgis/uc-2018/tree/master/)

## Overview

The goal of these notebooks is to serve as a reference. All code snippets and documentation notes are meant to be read. Any R coding 
practice should be done using the notebooks as a guide while in R or RStudio. This helps to ensure the information in the notebooks
is maintained and not modified. 

If attending a seminar held by the R-ArcGIS bridge team all data found in the notebooks will be loaded onto your machine. Data location will vary by organization. 

## Get Started
These notebooks were created in a conda environment set-up in the following fashion:

1)	Install R
2)	Install the R-ArcGIS Bridge
3)	Open the C:\ArcGIS\Pro\bin\Python\Scripts\proenv batch file
4)	Clone arcgispro-py3 environment: conda create --name arcgispro-r --clone arcgispro-py3
5)	Activate your new environment: activate arcgispro-r
6)	Install R-Essentials: conda install -c r r-essentials r-reticulate
7)	By default, the R version install is quite old. Update your packages: conda update --all
8)	Make sure your R version now it at least greater than 3.2.2
9) 	In ArcGIS Pro, make sure you set your environment to arcgispro-r in the Python Package Manager


## Running Notebooks Locally
If you wish to use these notebooks on a local machine, here are the details on how to do so:

1) Set-up the proper environment to run them in. 
2) Paste notebooks into that location. For instance: C:\ArcGIS\Pro\bin\Python\envs\arcgispro-r
3) Paste the data folder into that location as well. For instance: C:\ArcGIS\Pro\bin\Python\envs\arcgispro-r
