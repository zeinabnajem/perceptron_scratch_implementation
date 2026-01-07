# Perceptron Scratch Implementation

## 📌 Project Overview
To deepen my understanding of how neural networks make predictions, I implemented a **Perceptron classifier from scratch**.

---

## 🧠 Concept
The Perceptron is a **linear classifier** and represents the simplest form of a neural network.  
By implementing it manually, this project focuses on understanding:
- The learning rule
- Weight and bias updates
- Linear decision boundaries
- Model evaluation on unseen data

---

## 📊 Dataset
- **Iris Dataset**
- Features: Two selected numerical features
- Target: Class labels
- The dataset is split into **training** and **test** sets

---

## ⚙️ Project Workflow
1. Import required Python libraries  
2. Implement the `Perceptron` class from scratch  
   - Weight initialization  
   - Bias term  
   - Activation function  
   - Learning rule  
3. Load the Iris dataset  
4. Extract feature matrix (X) and target labels (y)  
5. Initialize a Perceptron with **two input features**  
6. Train the model on the **training set**  
7. Generate predictions on the **test set**  
8. Evaluate performance using **classification metrics**  
9. Visualize the **Perceptron decision boundary**

---

## 📈 Evaluation
Model performance is evaluated using:
- Accuracy
- Precision
- Recall
- F1-score

A visualization of the decision boundary is included to show how the Perceptron separates classes.

---

## 🛠️ Technologies Used
- Python  
- NumPy  
- Matplotlib  
- Scikit-learn 

---

## 📦 Requirements
All required packages are listed in the `requirements.txt` file.  
You can install them using:

```bash
pip install -r requirements.txt
