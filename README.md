🌾 Rice Leaf Disease Detection using Deep Learning
📌 Project Overview

This project focuses on detecting and classifying rice leaf diseases using Deep Learning and Computer Vision techniques. The model analyzes images of rice leaves and identifies the disease category, helping farmers and agricultural experts take early preventive actions to reduce crop loss and improve yield.

The project uses both a Custom CNN Model and MobileNetV2 Transfer Learning Model for image classification and compares their performance to select the best model for deployment.

🎯 Problem Statement

Rice crops are vulnerable to various diseases that can significantly affect productivity. Manual disease identification is time-consuming and requires expert knowledge. This project aims to automate disease detection using image classification techniques.

📂 Dataset

The dataset contains images belonging to the following rice leaf disease categories:

Bacterial Leaf Blight
Brown Spot
Leaf Smut
Dataset Processing
Image Resizing (224 × 224)
Image Normalization
One-Hot Encoding
Train-Test Split
Data Augmentation
🛠️ Technologies Used
Python
TensorFlow / Keras
OpenCV
NumPy
Pandas
Matplotlib
Seaborn
Scikit-Learn
🔍 Exploratory Data Analysis (EDA)

The project includes:

Dataset Information Analysis
Missing Value Check
Class Distribution Visualization
Sample Image Visualization
Image Dimension Analysis
🤖 Models Implemented
1️⃣ Custom CNN
Convolution Layers
Batch Normalization
Max Pooling
Dropout Regularization
Dense Layers
2️⃣ MobileNetV2 (Transfer Learning)
Pretrained ImageNet Weights
Feature Extraction
Global Average Pooling
Dense Classification Layer
📊 Model Evaluation

Evaluation metrics used:

Accuracy Score
Confusion Matrix
Classification Report
Model Comparison Visualization

The best-performing model is saved for future deployment and real-world predictions.

🚀 Key Features

✅ Rice leaf disease classification
✅ Deep Learning-based image recognition
✅ Transfer Learning with MobileNetV2
✅ Data Augmentation for better generalization
✅ Model Performance Comparison
✅ Production-ready model saving

📈 Business Impact

Early detection of rice leaf diseases can:

Reduce crop damage
Improve agricultural productivity
Support farmers in decision-making
Lower treatment costs
Increase overall crop yield
⚠️ Challenges Faced
Limited dataset size
Risk of overfitting
Variation in image quality
Class imbalance considerations
Computational requirements for model training
🎯 Future Enhancements
Deploy as a Web Application using Flask/Streamlit
Mobile App Integration
Real-time Disease Detection
Support for Additional Crop Diseases
Cloud Deployment for Scalability
🏆 Conclusion

This project successfully demonstrates the application of Deep Learning in agriculture by automating rice leaf disease detection. Both Custom CNN and MobileNetV2 models were implemented and evaluated, with the best-performing model selected for deployment. The solution has the potential to assist farmers in early disease identification and improve crop management practices.
