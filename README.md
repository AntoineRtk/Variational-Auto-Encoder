# Variational-Auto-Encoder
Variational auto-encoders can be used to generate data. In this project, we made one to generate digits thanks to the MNIST dataset.

The goal of a variational auto-encoder is to cluster data in the latent space in order that close points share the same properties.
![Graph](https://user-images.githubusercontent.com/97120816/166149231-8f88e9a8-dfbd-4204-857a-389867a6b54e.png)
Once we made groups in the latent space, we can simply decode a random point in it in a cluster we want for this point to have certain properties.

Variational auto-encoders require statistical theory and Bayesian inference because we want the data in the latent space to form clusters following a distribution. In order to force our data to respect a distribution, we try to minimize the Kullback-Leibler divergence between the prior distribution and distribution in the latent space.

Finally, we get these results in the latent space:

![VAE MNIST](https://user-images.githubusercontent.com/97120816/166150073-283dd560-b5b0-495f-b614-5a0baea574ca.png)

that gives this output:

![VAE Latent Sample](https://user-images.githubusercontent.com/97120816/166150091-57bd8992-8847-4bc5-a983-f037da873909.png)

The report of this project can be found here:
[Deep_Learning_Project_VAE.pdf](https://github.com/AntoineRtk/Variational-Auto-Encoder/files/8599100/Deep_Learning_Project_VAE.pdf).
