# PWmatMLFF

PWmat Machine Learning Force Field (PWmatMLFF) is an open source software under GNU license. It aims at generating force fields with accuracy comparable to Ab Initio Molecular Dynamics (AIMD). It is compatible with AIMD data with either **PWmat** or **VASP** format. Please refer to the manual for more details:

This package contains 8 types of features with translation, rotation, and permutation invariance, which are

        1. 2-body(2b)
        2. 3-body(3b) 
        3. 2-body Gaussian(2bgauss)
        4. 3-body Cosine(3bcos) 
        5. Multiple Tensor Potential(MTP)
        6. Spectral Neighbor Analysis Potential(SNAP)
        7. DP-Chebyshev(dp1)        
        8. DP-Gaussian(dp2) 

and 4 engines for training and prediction, which are 

        1. Linear Model
        2. Graphic Neural Netowrk (GNN)
        3. Deep Neural Netowrk with Kalman Filter optimizer(KFNN)
        4. DP-torch Network with Kalman Filter optimizer(KFDP) 
