# **Handwritten Digit Recognition Using Neural Networks**

This project was done in collaboration with Bing Wang, Behnaz Refahi, and Camille Mirmiran.

We utilize the **MNIST dataset**, a widely recognized benchmark dataset for handwritten digit recognition. The dataset is included in this repository as `dataset.mat`.

## **Project Overview**

This project demonstrates the implementation of a neural network to recognize handwritten digits. Handwriting recognition is a challenging problem due to variations in writing styles, but through machine learning, specifically neural networks, we can achieve high accuracy in digit classification.

### **Key Features**

1. **Data Handling**:
   - Dataset normalization scales pixel values between 0 and 1.
   - Sample digits are visualized for initial data exploration.

2. **Model Building**:
   - A feed-forward network with a Softmax output layer is implemented for digit classification.
   - Gradients are computed and verified to ensure correctness in backpropagation.

3. **Training and Optimization**:
   - Mini-batch gradient descent is utilized for efficient optimization.
   - Cross-entropy loss function ensures precise classification.

4. **Performance Analysis**:
   - Evaluation of classification accuracy on the test dataset.
   - Learning curves and heatmaps are analyzed for insights into training and feature detection.

5. **Advanced Features**:
   - A deeper neural network with a hidden layer and **tanh** activation function is implemented.
   - Visualization of weights connecting hidden layers to the output provides interpretability.

## **Results**

The project achieves high classification accuracy, effectively identifying handwritten digits. Visualization techniques such as heatmaps and weight mappings reveal the network's learning process and insights into feature detection.

## **Repository Contents**

- **Python Scripts**: Includes all scripts for data preprocessing, model building, training, and evaluation.
- **Dataset**: The `dataset.mat` file used for handwritten digit recognition.
- **Documentation**: The PDF file `Final-Report.pdf` in this repository contains the complete report with detailed explanations.



