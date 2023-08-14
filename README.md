# Generative adversarial networks GAN-

**Abstract**
 
The main claim of the original paper \cite{goodfeli-adversarial} by Ian Goodfellow et al. titled "Generative Adversarial Networks" is that the proposed Generative Adversarial Network (GAN) framework is capable of generating high-quality synthetic samples that are indistinguishable from real samples. The authors claim that GANs can learn to generate data that is similar to real data by training a generator network to produce samples that are close to real data and training a discriminator network to differentiate between real and fake data. The generator and discriminator networks are trained in a two-player minimax game, where the generator tries to produce fake data that is similar to real data, while the discriminator tries to distinguish between real and fake data.
Overall, the main goal of reproducing this paper would be to confirm whether the proposed GAN framework is indeed capable of generating high-quality synthetic data, and to investigate whether the findings reported in the original paper can be replicated.

**Methodology**



Our project aimed to replicate the experiments outlined in the seminal paper on Generative Adversarial Networks (GANs) by using open-source code from the authors \cite{goodfeli-adversarial}, the published paper \cite{gan}, and code provided by Brownlee \cite{brownlee2019developgan}. By exploring the widely recognized and promising GAN framework in deep learning, we sought to gain further insight into its potential applications. Our team successfully reproduced the results reported in the original paper for both the MNIST and CIFAR-10 datasets. In addition to replicating the experiments, we conducted an ablation study on the MNIST dataset to determine which components were essential for achieving a certain level of performance and which were not.%The ablation study allowed us to better understand the underlying mechanisms of the GAN framework and to potentially identify areas for improvement.%
However, due to limited computational resources and time constraints, we were only able to conduct the ablation study on the MNIST dataset.
