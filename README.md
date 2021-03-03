# Code-for-Holographic-dynamics-from-MERA.

This repository contains the program files of the MERA (Multi-scale Entanglement Renormalization Ansatz) 
tensor network applied to a 16 site transverse field Ising Model.  The Ising model has periodic boundary conditions.

The boundary (or UV) region is where the Ising model is located. 
The MERA circuit resides in the bulk space, which consists of alternating rows of disentangler and isometry operators.  
The disentangler operators act to remove entanglement in the components of the Ising model on a scale by scale basis.
The isometry operators serve to coarse grain the system.  

The Hilbert spaces of the UV and bulk have the same dimension.
