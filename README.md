This is a repository for code to compute the divergent and non-divergent wind components using available horizontal U and V wind components. 
The main features of the code are:
  1. Computation of the irrotational and non-divergent components of the wind (Helmholtz decomposition)
  2. Local Hadley-Walker circulation characterized by streamfunction and vertical velocities. 

The code is built into a single class under the file: decompose_wind.py. 

An example code with comments is found under the file: example.py

The decomposition is based on the study of Schwendike et al., (2014), which decomposes a full 3D circulation into 2 orthogonal 2D circulations, which is also called the $\psi$ method originally proposed by Keyser et al., (1989).
