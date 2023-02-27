# Image Classification with tensorflow and pytorch

Image Classification for Happy and Sad Emotions using PyTorch and TensorFlow
This project aims to classify images into two categories, happy and sad emotions, using PyTorch and TensorFlow deep learning frameworks. The dataset used for this project is the "Facial Expression Recognition Challenge" dataset available on Kaggle.

Getting Started

Prerequisites

```
Python 3.7 or later
Torch 1.12.1+cu113
TensorFlow 2.4.1 or later
Jupyter Notebook
```

Installing

Clone this repository using the following command:

```
git clone https://github.com/Atomic-man007/Image_Classification.git
```

Create a new virtual environment and activate it:


python3 -m venv venv
source venv/bin/activate
Install the required packages using pip:

pip install -r requirements.txt


The "Facial Expression Recognition Challenge" dataset images of faces, labeled with seven categories of emotions: angry, disgust, fear, happy, neutral, sad, and surprise. 

In this project, we only used images labeled as happy or sad.

You can scrape the dataset from google search for *happy people* and *sad people*

**Jupyter Notebooks**

This project contains two Jupyter notebooks: one for PyTorch and one for TensorFlow.

`pytorch.ipynb`: This notebook contains the code for image classification using PyTorch.
`tensorflow.ipynb`: This notebook contains the code for image classification using TensorFlow.


Both notebooks contain the following sections:

**Data loading and preprocessing**
**Data visualization**
**Model creation and training**
**Model evaluation**
**Training**

To train the models, run the Jupyter notebooks and execute all cells. The models will be trained using the training set and validated using the validation set. After training, the accuracy and loss curves will be plotted, and the models will be saved to disk.

**Evaluation**
To evaluate the models, run the Jupyter notebooks and execute all cells. The models will be loaded from disk, and the test set will be used to evaluate the models. The accuracy and loss values will be printed to the console, and the confusion matrix will be plotted.
