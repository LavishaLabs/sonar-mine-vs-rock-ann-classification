# SONAR Mine vs Rock Classification using ANN

## Project Overview

This project uses an Artificial Neural Network (ANN) to classify underwater sonar signals as either:

- Mine (M)
- Rock (R)

The model is trained using the SONAR dataset and implemented using TensorFlow/Keras.

---

## Business Objective

The goal of this project is to build an intelligent sonar classification system capable of identifying dangerous underwater mines and distinguishing them from harmless rocks.

Applications include:

- Maritime safety
- Naval defense
- Underwater object detection
- Resource exploration

---

## Dataset Information

- Total Samples: 208
- Features: 60 numerical sonar frequency values
- Classes:
  - M → Mine
  - R → Rock

Each feature represents energy measurements from sonar signals reflected by underwater objects.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- TensorFlow
- Keras
- Google Colab

---

## Project Workflow

1. Data Loading
2. Data Exploration
3. Missing Value Check
4. Data Normalization
5. ANN Model Building
6. Model Training
7. Model Evaluation
8. Manual Hyperparameter Tuning
9. Performance Comparison

---

## ANN Architecture

- Input Layer: 60 neurons
- Hidden Layer: 32 neurons
- Output Layer: 1 neuron

Activation Functions:
- ReLU
- Sigmoid

---

## Evaluation Metrics

The following metrics were used:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

## Hyperparameter Tuning

Manual hyperparameter tuning was performed by experimenting with different hidden neuron sizes:

- 16 neurons
- 32 neurons
- 64 neurons

The configuration with the best accuracy was selected as the optimized model.

---

## Results

The ANN model successfully classified sonar signals into mines and rocks with good accuracy.

Hyperparameter tuning improved overall classification performance.

---

## How to Run

### Clone Repository

```bash
git clone https://github.com/your-username/sonar-mine-vs-rock-ann-classification.git
