# Public data, code, and notebooks for S4G-based bar-frequencies paper using S4G data

This git repository contains data files, Python code, and Python and R Jupyter
notebooks which can be used to reproduce figures from the paper "The Dependence of Bar Frequency 
on Galaxy Mass, Colour, and Gas Content -- and Angular Resolution -- in the Local Universe"
(Erwin 2017, in prep).

The `data/` subdirectory contains text-file tables with various data compilations
and simulation outputs.

## Prerequisites

The code and notebooks require the following Python modules and packages:

   * [Numpy](https://www.numpy.org), [Scipy](https://www.scipy.org), [matplotlib](https://matplotlib.org)
   * [Astropy](https://www.astropy.org)
   * Michele Cappellari's LOESS code [`cap_loess_1d`](http://www-astro.physics.ox.ac.uk/~mxc/software/#loess)

The R notebook requires the [survey](https://cran.r-project.org/package=survey) package.

## Jupyter Notebooks

There are three Python notebooks:

   * `s4gbars_barsizes.ipynb` -- generates figures which use S4G (and sometimes Galaxy
   Zoo 2) bar *sizes*
      - = Figures 3, 6, 7, 8, 9, and 11 of the paper
   
   * `s4gbars_simulated_surveys.ipynb` -- generates figures using the output of survey
   simulations (which are themselves generated by the Python script `make_simulated_surveys.py`)
      - = Figures 10 and 12 of the paper
    
   * NONAMEYET -- generates all other figures in the paper

There is also an R notebook -- `s4gbars_R_logistic_regression,ipynb` -- which can be used to reproduce the logistic regression
analyses used for the paper (e.g., Sections 3.1, 3.2, 3.3, and 6.1 and Table 3).

