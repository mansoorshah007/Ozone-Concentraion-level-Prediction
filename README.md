# Ground Level Ozone Concentraion Prediction Using Supervised Classification

## Overview

This GitHub project focuses on predicting ground level ozone concentration using classification techniques. The dataset used for this project is available in both ARFF and CSV formats in the 'Data' directory.

## Dataset

The dataset files are located in the 'Data' directory:

- **phpdReP6S.arff**: ARFF formatted file
- **phpdReP6S.csv**: CSV formatted file

## Project Structure

The project structure is organized as follows:

- **Data**: Contains the dataset files.
- **Notebooks**: Jupyter notebooks and Python scripts for handling imports and the main Ozone Layer Detection notebook.
  - **importHandler.py**: Python script includes all the imports and dependencies that are used in the project.
  - **Ozone Layer Detection.ipynb**: Jupyter notebook include all the code.

## Classes

The prediction task involves classifying ground level ozone concentrations into two categories:

1. **Low Concentration**
2. **High Concentration**

## Getting Started

To get started with the project, follow these steps:

1. Clone the repository to your local machine.
2. Install the required dependencies using the provided `requirements.txt` file even On running jupyter notebook it will automatically install all the dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Explore the dataset files in the 'Data' directory.

## Notebooks

### Ozone Layer Detection.ipynb

This Jupyter notebook contains the main implementation for predicting ground level ozone concentration using classification techniques. It covers data exploration, preprocessing, model training, and evaluation.
