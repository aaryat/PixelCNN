# PixelCNN
IITB Internship
Project Title: PixelCNN Implementation for Image Generation

**Overview:**

This repository contains an implementation of the PixelCNN model for image generation. PixelCNN is a generative neural network architecture capable of generating images pixel by pixel. This project provides implementations for both grayscale and RGB image generation using the PixelCNN architecture.

**Features:**

1. **Grayscale Image Generation (MNIST Dataset):** You can train and use a PixelCNN model to generate grayscale images using the MNIST dataset. The model captures complex dependencies within the images and can generate new samples pixel by pixel.

2. **RGB Image Generation (CIFAR-10 Dataset):** We also provide an implementation for RGB image generation using the CIFAR-10 dataset. This model generates color images pixel by pixel, taking into account the complex relationships between color channels.

3. **Customizable Model:** The architecture of the PixelCNN model is highly customizable. You can adjust the number of residual blocks, mask types, and other hyperparameters to experiment with different configurations.

4. **Efficient Training:** The code includes options for efficient training, including batch processing and GPU acceleration using TensorFlow and Keras.

**Getting Started:**

To get started with using this PixelCNN implementation, follow these steps:

1. Clone this GitHub repository to your local machine.

2. Install the required dependencies.

3. Use the provided Jupyter notebooks or Python scripts to train and generate images using the PixelCNN model.

4. Experiment with different model configurations, datasets, and hyperparameters to see how they affect image generation.

**References:**

- [Pixel Recurrent Neural Networks (arXiv)](https://arxiv.org/abs/1601.06759)
- [Conditional Image Generation with PixelCNN Decoders (ICML)](http://proceedings.mlr.press/v70/oord17a/oord17a.pdf)

Feel free to explore the code and contribute to further enhancements or applications of the PixelCNN model for image generation. If you have any questions or feedback, please don't hesitate to reach out.
