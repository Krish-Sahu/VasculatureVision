# VasculatureVision Project

Welcome to the VasculatureVision project repository! This repository contains code files for our microvasculature segmentation project, aimed at automating the analysis of microvascular structures in histology images from healthy human kidney tissue slides.

## Project Overview

The goal of VasculatureVision is to create a robust and accurate model for segmenting microvascular structures, including capillaries, arterioles, and venules, in 2D PAS-stained histology images. By automating this process, we aim to enhance researchers' understanding of how blood vessels are arranged in human tissues, contributing to the development of a Vascular Common Coordinate Framework (VCCF) and a Human Reference Atlas (HRA).

## Repository Structure

- `data_preparation.ipynb`: This notebook guides you through the process of generating the training and validation datasets. It ensures that the data is well-preprocessed and ready for training.
- `model_training.ipynb`: In this notebook, we provide the code for training the microvasculature segmentation model. We leverage various architectures and backbones, ultimately selecting the ResNet-152 backbone for its exceptional performance.
- `inference.ipynb`: Once the model is trained, this notebook demonstrates how to perform inference on new images for microvasculature segmentation.

## Getting Started

1. Clone this repository to your local machine using:
   ```
   git clone https://github.com/your-username/VasculatureVision.git
   ```

2. Follow the instructions in `data_preparation.ipynb` to generate your training and validation datasets.

3. Use the code in `model_training.ipynb` to train the microvasculature segmentation model. Feel free to experiment with different architectures and backbones.

4. Once trained, refer to `inference.ipynb` for guidance on using the model for segmenting microvascular structures in new images.

## Contributions

Contributions to the VasculatureVision project are welcome! Whether you're interested in enhancing the model, improving data preprocessing, or optimizing the code, feel free to submit pull requests. Let's work together to advance our understanding of microvascular structures.

## Acknowledgments

We would like to express our gratitude to the Human BioMolecular Atlas Program (HuBMAP) for providing the dataset and the opportunity to contribute to this meaningful research endeavor.

For any questions or feedback, please contact [your-email@example.com](mailto:your-email@example.com). Thank you for being a part of the VasculatureVision project!
