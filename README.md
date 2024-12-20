# Road Segmentation from Satellite Images

This repository contains code for a semantic segmentation project focused on identifying roads from satellite imagery. The goal is to classify each pixel as either 'road' or 'background' using deep learning models. The project is built around AIcrowd's dataset and evaluates model performance based on the F1 score. 

## Repository Structure

### `data_augmentation/`
This folder contains scripts for applying various data augmentation techniques to improve the diversity of the training dataset. These include:
- Rotations
- Flips (horizontal and vertical)
- Scaling
- Cropping
- Brightness and contrast adjustments

### `models/`
This folder provides the implementation of the deep learning models used for segmentation. It includes:
- **U-Net**: A widely-used architecture for semantic segmentation.
- **SegFormer**: A transformer-based model for pixel-wise classification.
- **PSPNet**: Pyramid Scene Parsing Network for capturing multi-scale context.
- **DeepLab**: A model leveraging atrous convolutions for segmentation.

## Key Features
- **Customizable Data Augmentation**: Enhance the training data with flexible augmentation techniques.
- **Multiple Models**: Experiment with different state-of-the-art architectures.

## Dataset
The project uses AIcrowd's satellite image dataset, consisting of:
- **Training Images**: 700 RGB images (400x400 pixels)
- **Masks**: Corresponding ground truth masks for road and background labeling

## Evaluation Metric
The project uses the F1 score as the primary evaluation metric, emphasizing a balance between precision and recall.

## Future Work
- Add additional preprocessing and postprocessing scripts.
- Incorporate hyperparameter tuning utilities.
- Extend the model suite with more architectures.

## Acknowledgments
- Special thanks to our instructor, **Dr. Tamam Alsarhan**, for their guidance and support.
- AIcrowd for providing the dataset.
- Open-source libraries and frameworks used in the project.

 ## Team Members:
  - Beesan Al-Attal
  - Layan Balbisi
  - Leen Samman
  - Zaina Abu-Naser
