# Handwritten Digit Recognition with Machine Learning (Jupyter Notebook)

## Introduction

This project is an implementation of a machine learning model for recognizing handwritten digits using Jupyter Notebooks. Given a 28x28 grid of pixel values (784 in total), the model predicts the probabilities of the input image representing digits from 0 to 9. Handwritten digit recognition has applications in various fields, including optical character recognition (OCR) and digit-based classification tasks.

## Table of Contents

<details>
<summary>Click to expand</summary>

1. [Features](#features)
2. [Getting Started](#getting-started)
   - [Prerequisites](#prerequisites)
3. [Usage](#usage)
4. [Model Architecture](#model-architecture)
5. [Dataset](#dataset)
6. [Training](#training)
7. [Results](#results)

</details>

## Features

- Recognizes handwritten digits from 0 to 9.
- Accepts input as a 28x28 pixel grid (784 pixel values).
- Provides probabilities for each digit class.

## Getting Started

### Prerequisites

Before you begin, ensure you have the following prerequisites:

- Python 3.x
- Jupyter Notebook
- Required Python libraries (NumPy, Pandas, Matplotlib)

## Usage

To use this project, follow these steps:

1. Open the Jupyter Notebook file `traing_grounds.ipynb` to train network and 'trained_network_playground.ipynb' to test trained network.
2. Follow the instructions in the notebook to train and evaluate the model.
3. Examine the results and explore the model's predictions.


## Model Architecture

The model features an input layer of 784 inputs, 2 hidden layers with 10 neurons each but can be varied by adjusting n1 and n2 in 'init_params()' function and one ouput layer with 10 nodes

## Dataset

The dataset used for training and testing is described within the Jupyter Notebook. 

## Training

The Jupyter Notebook provides step-by-step instructions on how to train the model, including hyperparameters, data preprocessing, and model saving/loading.


## Results

The results of the model, including visualizations, and insights, are available in the Jupyter Notebook.

## Contact

For questions or collaborations, you can contact me at [GitHub profile](https://github.com/itmaybehimm/).
