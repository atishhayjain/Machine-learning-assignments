# Face Recognition using CNN (LFW Dataset)

## Project Overview

This project implements a Face Recognition system using a Convolutional Neural Network (CNN) with Transfer Learning on the Labeled Faces in the Wild (LFW) dataset. The model classifies facial images into different person identities using deep learning techniques.

---

## Dataset

**Dataset:** Labeled Faces in the Wild (LFW)

The LFW dataset contains face images of well-known individuals collected from the web under different lighting conditions, facial expressions, and poses.

Number of Classes: 7

Classes:
- Ariel Sharon
- Colin Powell
- Donald Rumsfeld
- George W. Bush
- Gerhard Schroeder
- Hugo Chavez
- Tony Blair

---

## Technologies Used

- Python
- TensorFlow
- Keras
- Scikit-Learn
- NumPy
- Matplotlib

---

## Project Workflow

1. Load LFW Dataset
2. Data Preprocessing
3. Image Normalization
4. Convert Grayscale Images to RGB
5. Resize Images to 96×96
6. Train-Test Split
7. Build CNN using MobileNetV2 Transfer Learning
8. Model Training
9. Performance Evaluation
10. Face Prediction

---

## Model Architecture

- MobileNetV2 (Pre-trained CNN)
- Global Average Pooling
- Dense Layer (256)
- Dropout (0.5)
- Dense Layer (128)
- Dropout (0.3)
- Softmax Output Layer

---

## Results

Test Accuracy:

**41.09%**

The model successfully learns facial representations and performs multiclass face recognition on the LFW dataset.

---

## Output

The notebook includes:

- Sample Images
- Accuracy Curve
- Loss Curve
- Confusion Matrix
- Classification Report
- Face Prediction Visualization

---

## Future Improvements

- Fine-tune MobileNetV2 layers
- Apply Data Augmentation
- Hyperparameter Optimization
- Train for More Epochs
- Balance Dataset Classes
- Use FaceNet or ResNet50 for improved accuracy

---

## Author

**Atishay Jain**

B.Tech CSE (Artificial Intelligence & Machine Learning)
