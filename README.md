# Waste Classification with CNN

This project uses a Convolutional Neural Network (CNN) to classify waste into different categories using image data. The model is implemented in TensorFlow/Keras and trained on labeled image datasets.

# **Waste Material Segregation for Improving Waste Management**
## **Objective**

The objective of this project is to implement an effective waste material segregation system using convolutional neural networks (CNNs) that categorises waste into distinct groups. This process enhances recycling efficiency, minimises environmental pollution, and promotes sustainable waste management practices.

The key goals are:

* Accurately classify waste materials into categories like cardboard, glass, paper, and plastic.
* Improve waste segregation efficiency to support recycling and reduce landfill waste.
* Understand the properties of different waste materials to optimise sorting methods for sustainability.

## 📁 Files

- `CNN_Waste_Segregation_RaghavMishra.ipynb`: Jupyter Notebook containing model definition, training, evaluation, and visualization.

## 🧠 Model Architecture

### 🧠 Model Summary
- CNN with multiple Conv2D + MaxPooling2D layers
- Uses BatchNormalization and Dropout for regularization
- Final layer with `softmax` activation for multi-class classification

## ⚙️ Training Details

### ⚙️ Training Configuration
- Optimizer: Adam
- Loss: Categorical Crossentropy
- Metrics: Accuracy
- Includes validation split and plots for `val_loss` and `val_accuracy`

## 📈 Visualization

The notebook also includes training and validation plots to visualize the model's performance over epochs.

---

## ✅ Requirements

- Python 3.8+
- TensorFlow 2.x
- NumPy, Matplotlib
- Jupyter Notebook
