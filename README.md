# Biometrics: The Use of Facial Authentication for Deepfake Detection

This project explores the use of facial recognition to detect AI-generated deepfake images. Using Convolutional Neural Networks (CNNs) for feature extraction and Support Vector Machines (SVMs) for classification, the model was trained on a reduced version of the OpenForensics dataset.

## 📁 Dataset
- **OpenForensics** (subset of ~26,000 images)
- Categories: Real vs. Deepfake images
- Reduced size due to limited computational resources

## 🧠 Model Architecture
- CNN built using TensorFlow and Keras (Sequential API)
- SVM for final classification
- Includes version with data augmentation to improve generalization

## ⚙️ Features
- Precision, Recall, F1 Score, Confusion Matrix, Detection Speed
- Data Augmentation for model robustness
- Evaluation on training, validation, and test sets

## 📊 Results Summary
- Validation accuracy: up to 90%, but low recall and F1
- Improved speed with augmented model
- Highlighted challenges in class imbalance and limited compute

## 🚧 Challenges
- Limited computing power
- Slow training time for iterative improvements
- Overfitting in some model runs

## 📝 Future Work
- Try Functional API for multiple outputs
- Experiment with different datasets
- Optimize recall and reduce false negatives
- Add more layers or use transfer learning (e.g., XceptionNet)

## 📌 Tools Used
- Python, TensorFlow, Keras
- OpenForensics Dataset

## 📄 Author
Jade Muyambo  
Graduate Student – Data Science  
University of Miami
