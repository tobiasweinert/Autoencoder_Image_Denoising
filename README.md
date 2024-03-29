# Autoencoder_Image_Denoising
A simple autoencoder for image denoising, written in python using Keras and the MNIST dataset.
Run the program from the Terminal: python autoencoder.py

This will train the Model using MNIST and save the trained Model. The saved model will be loaded the next time it is called to eliminate redundant training.
Also the noised inputs and denoised outputs will be displayed using Matplotlib.

This is part of a small research paper I've written on convolutional autoencoders for image denoising which you can read [here](https://raw.githubusercontent.com/tobiasweinert/Autoencoder_Image_Denoising/6e43b36d35213684df6ca6cc6050d207678bb1d8/Convolutional_Auto_Encoder_For_Image_Denoising_Tobias_Weinert.pdf).
