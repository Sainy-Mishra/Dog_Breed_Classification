# 🐶 Dog Breed Classification using TensorFlow 2.0

## Overview
This project is an end-to-end multi-class dog breed classification system using deep learning. It leverages TensorFlow 2.0 and TensorFlow Hub to classify images of dogs into their respective breeds.

## 💻 Dataset
The dataset is downloaded using the Kaggle API and contains images of various dog breeds for training and testing.

## 🤖 Technologies Used
- Python
- TensorFlow 2.0
- TensorFlow Hub
- NumPy
- Pandas
- Matplotlib

## Setup Instructions
### 1. Clone the Repository
```bash
git clone "https://github.com/Sainy-Mishra/Dog_Breed_Classification.git"
cd dog-breed-classification
```
### 2. Run the Notebook
Execute the Jupyter Notebook to train and test the model:
```bash
jupyter notebook dog_vision.ipynb
```

## Model Details
The project utilizes:
- MobileNet V2 from TensorFlow Hub
- Convolutional Neural Networks (CNNs) for feature extraction
- Image augmentation techniques for better generalization

## Results
After training, the model predicts the breed of a dog given an input image. The performance is evaluated based on accuracy and loss metrics.

## 📊 Future Improvements
- Implementing additional deep learning architectures
- Deploying the model as a web application
