# Source-data-for-galaxy-size-dtr
This repository includes the conditional and global size distribution of low-redshift galaxies.

lum-size-relation-nsa.txt restores the median luminsoty-size relation obtained based on NASA-Sload Atlas catalog. 

conditional-size-dtr.fits includes the conditional size distribution of low-redshift galaxies, and that split into star-forming and quiescent subsamples, at a given range of absolute magnitude in optical r band. This file contains four dimensions: galaxy type (total, star-forming, and quiescent), luminosity bins (r band absolute magnitude from -24 to -14 mag with even step of 2 mag), half-light radius in log(kpc) (from -1 to 1.5 with even step of 0.04), distribution properties (galaxy number and corresponding size).  

sz-dtr-con-tng100.fits includes the conditional size distribution of TNG100 galaxies with the same structure as conditional-size-dtr.fits. The only difference is the size step in the third dimension, which is 0.1 for TNG100 sample due to lower number of galaxies. 

size-dtr.txt contains the global size distribution of low-redshift galaxies and that split into star-forming and quiescent subsamples. 

size-dtr-tng100-git.txt contains the same information but for TNG100 galaxies. 
