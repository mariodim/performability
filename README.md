# Performability of 5G infrastructures

The code implements the Multidimensional Universal Generating Function (MUGF) method adopted to characterize performability of 5G infrastructures as detailed in the paper entitled "Performability of Service Chains with Rejuvenation: A Multidimensional Universal Generating Function Approach"
by Luigi De Simone, Mario Di Mauro, Roberto Natella, Fabio Postiglione submitted to IEEE Transactions on Emerging Topics in Computing.

The code has been tested on Wolfram (TM) Mathematica version 12.X.
It is released as a pdf file, and it is enough to copy/paste the code into a file with extension .nb and load it in Mathematica before running it.

The values of parameters are the same of the paper (but they can be changed to test different configurations).
Please also note that all the comments in the Mathematica code are enclosed into (\*...\*).

The output is returned in terms of a set of possible redundant Open5GS configurations (arranged as a chain of 3 nodes: AMF, SMF, UPF), 
with the performance constraint dmax (set to 0.5 sec in the code). 
Among the configurations evaluated, it is possible to extract the optimal one (in terms of number of "nines" for the availability), or to display a limited subset of configurations, leaving the network designer to choose the optimal one according to different and personal criteria.

The pdf file with the code can be downloaded here: 
https://drive.google.com/file/d/1v9uroITImO2e0A1DHsQBmm8VACPNABVf/view?usp=sharing
