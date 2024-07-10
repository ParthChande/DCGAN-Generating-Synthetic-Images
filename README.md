# DCGAN-Generating-Synthetic-Images
# DCGAN for Fashion MNIST

This project demonstrates the implementation of a Deep Convolutional Generative Adversarial Network (DCGAN) using TensorFlow and Keras to generate synthetic images of Fashion MNIST dataset.

You can learn more about DCGAN in ```More Info.md```

## Requirements

- TensorFlow
- NumPy
- Matplotlib
- tqdm
- imageio

## Setup

Install the required libraries using pip:

```bash
pip install tensorflow numpy matplotlib tqdm imageio
 ```
## Code Explanation

- Imports and Setup: Import necessary libraries and set up the environment.
- Loading and Preprocessing Data: Load the Fashion MNIST dataset and normalize the pixel values.
- Display Sample Data: Display a sample of the training images.
- Create Batches: Create batches of training data using TensorFlow's tf.data.Dataset.
- Build Generator Network: Define the Generator model with fractionally-strided convolutions.
- Build Discriminator Network: Define the Discriminator model with convolutional layers.
- Compile Models: Compile the Discriminator and the combined GAN model.
- Training Function: Define the training loop to train both the Generator and Discriminator.
- Generate and Save Images: Define a function to generate and save synthetic images during training.
- Train DCGAN: Train the DCGAN model on the dataset.
- Generate Synthetic Images: Generate a batch of synthetic images using the trained Generator.
- Create GIF: Create a GIF to visualize the training process.
  
This process results in a trained DCGAN that can generate synthetic images similar to the real images in the dataset.
