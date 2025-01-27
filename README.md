# Udacity Data Science Nanodegree Recommendation Engine Project

This repository contains the code and analysis for the recommendation engine project of Udacity's Data Science Nanodegree. The project involves exploring a dataset and implementing a guided recommendation engine.

## Project Overview

The goal of this project is to apply basic recommendation techniques to a dataset of articles and user ids. 

## Repository Structure

- `notebooks/`: Contains Jupyter Notebook for the project
- `src/`: Python functions to ease importation of data 
- `.gitignore`: Specifies files and directories to be ignored by git.
- `.pre-commit-config.yaml`: Configuration for pre-commit hooks.
- `requirements.txt`: Lists the Python package dependencies required for the project.

## Data Overview

The data is Udacity's and can be found in the appropriate workspace location, as the data is not open source I will not upload this to GitHub.

## Licence

This code may not be copied or used as it contains elements of code provided by Udacity to guide the project. Once rated this project will be made private to respect this.

## Acknowledgements

All packages are acknowledged in the notebook as well as their current version, data is acknowledge in this readme.

## Summary of Results 

Due to low overlap in test and training sets for sparse prediciton problems, FunkSVD is an advisable practical step to allow for more overlap through the prediction of unseen data.

## Getting Started

To replicate the analysis or run the code locally, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Parthian-Sunrise/udacity-ds-recom-engine.git
2. **Navigate to the repository:**
   ```bash
   cd uudacity-ds-recom-engine
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
