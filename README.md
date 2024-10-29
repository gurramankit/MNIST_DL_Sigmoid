# Handwritten Digit Classifier using Neural Network
This project involves building a simple neural network to classify handwritten digits using the MNIST dataset, a well-known dataset in computer vision. The model aims to achieve high accuracy in recognizing digits, with your neural network reaching an accuracy of 96%

## Overview
This project is a neural network-based classifier that can identify handwritten digits with high accuracy. Using the MNIST dataset, it provides a great starting point for computer vision and deep learning projects.

## Dataset
- **Source**: [MNIST Database](http://yann.lecun.com/exdb/mnist/)
- **Size**: 60,000 training images, 10,000 test images, each 28x28 pixels.

## Problem Statement
The goal is to correctly classify handwritten digit images (0-9) by building and evaluating a neural network model.

## Project Tasks
### 1. Data Preprocessing
- Normalized pixel values for faster convergence.
- Reshaped the data to match input requirements of the neural network.

### 2. Model Building and Training
- Developed a simple neural network for classification.
- Trained the model using the training dataset, achieving 96% accuracy on the test dataset.

### 3. Evaluation
- Assessed the model performance using accuracy and visualized results with sample predictions.

## Results
- The neural network model achieved **96% accuracy** on the test dataset.

## Installation and Usage
1. Clone this repository:
    ```bash
    git clone https://github.com/gurramankit/MNIST_DL_Sigmoid.git
    ```
2. Install the required libraries:
    ```bash
    pip install -r requirements.txt
    ```
3. Run the project:
    ```bash
    python main.py
    ```

## Project Structure
- `data/` - Contains the MNIST dataset.
- `notebooks/` - Jupyter notebooks with model building and evaluation.
- `src/` - Python scripts for data processing and model implementation.
- `README.md` - Overview and instructions.
- `requirements.txt` - Dependencies for running the project.

## Additional Resources
For a detailed explanation of the approach, refer to my blog post: [Your First Deep Learning Project on Medium](https://medium.com/analytics-vidhya/get-started-with-your-first-deep-learning-project-7d989cb13ae5)

## Contact
For questions or suggestions, feel free to reach out at [ankithkumarankith122@gmail.com].

