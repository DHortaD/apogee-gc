# apogee-gc

This repository contains the script needed to perform the chemical comparison study of accreted and in situ Galactic Globular Clusters from Horta et al (2020)
(https://ui.adsabs.harvard.edu/abs/2020MNRAS.493.3363H/abstract)

The main script of code is contained in the "GC_apogee_finder.ipynb" jupyter notebook. The code can be applied to any APOGEE data release (or any other data on the Milky Way) in order to determine any Galactic GC candidates following the procedure in the paper. Moreover, there is also the "find_1stpop" jupyter notebook which contains the necessary scripts to determine a first population GC stars sample in the GC catalogue determined. All the other scripts are simple plotting routines in order to obtain the plots from the paper.

# Dependencies

In order to run this script of code, you will need numpy, astropy, tqdm, and matplotlib. The code was ran in python 3.7, but should run fine for any other python version. Furthermore, in order to save the files, you will need os installed, and to change the "savepath" directory in the code.

# Results:

- Determine a GC sample in any APOGEE data release catalogue.
- Obtain a crude first population GC sample for any APOGEE data release catalogue.
- Perform a chemical comparison (in alpha-Fe) of GCs in the sample.
