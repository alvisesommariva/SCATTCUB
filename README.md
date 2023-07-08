# SCATTCUB
Cubature over scattered data

a) The main Matlab code used in our numerical tests, can be found in the folder "General" 
and is named "demo_scattcub_driver_01.m".

There You can change the domain, the algebraic degrees of exactness of the rule, cardinali-
ty and type of the scattered data.

b) For a simple usage of the algorithm, we have added the routine "demo_scattcub", where one can use one of the algorithms
to compute the wanted integrals. It makes comparisons with the algebraic rule used in the integral evaluation knowing the function evaluations at the nodes.

IMPORTANT:
The directory "EXTERNAL_ROUTINES" contains methods and cubature rules used in the paper.
