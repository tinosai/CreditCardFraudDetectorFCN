# CreditCardFraudDetectorFCN
Making of a Credit Card Fraud Detector using a Fully-Connected Neural Network in PyTorch

## Project Overview

In this project we will develop a Credit Card Fraud Detector using a Fully-Connected Neural Network (FCN).

The project will first lead you through the preprocessing of the csv data using pandas. Then you will use TensorDataset and DataLoader utilities to build the PyTorch loaders. Finally, you will initialize the network, train and calculate F1-score and AUC to get a feel of how good the model is.

## Project Instructions

### Instructions

1. Clone the repository on your computer. For those who are not familiar with command line utilities, GitHub has developed this utility which lets do pretty much everything you need through a GUI.
   [GitHub Desktop](https://desktop.github.com/)
2. Download the dataset (the link is included in the jupyter notebook).
3. Open a terminal window and navigate to the project folder. Open the notebook and follow the instructions.

__NOTE:__ Chances are part of the code may not run due to some missing packages. Please make sure to go through the notebook and retrieve all the necessary packages. In a future release, I will include the list of packages needed (in the form of a python environment file).

## GPU

Training this Neural Network will definitely take a long time. As a result, it would be a good idea to train on a GPU. On AWS, I believe a p2.xlarge instance should be enough for training (and keeping the costs limited).
In addition, I recommend that you only switch to GPU when you're about to train, and you instead write all your code while in a CPU environment to keep costs down.

## GitHub rendering Problems

Sometimes GitHub cannot render the jupyter notebook properly. In such a situation, go to the [nbviewer website](https://nbviewer.jupyter.org/) and copy and paste the URL address of the notebook so as to render it on the browser.
