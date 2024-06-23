# Fashion-MNIST

![GeneratorDiscriminator](https://developers.google.com/static/machine-learning/gan/images/gan_diagram_generator.svg)

## Steps in building a GANN
1) Generator is a neural network which takes noise as input and outputs a randomly generated image
2) This generated image is passed to the Discriminator which tries to differentiate between Real and Fake Images
3) 0 - True, 1 - Fake
