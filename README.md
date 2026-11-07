
# CSC 309 - Facial Recognition System

## 1. Project Description
This project develops a facial recognition system using
Computer Vision and Supervised Machine Learning.

The system uses Python and Support Vector Machine (SVM)
to identify individuals from facial images.

## 2. Dataset
Dataset: Olivetti Faces Dataset

- Original images: 400
- Selected images: 200
- Number of individuals: 40
- Images selected per individual: 5
- Image dimensions: 64 x 64 pixels

Dataset source:
https://scikit-learn.org/stable/modules/generated/sklearn.datasets.fetch_olivetti_faces.html

## 3. Technologies Used
- Python
- Google Colab
- NumPy
- Matplotlib
- Scikit-learn
- Pillow
- Joblib

## 4. Image Preprocessing
The following preprocessing operations were performed:
- Image resizing
- Pixel normalization
- Image flattening

## 5. Machine Learning Algorithm
Support Vector Machine (SVM) with an RBF kernel
was used for facial recognition.

## 6. Model Evaluation
Training images: 160
Testing images: 40

Facial Recognition Accuracy: 92.5%

Correct predictions: 37
Incorrect predictions: 3

## 7. Evaluation Techniques
- Classification Report
- Confusion Matrix
- Actual versus Predicted Images

## 8. Project Files
- facial_recognition.ipynb
- requirements.txt
- CSC309_Facial_Recognition_Model.pkl
- classification_report.txt

## 9. How to Run the Project

Install the required libraries using:

pip install -r requirements.txt

Open the notebook in Google Colab and run
the code cells from beginning to end.

## 10. Conclusion
The project successfully demonstrates how
Computer Vision and supervised machine learning
can be used to develop a facial recognition system.

The model achieved 92.5% accuracy on the test dataset.

This project is intended for educational purposes.
