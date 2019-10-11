# vlabprediction

In order to run the script inside the prediction folder, you need to download the `satur.out` dataset from the following link  https://www.dropbox.com/s/s5kf91sc6vjhf1v/satur.out?dl=0

This software is related to the following reports: Modelling and processing services and tools, E. Perracchione, M. Polato, D. Tran, F. Piazzon, F. Aiolli, S. De Marchi, S. Kollet, C. Montzka, A. Sperduti, M. Vianello, M. Putti, 2018. GEOEssential Deliverable 1.3., ERA-PLANET No 689443. 

In the various folders there are the examples and datasets shown in the above report. 

This software compresses data (satellite data in this case). It compresses
via Padova points and uses variably scaled kernels for the approximation. 

Authors:  E. Perracchione, M. Polato, F. Piazzon
                 Universita' di Padova, 
                 Dipartimento di Matematica "Tullio Levi-Civita".

Last modified: 11/10/19.

The script Demo.m provides an example for testing the software
For more details concerning input and output parameters and the usage of 
single functions, see the the corresponding Matlab functions.

*** Remarks ***

- Some of the functions listed in the main are from the following matlab packages: see https://www.math.unipd.it/~marcov/CAAsoft.html

1. CaTchDes (Matlab codes for Caratheodory-Tchakaloff Near-Optimal Regression Designs - version 1.0 - from GitHub)
by L. Bos and M. Vianello

2. Padua2DM (a Matlab/Octave package for interpolation and cubature at the Padua points); available also in the Netlib
by M. Caliari, S. De Marchi, A. Sommariva and M. Vianello (see paper) - Numer. Algorithms 56 (2011)
note: interpolation at the Padua points has been inserted in the Chebfun package
see Padua points in Chebfun2 by N. Hale and A. Townsend, July 2014

3. CATCH suite. Object: Demo of least squares on a 2D mesh and least squares on a compressed mesh. Examples on union of disks and polygons. For details, see the paper F. Piazzon, A. Sommariva and M. Vianello, Caratheodory-Tchakaloff Subsampling.
