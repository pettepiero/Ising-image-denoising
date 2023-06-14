# Ising model for simple image denoising
Group project for Probabilistic Machine Learning course by Luca Bortolussi (UNITS) 2023. The group members are: Noemi Ippolito, Piero Pettenà and Maria Pronestì.

The goal of this project is to perform some simple image denoising on black and white images (or figures). Random noise is added to these images and the Ising model is used to try to remove it.

A Markov Random Field is used to represent the problem, where each node corresponds to a single pixel of the image. As the following figure shows (source:  *Pattern Recognition and Machine Learning by Bishop*), a 2 layered structure is considered, where x nodes represent the real pixels and y nodes represent the observed pixels.

![Screenshot from 2023-06-14 11-50-01](https://github.com/pettepiero/Ising-image-denoising/assets/81314827/fcfd26d4-fea8-4625-8c8a-133232f33cd3)

At the moment of creation of this project, the goal is to use ICM and different sampling techniques, but updates will follow. 
