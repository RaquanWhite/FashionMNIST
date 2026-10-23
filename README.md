Fashion-MNIST Image Classification Using PyTorch

Project Overview

This project implements a Convolutional Neural Network (CNN) using PyTorch to classify grayscale clothing images from the Fashion-MNIST dataset.

The objective is to demonstrate practical applications of deep learning, computer vision, neural network training, and model evaluation.

Developed as part of the IBM AI Engineering Professional Certificate learning pathway.

Model Performance

Metric

Result

Dataset

Fashion-MNIST

Deep Learning Framework

PyTorch

Model Architecture

Convolutional Neural Network (CNN)

Training Epochs

5

Validation Accuracy

Approximately 89.9%

Optimization Algorithm

Stochastic Gradient Descent (SGD)

Learning Rate

0.1

Loss Function

Cross-Entropy Loss

Training Results

During training, the model demonstrated:

A consistent decrease in training loss across five epochs.

Improved validation accuracy throughout training.

Approximately 89.9% validation accuracy by the final epoch.

These results demonstrate the CNN's ability to learn visual features and classify previously unseen clothing images.

Technologies Used

Python — Model development and data processing

PyTorch — Deep learning framework

Torchvision — Dataset loading and image transformations

NumPy — Numerical operations

Matplotlib — Training performance visualization

Google Colab — Cloud-based notebook development

Neural Network Architecture

The model uses a convolutional neural network featuring:

Convolutional layers for image feature extraction.

Batch normalization to support stable training.

ReLU activation functions to introduce nonlinearity.

Max pooling layers to reduce spatial dimensions.

A fully connected layer for classification.

The model produces output scores for 10 clothing categories.

Dataset

Fashion-MNIST contains 70,000 grayscale images across 10 categories, including:

T-shirts/tops

Trousers

Pullovers

Dresses

Coats

Sandals

Shirts

Sneakers

Bags

Ankle boots

The dataset contains 60,000 training images and 10,000 test images.

Model Training

The training workflow consists of:

Loading and preprocessing the Fashion-MNIST dataset.

Applying image transformations.

Creating training and validation DataLoaders.

Defining the CNN architecture.

Configuring cross-entropy loss and SGD optimization.

Training the network for five epochs.

Evaluating classification accuracy.

Visualizing training loss and validation accuracy.

Running the Project

Download the FashionMNISTProject-v1.ipynb notebook.

Open the notebook in Google Colab or Jupyter Notebook.

Install the required Python libraries if necessary.

Execute the notebook cells sequentially.

Review the resulting training loss and validation accuracy graph.

Skills Demonstrated

Deep Learning

Computer Vision

Convolutional Neural Networks

PyTorch Model Development

Image Classification

Data Preprocessing

Neural Network Optimization

Model Evaluation

Python Programming

Future Improvements

Potential improvements include:

Experimenting with additional convolutional layers.

Comparing different optimization algorithms.

Evaluating model performance using a confusion matrix.

Implementing data augmentation.

Testing transfer learning with pretrained architectures.

Deploying the trained model as an interactive image classification application.

About the Developer

I am an engineering and infrastructure planning professional transitioning into Artificial Intelligence and Machine Learning Engineering, with a background in computational mathematics, engineering, and technical problem-solving.

My focus is on developing practical AI solutions that automate workflows, improve decision-making, and solve real-world challenges, particularly within construction, infrastructure, and engineering.

This project represents part of my continued development in deep learning, computer vision, and AI software engineering.

Acknowledgments

Developed through the IBM AI Engineering Professional Certificate curriculum using PyTorch and the Fashion-MNIST dataset.
