# Week 5: GANs and Monet Kaggle Mini-Project

This is the mini-project for Week 5 of CSCA 5642: Introduction to Deep Learning.

As part of this project, we will compete in the Monet Style Image Generation competition. The primary goal of the competitoin is to build a model that will produce Monet-style images based on "normal" input images.

This type of problem is typically addressed using a GAN (Genrative Adversarial Network) which consists of at least two neural networks: a generator and a discriminator. The generator is used to generate the images, while the discriminator is used to train the generator during model training. For this specific type of problem, which is sometime termed "style transfer", a [CycleGAN](https://www.geeksforgeeks.org/machine-learning/cycle-generative-adversarial-network-cyclegan-2/) us commonly used since it does not need paired data for training.
