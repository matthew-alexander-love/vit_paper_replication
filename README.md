# Vision Transformer (ViT) - PyTorch Implementation

This repository contains my implementation of the Vision Transformer (ViT), based on the original paper by Dosovitskiy et al., in PyTorch. The implementation replicates key aspects of the Vision Transformer model, with adaptations and modifications for supervised learning both with and without pretraining.
Project Structure

## Overview

The Vision Transformer (ViT) introduces a novel approach to image classification, applying transformer architectures to vision tasks. Transformers, originally developed for NLP tasks, are used in this work to model sequences of image patches, achieving state-of-the-art performance without the need for convolutional networks.

In this project, you can find:

 - Supervised learning with and without pretraining: Models trained from scratch as well as pre-trained models adapted for vision tasks.
 - Efficient training and evaluation loops: Custom training code in engine.py with utilities for flexible experimentation.
 - Helper functions: Various utilities in helper_functions.py for logging, metric calculations, and more.

## Setup

To get started, clone the repository and install the necessary dependencies. You can use the following command to install dependencies:

pip install -r requirements.txt

Ensure you have PyTorch installed. You can refer to the official PyTorch installation guide for your system.

For a quick overview and demonstration of the Vision Transformer model, check out the vision_transformer.ipynb notebook. It walks through the model's key concepts and shows how to train and evaluate the ViT model on a sample dataset.
## Credits

This project was inspired by the Vision Transformer paper by Dosovitskiy et al. A significant portion of the initial setup was adapted from the excellent tutorial on Learn PyTorch: https://www.learnpytorch.io/08_pytorch_paper_replicating/
## License

This project is licensed under the MIT License.