This project focuses on building a Convolutional Neural Network (CNN) to recognize whether individuals are wearing face masks or not. Using a dataset sourced from Kaggle, the notebook walks through the process of data preprocessing, model training, and evaluation.

Key Features:

1.Data Collection:

The dataset is downloaded from Kaggle using its API, specifically the "Face Mask Dataset" by Omkar Gurav.
The dataset contains images of people with and without face masks, stored in separate directories.

2.Data Preprocessing:

The images are extracted from a zip file and organized into categories: "with mask" and "without mask."
Labels are created for each category: 1 for "with mask" and 0 for "without mask."

3.Exploratory Data Analysis (EDA):

The dataset includes 3,725 images of individuals wearing masks and 3,828 images of individuals without masks, for a total of 7,553 images.

4.Model Building:

A CNN model is built to classify the images.
The model is trained using Keras or TensorFlow, with convolutional layers to extract features from the images and dense layers for classification.

5.Model Evaluation:

The model is evaluated using accuracy metrics, and predictions are made to assess its effectiveness in detecting masks.
Implementation:

The project also demonstrates the use of data augmentation and other techniques to improve the generalizability of the model.
