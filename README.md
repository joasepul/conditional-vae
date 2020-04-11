# Conditional Image Synthesis using a Variational Autoencoder
Trained on: Large-scale CelebFaces Attributes (CelebA) Dataset 

VAE trained to model (64,64) size images and 40 attributes to a 100-dim latent.

Allows the linear sweep of facial attributes by just increasing or decreasing the input attribute to the decoder.
### Results
This model was trained to 500 Epochs on a Titan xp.
This face was sampled from a gaussian distribution, attributes were then selected initially to generate a realistic face.
These are some of the different effects of sweeping a few attributes, for more please see the gifs/ directory.

#### Black Hair attribute sweep
![Black hair attribute sweep](/gifs/gifs-sample-1-200kimgs/Black_Hair.gif?raw=true "Black hair attribute sweep")

#### Gender attribute sweep
![Gender attribute sweep](/gifs/gifs-sample-1-200kimgs/Male.gif?raw=true "Gender attribute sweep")

#### Bangs attribute sweep
![Bangs attribute sweep](/gifs/gifs-sample-1-200kimgs/Bangs.gif?raw=true "Bangs attribute sweep")

#### Smiling attribute sweep
![Smiling attribute sweep](/gifs/gifs-sample-1-200kimgs/Smiling.gif?raw=true "Smiling attribute sweep")

#### Makeup attribute sweep
![Makeup attribute sweep](/gifs/gifs-sample-1-200kimgs/Heavy_Makeup.gif?raw=true "Makeup attribute sweep")
