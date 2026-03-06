# PROJECT OVERVIEW
-This project implements a machine learning classification model to recognize handwritten digits from images. The model is trained using the MNIST Dataset, which contains thousands of handwritten digit images from 0 to 9.
-The images are processed and classified using the Logistic Regression algorithm from the scikit-learn library.
-The goal of this project is to train a model that can accurately predict the digit present in an image.
Dataset

-> The project uses the MNIST dataset, which is a widely used dataset in machine learning for image classification.
        Dataset details:
           Total images: 70,000
           Training images: 60,000
           Testing images: 10,000
           Image size: 28 × 28 pixels
           Digits: 0 – 9
Each image is converted into 784 pixel features (28×28) before training the model.

-> Technologies Used:
   -Python
   -TensorFlow
   -scikit-learn
   -NumPy
   -Matplotlib

MACHINE LEARNING ALGORITHM:
-The project uses Logistic Regression for classification.
-Logistic Regression is a supervised learning algorithm used for classification problems.
-It predicts the probability that a given input belongs to a particular class.
-In this project, the algorithm classifies handwritten images into 10 classes (digits 0–9).

-> Project Workflow:
    1.Load the MNIST dataset.
    2.Preprocess the dataset.
    3.Reshape images from 28×28 to 784 features.
    4.Normalize pixel values.
    5.Train the Logistic Regression model.
    6.Predict digits on test images.
    7.Evaluate the model using accuracy and classification report.
    8.Visualize predictions using images.

-> Model Evaluation
     The model performance is evaluated using:
         -Accuracy Score
         -Classification Report
         -Visualization of predicted digits

-> EXPECTED OUTPUT:
  The program displays:
    -Predicted digit images
    -Accuracy score
    -Classification report
    -And images showing predicted digits.
     Applications

APPLICATIONS
 -Postal code recognition
 -Bank cheque processing
 -Form digitization
 -Document processing systems

CONCLUSION
    This project demonstrates how machine learning can be used to recognize handwritten digits from images. Using Logistic Regression with the MNIST dataset provides a simple but effective approach to image classification.
