#Project
## Explainable AI for Diabetic Retinopathy Detection with DenseNet121 and LIME
This repository demonstrates the use of Deep Learning and Explainable AI techniques for diabetic retinopathy detection. The model is built on the DenseNet121 architecture, fine-tuned on the APTOS dataset, with Gaussian filtering applied for enhanced feature extraction.

Key features:
Model Architecture: DenseNet121 with a custom classification head (Flatten, Dense(128, ReLU), Dropout(0.4), Softmax).
Training Accuracy: Achieved 99.4% accuracy on training data and 93.24% accuracy on the test set, using 128x128 input images.
Explainability: Integrated LIME (Local Interpretable Model-agnostic Explanations) to provide transparent insights into the model's predictions.
Dataset: APTOS Diabetic Retinopathy dataset with Gaussian-filtered preprocessing for improved model performance.

This project aims to bridge the gap between deep learning-based automated diagnostic tools and healthcare professionals by providing interpretability and trust in model predictions.
