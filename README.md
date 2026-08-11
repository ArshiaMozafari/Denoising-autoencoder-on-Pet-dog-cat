# Denoising-autoencoder-on-Pet-dog-cat
A simple from scratch autoencoder (using ResNet34 as the encoder) to reduce gaussian noise on photos, trained on Oxford-IIIT Pet dataset.
As it was trained on random gaussian noise with the factor of 0.01 to 0.1, so it will be able to reconstruct photos with that range of noise.
It simply demonstrates the idea of using AutoEncoders for denoising pupose at its simplest way: An AutoEncoder trained in a self-supervised manner, fed with Original Images + random noise, and enforced to recontruct original photos.
