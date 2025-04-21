# VAE
A MiniRNN-based VAE model to generate new sequence using SBVM

We propose a MiniRNN-based Variational Autoencoder (VAE) that captures the cyclic nature of dihedral angles using Pyro’s probabilistic framework and the Sine Bivariate von Mises (SBVM) distribution. Our approach leverages a lightweight MiniRNN to efficiently encode long-range dependencies while maintaining computational efficiency. The model is  trained with Stochastic Variational Inference (SVI) and optimized via the Evidence Lower Bound (ELBO). 

To evaluate its performance, we analyze ELBO convergence, parameter distributions, and Ramachandran plots of reconstructed angles compared to real protein structures. Even though we used a small data set, but results indicate that our approach effectively captures key structural patterns, demonstrating its potential for protein conformation modeling and structural bioinformatics applications.
