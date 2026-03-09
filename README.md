# Cats vs Dogs Image Classification using SVM

## Project Overview

This project implements a **Support Vector Machine (SVM)** model to classify images of **cats and dogs**.
The model is trained using the **Dogs vs Cats dataset** available on Kaggle.

The goal of the project is to demonstrate how machine learning can be used for **image classification tasks** by extracting features from images and training an SVM classifier.

---

## Dataset

Dataset Source: Kaggle – Dogs vs Cats Dataset

The dataset contains thousands of labeled images belonging to two categories:

* Cat
* Dog

Each image is labeled according to the animal present in the image.

Dataset structure example:

dataset/
│
└── train/
  ├── cat.1.jpg
  ├── cat.2.jpg
  ├── dog.1.jpg
  ├── dog.2.jpg

---

## Technologies Used

* Python
* OpenCV
* NumPy
* Scikit-learn
* Matplotlib

---

## Machine Learning Algorithm

This project uses the **Support Vector Machine (SVM)** algorithm for classification.

SVM works by finding the optimal hyperplane that separates data points into different classes. In this project, the two classes are **cats** and **dogs**.

---

## Project Workflow

1. Download dataset from Kaggle
2. Load images from the dataset
3. Resize images to a fixed size
4. Convert images into feature vectors
5. Split the dataset into training and testing sets
6.Train the SVM model
7.Evaluate the model performance using accuracy
8.Predict whether a new image is a cat or a dog

## Installation

Install the required Python libraries:
pip install numpy pandas matplotlib scikit-learn opencv-python

## Model Evaluation

The model performance is evaluated using:
Accuracy Score
Classification Report
Example Output:
Model Accuracy: 0.82

## Future Improvements

Use Convolutional Neural Networks (CNN) for better accuracy

1.Implement image augmentation
2.Deploy the model as a web application
3.Improve preprocessing techniques

## License

This project is for educational purposes.
