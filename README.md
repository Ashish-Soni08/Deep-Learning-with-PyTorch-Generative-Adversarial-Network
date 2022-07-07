# Deep-Learning-with-PyTorch-Generative-Adversarial-Network

Task 1: Setup google runtime

- Setup google colab

Task 2: Configurations

- Declare configurations for the project

Task 3: Load MNIST handwritten dataset

- Download MNIST dataset
- Apply Random Rotation Transformations to Images and convert to PyTorch tensors

Task 4: Load dataset into batches

- Use DataLoader to load dataset in batches
- Plot Multiple Images

Task 5: Create discriminator network

- Discriminator network, is a simple binary classifier which classifies whether a given image is real or fake
- We are not using Sigmoid layer because we are using binary cross entropy with logit loss which takes raw output without any sigmoid activation. The sigmoid layer gets applied in the loss function

Task 6: Create generator network

- The goal of the generator network is to produce realistic fake images. Given random noise, generator network takes the random noise to generate a fake image

Task 7: Create loss function and load optimizers

- Define two loss functions that will be useful to compute Discriminator loss and the Generator loss in the training loop
- Define optimizers for Discriminator and Generator

Task 8: Create training loop to train GAN

- Train the GAN model
