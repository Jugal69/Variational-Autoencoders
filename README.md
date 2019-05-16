# Variational-Autoencoders
Variational Autoencoders(VAE) to generate new examples

1) Trained a CNN network on the MNIST dataset which comprised of only sevens with an added additional special effect.
2) Used the output of the hidden layer as a latent embedding for the training dataset which acted as an encoder of VAE.
3) Posed the learned latent embedding as a Multivariate standard normal distribution & updated the loss function accordingly.
4) Randomly sampled code vectors from the learned Multivariate Gaussian distribution to generate new digits which acted as a decoder of VAE.
5) Used the new generated digits to verify the special effect added in the original training dataset.
6) Tools/Technologies used : Pyton,Tensorflow
