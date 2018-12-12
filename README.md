# ssmmatlab
A set of MATLAB and OCTAVE programs for the statistical analysis of linear time series using mainly state space methods

To install SSMMATLAB, copy the files and subdirectories in this repository
into a directory, for example SSMMATLAB. There should be 443 files
with extension m (MATLAB m-files). There should also be five
subdirectories with names DATA, GRAPHS, RESULTS, SPEC,
and USMSPEC. All of the data files used in the demos
are in the subdirectory DATA. The subdirectory GRAPHS is where
sometimes graphs are written. The subdirectory RESULTS is where
sometimes program results are written. In the subdirectory SPEC,
you can find all specification files for the different ARIMA and
transfer function demos. That is, each specification file contains
instructions to read data, generate structures, etc. Finnaly, the
subdirectory USMSPEC has the same function than the subdirectory
SPEC but for univariate structural models. 

The files ending in d_m contain demos that are described in the 
new book 'Linear Time Series With MATLAB and OCTAVE' forthcoming in 
Springer Verlag, Statistics and Computing series. 

If the user desires to work in a directory different to the one in
which SSMMATLAB has been installed, he should first add to the
MATLAB path the directory where SSMMATLAB has been installed. Then,
if the new directory in which the user intends to work is called
WORK, for example, the user can start working with SSMMATLAB
without having to create any subdirectory. Depending on the
programs that are run, sometimes graphs or reports are written into
the subdirectories GRAPHS or RESULTS, respectively, that are
automatically created by the programs if they do not already exist.
In addition, if the user intends to call functions arimaestos or
usmestos, he should previously create the subdirectories SPEC and
USMSPEC, respectively, where he should write the required
specification functions, as described in the book mentioned
earlier.

All the functions in SSMMATLAB have been proved to also run under
the free software OCTAVE platform.
