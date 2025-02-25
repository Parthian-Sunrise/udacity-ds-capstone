# Udacity Data Science Nanodegree Capstone CNN Project

This repository contains the code and analysis for the capstone project of Udacity's Data Science Nanodegree. The project follows the guided approach given by Udacity to build a CNN capable of classifyin dog breeds based on images or guessing what breed a human looks like based on a photo of their face.

## Project Overview

The goal of this project is to build a CNN (from scratch and then using transfer learning) to classify 133 dog breeds. 

1. Build a CNN from scratch that performs better than random chance in predicting the dog breed

2. Use transfer learning to bootstrap onto a pre-trained model to build a prediction model (significantly reduces the training burden computationally as the majority of optimisation has been previously performed).

3. As a tertiary fun task we can pass in images of people to leverage the model to predict what type of dog they look like, that at least has some scientific backing if a somewhat dubious.

## Repository Structure

- `notebooks/`: Contains the essential Jupyter Notebook for the project
- `src/`: Python functions to ease importation of data 
- `requirements.txt`: Lists the Python package dependencies required for the project.
- `saved_models/`: stores the weights for saved models developed during the process of running the notebook.
- `data/`: stores data for the project, see the Data Overview section to get information on how to download the data and the structure needed.
- `images/`: images for display in markdowns in the notebook.
- `bottleneck_features/`: stores a numpy array of the last convolutional layer output for the pre-trained VGG-16 and VGG-19 CNNs used in this project. See the Data Overview section for more detail.

## Data Overview

As the data is large I can link to it as I will not be able to upload it, however you can make free use of it using the links to download below.

1. **Dog Images**
[Download Zip](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip)
Extract and place at data/dog-project/dog_images
2. **Human Images**
[Download Zip](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/lfw.zip)
Extract and place at data/dog-project/lfw
3. **VGG-16 Bottleneck Features**
[Download Bottleneck .npz](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/DogVGG16Data.npz)
Place at bottleneck_features
4. **VGG-19 Bottleneck Features**
[Download Bottleneck .npz](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/DogVGG19Data.npz)
Place at bottleneck_features

## Licence

This code may not be copied or used as it contains elements of code provided by Udacity to guide the project. Once rated this project will be made private to respect this.

## Acknowledgements

All packages are acknowledged in the notebook as well as their current version, data is acknowledge in this readme.

## Summary of Results 

Please find a detailed summary of results on my Medium [project report](https://medium.com/@judeking_21019/udacity-data-science-nanodegree-capstone-report-dog-breed-classifier-cnn-95a86a8c7183) page.

## Getting Started

To replicate the analysis or run the code locally, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Parthian-Sunrise/udacity-ds-capstone.git
2. **Navigate to the repository:**
   ```bash
   cd udacity-ds-capstone
3. **Create virtual environment (optrional)**
   ```bash
   python3 -m venv venv
   source venv/bin/activate
4. **Install all requirements**
  ```bash
   pip install -r requirements.txt
  ```
5. **Set up pre-commits**
   ```bash
   pre-commit install
   ```
Now launch in any IDE you wish
