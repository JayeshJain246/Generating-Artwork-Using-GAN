# Generating-Artwork-Using-GAN
converting specific artist's artwork in modern setup
dataset :
https://www.kaggle.com/code/jeff86/p8-01-cyclegan-v1/data

Generative models are one of the most promising approaches towards this goal. To train a generative model we first collect a large amount of data in some domain (e.g., think millions of images, sentences, or sounds, etc.) and then train a model to generate data like it. The intuition behind this approach follows a famous quote from Richard Feynman:
What I cannot create, I do not understand.” The trick is that the neural networks we use as generative models have a number of parameters significantly smaller than the amount of data we train them on, so the models are forced to discover and efficiently internalize the essence of the data in order to generate it.
CycleGAN incorporates a novel unpaired image-to-image translation technique that can be used for style transfer.  CNNs have been usually used with paired datasets. This approach is a very human way of unsupervised learning because the model learns what not to do and then improves itself over time. The loss functions evaluate the accuracy or the similarity between real and fake images. CycleGAN provides us the ability to perceive the plausible what-if situation? Like how it was possible for us to translate input images into Monet-esque paintings even after a century. With our implementation we were able to see how a Monet painting would look today. It gives us the ability to perceive different styles,  through the vision of the artist.
