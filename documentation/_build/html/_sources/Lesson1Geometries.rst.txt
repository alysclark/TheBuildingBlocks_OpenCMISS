1. Creating, reading, and visualising geometries in OpenCMISS
=============================================================
The first step in any modelling process is working out what your model geometry is. That is, what does your biological structure look like? How big is it? We then create a computational description of our model geometry, called a mesh. The mesh represents the structure of the organism that you are interested in, and depending on the mathematics of the problem you ultimately solve, may need to be refinable (i.e. you may need to describe your mesh in smaller 'chunks' than you originally  thought of to get the numerical model you are interested in to solve accurately).


In this example we work through ways to generate meshes in OpenCMISS, and how to read in a mesh that you have generated elsewhere.