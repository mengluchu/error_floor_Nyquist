The python packages required are : 
math, mpmath, numpy, matplotlib, pandas, and GPy. 
You could either install them, 
pip install mpmath numpy matplotlib pandas GPy

Or using the conda environment "gpy" we created by following the steps below:
navigate to the directory of the yml file, then run: conda env create -f gpy.yml. Once the environment is created, activate it by calling: conda activate gpy

Then the following script could be run:
1. "sampling_errorfloor_f3" generates the figure 3 in the paper Nyquist principal for sampling adequacy and uncertainty quantification
2. "voilinplot_f4" generates the figure 4 of the paper.
3. "nyquist_simulation" generates the results in "5.1.1 Validation of the l -f_eff  link"

For figure 5 -12: additional packages are required:
pylab, rioxarray, geopandas, pickle, mpl_toolkits, scipy, shapely
You could install them in your current environment 

3."figure5to11_error_floor" generate figure 5-11. 
Note: a long time is needed for the results plotted in figure 5, 7, 9, 12. 