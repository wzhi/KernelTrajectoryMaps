# KernelTrajectoryMaps
KTMs leverage the power of kernels to achieve powerful results, without the need for layers and layers of neural networks. 

Please find a jupyter notebook tutorial of our KTM method. The main challenge here would be to install the library that allows frechet distances to be calculated efficiently https://github.com/bguillouet/traj-dist

Lank_1_nn and Lank_2_nn.npy contain trajectories from the NGSIM Lankershim dataset, from an intersection. The code allows the user to train up a KTM evaluate it, and then use it to predict a mixture of stochastic processes, where the trajectories can be sampled.

Note that with the jupyter notebook, please run the cells one by one.

Also note that for generating the frechet distances between trajectories, and converting discrete tareget trajectories to continuous functional representations, these only need to be run once, as the results of these computations are stored as .npy files.
