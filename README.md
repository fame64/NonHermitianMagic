# NonHermitianMagic
Codes used to generate the numerical simulations for an article in Magic Steady State Production through Non-hermitian and Stochastic Non Hermitian dynamics
The numerics was done in python with Jupyter notebooks
The analytical calculations were done in Mathematica. 
The file "analytical_Calculations_NHMagic.nb" is the clean version while "SDQ_magic_Stuff.nb" contains many more calculations which may be missing from the clean one
Meaning of the abbreviations:
DQ: Dissipative Qubit (Deterministic Non-Hermitian)
SDQx: Stochastic Dissipative Qubit with hopping along sigmax (real)
SDQxy: Stochastic Dissipative Qubit with hopping along sigmax and sigmay (complex)
SRE: Stabilizer Renyi Entropy (a quantity to measure the magic of a given quantum state)
  It is shown in two types of plots SREevol shows the time evolution and SREst shows the steady state SRE
We have two types of calculations: 
  Single Trajectories refers to solving the system of SDE's in the Bloch sphere, 
  Av refers to the average solution which can be obtained analytically under certain approximations [see paper]


